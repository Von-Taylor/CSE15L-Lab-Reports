# Lab Report Week 9
- **HTML Link:** [https://von-taylor.github.io/cse15l-lab-reports/lab-report-week-9.html](https://von-taylor.github.io/cse15l-lab-reports/lab-report-week-9.html)

## grade.sh:
```
# Create your grading script here

# set -e

rm -rf student-submission
git clone $1 student-submission
GRADE=0

# check if ListExamples.java exists
cd student-submission
if [ -f ListExamples.java ]
then
    echo "ListExamples.java file found"
else
    echo "ListExamples.java file not found"
    echo "Grade is: "$GRADE
    exit 1
fi

cd ..
cp -r lib student-submission/
cp TestListExamples.java student-submission/
cd student-submission
javac -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar *.java

# check that the compile went fine
if [ $? -eq 00 ]
then
    echo "Compilation succeeded"
else
    echo "Compilation failed"
    echo "Out of 3, you grade is: "$GRADE
    exit 1
fi

java -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar org.junit.runner.JUnitCore TestListExamples

if [ $? -eq 00 ]
then
    GRADE=3
    echo "You passed all the tests!"
    echo "Out of 3, you grade is: "$GRADE
else
    echo "You failed some tests"
    echo "Out of 3, you grade is: "$GRADE
fi
```

## Screenshots of **three** different student submissions and their reported grade as loaded in the browser:
> Sample Submission 1: https://github.com/ucsd-cse15l-f22/list-methods-lab3
> ![sample1](Week-9-Lab-Reports-Pics/sample1.jpg)

> Sample Submission 2: https://github.com/ucsd-cse15l-f22/list-methods-corrected
> ![sample2](Week-9-Lab-Reports-Pics/sample2.jpg)

> Sample Submission 3: https://github.com/ucsd-cse15l-f22/list-methods-compile-error
> ![sample3](Week-9-Lab-Reports-Pics/sample3.jpg)
