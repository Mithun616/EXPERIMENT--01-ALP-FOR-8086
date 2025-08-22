# EXPERIMENT 01 ALP FOR FUNDAMENTAL AND ARITHMETIC OPERATIONS USING 8086
Name : Mithun Kumar.G
Roll no : 212224230160
Date of experiment : 22-08-2025





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
~~~
org 100h
mov ax,2345h
mov bx, 4444h
add ax,bx
ret

org 100h
mov ax, 1003h;
mov bx, 1004h;
mul bx
div bx
ret
~~~
## Output for arithmetic oprtation
<img width="1515" height="751" alt="Screenshot 2025-08-21 213920" src="https://github.com/user-attachments/assets/3d7cfebc-af88-4998-b7fa-eae802093651" />

<img width="1757" height="659" alt="Screenshot 2025-08-21 214447" src="https://github.com/user-attachments/assets/ed94ba6b-a986-48b1-9fe1-f4c290beba10" />

## Programs for logical  operations  
~~~
org 100h
mov bx,1000h
mov cx,1002h
mov ax,[bx]
mov dx,cx
and ax,dx
or  cx,dx
ret

org 100h
mov bx,1000h
mov cx,1002h
mov ax,[bx]
mov dx,cx
xor ax,dx
not ax
ret
~~~
 
## Output for logical operations 

<img width="1522" height="829" alt="Screenshot 2025-08-21 214040" src="https://github.com/user-attachments/assets/ceff3605-c1c3-4dfc-a984-7a7e4ddb8fde" />

<img width="1571" height="914" alt="Screenshot 2025-08-22 092440" src="https://github.com/user-attachments/assets/08032a74-4834-496e-83e0-cb0704d46e6d" />

## Result :

The program was executed successfully








