# EXPERIMENT--01-ALP-FOR-8086

Name :KARTHIKEYAN P

Roll no : 212223230102

Date of experiment : 20/8/2024





## Aim: To Write and execute ALP on fundamental arithmetic and logical operations
## Components required: 8086  emulator 
## Theory 
Running The Emulator (emu8086) Intro 8086 Microprocessor Emulator, also known as EMU8086, is an emulator of the program 8086 microprocessor. It is developed with a built-in 8086 assembler. This application is able to run programs on both PC desktops and laptops. This tool is primarily designed to copy or emulate hardware. These include the memory of a program, CPU, RAM, input and output devices, and even the display screen. There are instructions to follow when using this emulator. It can be executed into one of the two ways: backward or forward. There are also examples of assembly source code included. With this, it allows the programming of assembly language, reverse engineering, hardware architecture, and creating miniature operating system (OS). The user interface of 8086 Microprocessor Emulator is simple and easy to manage. There are five major buttons with icons and titles included. These are “Load”, “Reload”, “Step Back”, “Single Step”, and “Run”. Above those buttons is the menu that includes “File”, “View”, “Virtual Devices”, “Virtual Drive”, and “Help”. Below the buttons is a series of choices that are usually in numbers and codes. At the leftmost part is an area called “Registers” with an indication of either “H” or “L”. The other side is divided into two, which enables users to manually reset, debug, flag, etc. What is 8086 emulator emu8086 is an emulator of Intel 8086 (AMD compatible) microprocessor with integrated 8086 assembler and tutorials for beginners. Emulator runs programs like the real microprocessor in step-by-step mode. it shows registers, memory, stack, variables and flags.


 ## Running the Emulator :
1.	Download and install emu8086 (www.emu8086.com) It is usually installed in C:\EMU8086 subfolder in the “Windows” directory
2.	  Run  emu8086 icon (on the desktop or in the c:\EMU8086 folder of window) It has green color 
 
 
3.		write the code for the appropriate program for ADDITION,SUBTRACTION, MULTIPLICATION,  DIVISION operations 

4.	 Compile the program and check for the errors 
5.	Run (once there is no syntax error) 

6.	Click OK to see/view the output of your program on the Emulator screen. 


7.	After running the program, another menu screen will be displayed, where you have the option to “View” symbol table,
8.	 


![image](https://user-images.githubusercontent.com/36288975/189273263-d65baae9-4b8f-4723-afb3-c0ffa4052b04.png)











9.	Click on emulate to start emulation 








![image](https://user-images.githubusercontent.com/36288975/189273273-9bb36ec1-e2e8-4892-8d35-37707332bfdc.png)








10.	If no errors are found click on run the program and check the status of various flags in the flags tab as shown below 






![image](https://user-images.githubusercontent.com/36288975/189273277-113a2a33-4a40-4ff8-95a5-ecd3a1f504fe.png)







## Programs for arithmetic  operations

## Addition  of 8 bit ALP 
```
org 100h

mov al,0046h 
mov bl,0056h
add al,bl
mov [6366h],al

ret
```
## Output  
 ![image](https://github.com/user-attachments/assets/ff71942f-d4f9-4c0e-a533-97cb1b5ad132)

## Subtraction   of 8 bit numbers  ALP 
```
org 100h

mov ax,0046h 
mov bx,0056h
sub ax,bx;
mov [6378h],ax

ret
```
## Output  
![image](https://github.com/user-attachments/assets/2f22a1a9-6a3b-4e3d-a71a-b3e211929533)

## Multiplication alp 
```
org 100h

mov ax,0046h 
mov bx,0056h
mul bx;
mov [6367h],ax

ret
```
 ## Output  
![image](https://github.com/user-attachments/assets/18c055a5-9bc5-46ce-bc8e-f508355f8de4)


## Division alp 
```
org 100h

mov ax,0046h 
mov bx,0056h
div bx;
mov [6355h],bx

ret
```
## Output  
![image](https://github.com/user-attachments/assets/1d9a76f1-9405-4c8d-aad8-2832d7718439)

## OR Operation
```
org 100h

mov ax,0046h 
mov bx,0056h
or ax,bx

ret
```
## Output
![image](https://github.com/user-attachments/assets/da18a0eb-705b-424f-8a3c-c93cb49c8797)


## AND Operation
```
org 100h

mov ax,0046h 
mov bx,0056h
and ax,bx

ret
```
## Output
![image](https://github.com/user-attachments/assets/4166db7c-9a51-44aa-9436-a744fb0227d9)

## NOT Operation
```
org 100h

mov ax,0046h 
not ax

ret
```
## Output
![image](https://github.com/user-attachments/assets/753e1342-b004-4c9a-aa98-6d5e618431e9)

## XOR Operation
```
org 100h

mov ax,0046h 
mov bx,0056h
xor ax,bx

ret
```
## Output
![image](https://github.com/user-attachments/assets/52cb261b-872b-48e3-aab2-784c113088b3)


## Result :

 Thus, ALP for fundamental arithmetic and logical operations are executed successfully








