# Lab Report 5

## 1 original post
```
Symptom: The first image is showing a failed test case in Junit. 

Description of a guess at the bug: It might be a bug in the code of the second image. It suggests that after an operation, an element in the deque that was expected to be 1 is instead null. This might related to the condition of the deque when expandCapacity is called. Given that the error occurs after expandCapacity, it suggests that the elements are not being copied correctly into the new array.
```
![Image](lab5-1.png)
![Image](lab5-2.png)

## 2 response
a leading question: why do you think the element becomes null? Can you check your logic of the the loop that copies the elements. Is it iterating through the entire array? is there an issue with the index calculations?

## 3 try
![Image](lab5-3.png)
```
Description of what the bug is: To fix the bug, I went back to the expand method to see the logic of the loop. I discovered that it will not include the element at index size - 1 and this is what causes the last element of the array to be missing in the new array after expansion.
```

## 4 setup
all the information needed about the setup:
```
The file & directory structure needed:
```
![Image](lab5-4.png)
```
the content of each file before fixing the bug: it has too many files and it is not very possible to copy and paste all of them here. I have provided the basic setup of what files are included. 
```
```
The full command line (or lines) you ran to trigger the bug: bash test.sh to run the Junit test:
javac -cp ../libs/junit-4.13.2.jar:../libs/hamcrest-2.2.jar:. PublicTester.java
java -cp ../libs/junit-4.13.2.jar:../libs/hamcrest-2.2.jar:. org.junit.runner.JUnitCore PublicTester
```
```
A description of what to edit to fix the bug:it is included in the step3
```


