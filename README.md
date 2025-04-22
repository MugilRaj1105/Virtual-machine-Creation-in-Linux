 # VIRTUAL MACHINE CREATION IN LINUX
  ## AIM
       To Install Virtualbox / VMware Workstation with different flavours of linux.
## PROBLEM STATEMENT
    Explain about the Experiment.

## ALGORITHM
steps 1:
open the terminal in Kali Linux.

Steps 2:
Use basic Linux commands to navigate and mangae files.

Steps 3:
Create a Bash script using Mousepad.

Steps 4:
Write a script that performs arithmetic operations and reads a file.

Steps 5:
Make the script executable.

Steps 6:
Run the script and observe the output.
## COMMANDS
Execute Basic Linux Commands in the Terminal
Check the Current Working Directory
```
pwd
```
Create a New Directory
```
mkdir my_experiment
```
Navigate into the Directory
```
cd my_experiment
```
List the Files in the Directory
```
ls`
```
Write Some Text into the File
```
echo "Hello, this is a test file." > myfile.txt
```
Read the File Contents
```
cat myfile.txt
```
Get the Current Date and Time
```
date
```
Writing a Bash Script in Mousepad
Open Mousepad
```
mousepad myscript.sh &
```
Write the Bash Script
```
#!/bin/bash 

echo "Current Directory:"
pwd

echo "Files in this directory:"
ls

echo "Current Date and Time:"
date

read -p "Enter first number: " num1
read -p "Enter second number: " num2

sum=$((num1 + num2))
diff=$((num1 - num2))
prod=$((num1 * num2))
quot=$((num1 / num2))
rem=$((num1 % num2))

echo "Sum: $sum"
echo "Difference: $diff"
echo "Product: $prod"
echo "Quotient: $quot"
echo "Remainder: $rem"
```
Make the Script Executable
```
chmod +x myscript.sh
```
Run the Script
```
./myscript.sh
```
## OUTPUT
REG NUMBER:212223220062
NAME:MUGIL RAJ S A
Configuration of Kali Linux on Oracle Virtual Box :
![image](https://github.com/user-attachments/assets/0089b19a-d9af-4cf1-82a5-6095667dd881)
![image](https://github.com/user-attachments/assets/34bbdc04-d5c5-4e01-8710-e151cbe5c5e1)
## RESULT
 Thus, this experiment helped in understanding the fundamentals of Linux commands and Bash scripting for automation and system management.

  


