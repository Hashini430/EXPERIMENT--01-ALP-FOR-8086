# EXPERIMENT--01-ALP-FOR-8086
## Name :HASHINI R
## Roll no :212224240055





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
mov  al,60h
mov bl,20h
add al,bl
ret
```

## Output <img width="1218" height="794" alt="image" src="https://github.com/user-attachments/assets/646bc87b-2637-44d8-b863-cb16505fe945" />



 
## Subtraction   of 8 bit numbers  ALP 
```
mov al,60h
mov bl,20h
sub al,bl
ret
```
 
## Output  
<img width="1375" height="833" alt="image" src="https://github.com/user-attachments/assets/05fa7bff-db89-4471-8e83-e40a2ae72498" />

## Multiplication alp 
```
mov al,60h
mov bl,20h
mul bl
ret
```
 ## Output  
<img width="1204" height="826" alt="image" src="https://github.com/user-attachments/assets/cd4944a1-2bce-4998-a716-9d360eb643d2" />



## Division alp 
```
mov al,60h
mov bl,20h
div bl
ret
```

## Output  
<img width="1291" height="911" alt="image" src="https://github.com/user-attachments/assets/69befd16-705d-454f-ad1d-af82b9123a5c" />



## AND  alp 
```
MOV AL, 53H;
MOV BL, 24H;
AND AL,BL;
HLT
```

## Output  
<img width="1446" height="939" alt="image" src="https://github.com/user-attachments/assets/df52ca84-637c-4b00-b52b-f017d09a706d" />



## OR  alp 
```
MOV AL, 53H;
MOV BL, 24H;
OR AL, BL;
HLT
```

## Output  
<img width="1880" height="931" alt="image" src="https://github.com/user-attachments/assets/b6aa40ee-6f29-4a56-825b-86c884a08714" />



## NOT alp 
```
MOV AL, 53H;
MOV BL, 24H;
NOT AL;
HLT
```

## Output  
<img width="1188" height="732" alt="image" src="https://github.com/user-attachments/assets/de8ab641-502a-434a-9412-58924d6361e8" />


## XOR alp 
```
MOV AL, 53H;
MOV BL, 24H;
XOR AL, BL;
HLT
```

## Output  
<img width="1254" height="775" alt="image" src="https://github.com/user-attachments/assets/ca802d39-871b-450f-bdce-ad792e327be2" />


## NAND alp 
```
MOV AL,53H
MOV BL,24H
AND AL,BL
NOT AL
```

## Output  

<img width="1235" height="816" alt="image" src="https://github.com/user-attachments/assets/cbcc37d8-f432-4996-8e71-5e4341a5e984" />




## Result :

 








