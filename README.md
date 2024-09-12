# Lab1

How to set up the environment:
- download all the files from this repo. aside from out directory since thats just output
- get hamcrest and junit
- make a src directory 
- within that make c and u directories
- put all the code files into c
- put the testfile with unit tests into u
- view screenshot on my Lab report if needed. (video and instructions show how it runs too if needed)
 
 How to compile/run the code:

Step 1 : Compile ALL the java files using:
- javac -cp junit-4.13.2.jar:hamcrest-core-1.3.jar -d ./out ./src/c/*.java ./src/u/*.java

Step 2 : Run CarRunner.java by using:
- java -cp ./out c.CarRunner

Step 3 : Run the Unit tests: 
- java -cp junit-4.13.2.jar:hamcrest-core-1.3.jar:./out org.junit.runner.JUnitCore u.TestMeTests 
