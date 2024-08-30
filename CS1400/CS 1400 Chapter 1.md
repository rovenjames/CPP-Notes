## Table of Contents
- [Table of Contents](#table-of-contents)
- [Computer Systems: Hardware](#computer-systems-hardware)
    - [ Computer Block Diagram ](#-computer-block-diagram-)
- [Computer Systems: Hardware Central Processing Unit](#computer-systems-hardware-central-processing-unit)
    - [ CPU Diagram ](#-cpu-diagram-)
- [Hardware Main Memory](#hardware-main-memory)
- [Hardware Secondary Storage Devices](#hardware-secondary-storage-devices)
- [Hardware Input Devices](#hardware-input-devices)
- [Hardware Output Devices](#hardware-output-devices)
- [Computer Systems: Software](#computer-systems-software)
- [Programming Languages](#programming-languages)
- [Programming Languages: Common Language Elemnents](#programming-languages-common-language-elemnents)
- [Java Sample Program](#java-sample-program)
  - [Key Words](#key-words)
  - [Punctuation](#punctuation)
  - [Lines vs. Statements](#lines-vs-statements)
  - [Variables](#variables)
  - [JVM](#jvm)
- [C++ Sample Program](#c-sample-program)
- [Compiler and the JVM](#compiler-and-the-jvm)


## Computer Systems: Hardware

- Computer hardware components are the physical pieces of the computer
- The major hardware components of a computer are:
    - The central processing unit (CPU)
    - Main memory
    - Secondary storage devices
    - Input and output devices
#### <u> Computer Block Diagram </u>

![Computer Block Diagram](https://lucid.app/publicSegments/view/668c4f02-3ba6-48cf-9f80-c5d1b9712f07/image.png)

## Computer Systems: Hardware Central Processing Unit

#### <u> CPU Diagram </u>
<img src="https://lucid.app/publicSegments/view/2b928257-aa68-4546-9c50-2c56b210912d/image.png" width="700">

- The CPU performs the **fetch, decode, execute cycle** in order to process program information
> CPU will fetch the next instruction in the sequence of program instructions from the main memory.\
> Instruction is then decoded (originally encoded in the form of a number), generating an electronic signal.\
> Signal is then routed to the apprporiate component of the computer, causing it to perform an operation.\


## Hardware Main Memory
- Commonly known as **random-access memory \(RAM\)**
- RAM contains:
    - currently running programs
    - data used by those programs
- RAM is divided into units called bytes
- A byte consists of eight bits that may be either on or off
- Bit is either on or off
    - 1 = ON
    - 0 = OFF
- Bits form a pattern that represents a character or number
- Each byte is assigned an address, unique to each byte
> RAM is **volatile** which means that when the computer is turned off, the contents of RAM are erased\.
>
>Memory is moved over to **second-hand memory** which is then translated to the main memory when computer is turned on\.

Main memory can be visulaized as a column or row of cells.\
A section of two or four bytes is called a **word**

## Hardware Secondary Storage Devices
- Secondary storage devices are capable of storing information for longer periods of time **\(non-volatile\)**
- Common Secondary Storage Devices:
    - Disk drive
    - External drive
    - CD drive
    - Solid state drive
    - USB drive
    - DVD drive

## Hardware Input Devices
- Input is any data the compuer collects from the outside world
- That data comes from devices known as input devices
- Common input devices
    - Keyboard
    - Mouse
    - Scanner
    - Digital camera

## Hardware Output Devices
- Output is any datat the computer sends to the outside world
- That data is displated 

## Computer Systems: Software
- Software refers to the programs that ru on a computer\.
- There are two classifications of software:
    - **Operating Systems**
    - **Application Software**

>### Computer Systems: Software Operating Systems
>>An operating system is a set of programs that manages the computer's hardware devices and controls their processes
>>
>>Most all modern opearating systems are multitasking
>>
>>A multitasking operating system is capable of running multiple programs a t once
>>- Unix
>>- Linux
>>- MacOS
>>- Windows
>### Computer Systems: Software Application Software
>>Applciation software refers to programs that make the computer useful to the user
>>Application software provides a more specialized type of environment for the user to work in.
>>Common application software:
>>- Spreadsheets
>>- Word processors
>>- Accounting software
>>- Tax software
>>- Games
>  

## Programming Languages
- A program is a set of instructions a computer follows in order to perform a task
- A programming langauge is a special langauge used to write computer programs
- A computer program is a set of instructions that enable the computer to sovle a problem or perform a task
- Collectively, these instructions form an algorithim
- Algorithim is a set of well defined steps to completing a task
- The steps in an algorithim are performed sequentially
- A computer needs the algorithim to be written in machine language
- Machine langauge is written using **binary numbers**
- Binary numbers are encoded as a machine language
- Each CPU has its own machine language
    - Motorola processors
    - Intel x86 processors
    - ARM processors
- Before programming languages were developed, programmers had to program using machine language
- Following simple progeamming languages, high level programming languages were made which weren't processor dependent
- Common Programming Languages:
    - Java
    - BASIC
    - Go
    - Rust
    - C
    - C++
    - C#
    - Visual Basic
    - Python
    - Ruby
    - JavaScript

## Programming Languages: Common Language Elemnents
- Common conepts seen in virtually all programming languages:
    - Key words
    - Operators
    - Punctuation
    - Programmer-defined identifiers
    - Strict syntatic rules

## Java Sample Program

```java
{
    public class HelloWorld
    {
        public static void main(String[] args)
        {
            String message = "Hello World";
            System.out.println(message);
        }
    }
}
```
- Messages are called "statements" in Java.
- Most important statement: **"public static void main(String[] args)"**
### <u>Key Words</u>
- Key words in the sample program are:
    - public
    - class
    - static
    - void
- Key words are lower case (Java is case sensitive)
- Key words cannot be used as a programmer-defined identifier
### <u>Punctuation</u>
- Part of learning java is to learn where to properly use the punction.
### <u>Lines vs. Statements</u>
- There are differences between liens and statements when discussing source code.
```java
{
    System.out.println();
}
```
- This is a statement as it ends with a semi colon.
### <u>Variables</u>
- Data in a Kava program is stored in memory
- Variable names reperesent a location in memory
- Variabales in Java are sometimes called fields
- Variables are created by the programmer, assigning it a programmer-defined identifier
```java
{
    example: int hours = 40;
}
```
- Here, the variable "hours" is created as an integer, assigned the value of 40.
### <u>JVM</u>
- The Java Virtual Machine actually decides where the value will be placed in memory
- (insert JVM chart)

## C++ Sample Program
```c++
{
    #include <iostream>
    #include <string>

    int main()
    {
        string message = "Hello World";
        cout <<message>> endl;
    }
}
```
- Does the same thing as what the [Java Sample Program](#java-sample-program) is doing, except with a different syntax.
- Instead of "statements," messages are called "commands."

## Compiler and the JVM
- Java programming statements written by a programmer are known as **soruce code**
- A text editor is used to edit and save a Java source code file
- Source code files have a **.java** extension
<br></br>
- A compiler is a program that translates source code into an executable form
- Compilers are run using a source code file as input
- Syntax errors that may be in the program will be discovered during compilation
- Syntax errors are mistakes that the programmer has made that violate the rules of the programming language
- Compiler creates another file that holds the translated instructions
- Most compilers translate source code into executable files contatining machine code
<br></br>
- The Java compiler translates a Java source file into a file that contains **byte code instructions**
- Byte code instructions are the machine language of the JVM, it cannot be directly executed by the CPU
- Byte code files end with the **.classs** extension
<br></br>
- The JVM emulates a micro-processor
- JVM executes instructions as read
- The JVM is often called an interpreter
- Java is often referred to as an interpreted language