<img src="./Images/MemLabs-logo.png" alt="MemLabs" class="center">
---

## **Table of contents**

1. [About MemLabs](https://github.com/stuxnet999/MemLabs#About-MemLabs)
2. [Motivation](https://github.com/stuxnet999/MemLabs#motivation)
3. [Structure of Repository](https://github.com/stuxnet999/MemLabs#structure-of-the-repository)
4. [Tools and Frameworks](https://github.com/stuxnet999/MemLabs#tools-and-frameworks)
5. [Flag Submission](https://github.com/stuxnet999/MemLabs#flag-submission)
   - [Email Format](https://github.com/stuxnet999/MemLabs#email-format)
6. [Resources](https://github.com/stuxnet999/MemLabs#resources)
7. [Feedback & suggestions](https://github.com/stuxnet999/MemLabs#feedback--suggestions)
8. [Usage](https://github.com/stuxnet999/MemLabs#usage)
9. [Author](https://github.com/stuxnet999/MemLabs#author)

## **About MemLabs** :mag:

MemLabs is an educational, introductory set of CTF-styled challenges which is aimed to encourage students, security researchers and also CTF players to get started with the field of **Memory Forensics**.

## **Motivation** :dart:

The main goal of creating this repository was to provide a reliable platform where individuals can learn, practice and enhance their skills in the field of memory forensics. As of the CTF-style, well, what better & interesting way to learn security than by playing CTFs?

I also believe these labs can be used by anyone to help others become good with the essentials and fundamentals of memory forensics.

## **Structure of repository**

| Directory | Challenge Name | Level Of Difficulty |
|:----:|:----:|:----:|
|Lab 0 | [Never Too Late Mister](./Lab%200) | Sample challenge |
|Lab 1 | [Beginner's Luck](./Lab%201) | Easy |
|Lab 2 | [A New World](./Lab%202) | Easy |
|Lab 3 | [The Evil's Den](./Lab%203) | Easy - Medium |
|Lab 4 | [Obsession](./Lab%204) | Medium |
|Lab 5 | [Black Tuesday](./Lab%205) | Medium - Hard |
|Lab 6 | [The Reckoning](./Lab%206) | Hard |

To aid first-timers to understand how to approach CTF challenges & usage of volatility, please refer [Lab 0](https://github.com/stuxnet999/MemLabs/tree/master/Lab%200) which comes with a elaborate walkthrough & I hope it will be a great way to start MemLabs!

All the memory dumps are that of a Windows system.

> **Note**: The level of difficulty specified may not be fully accurate as it depends on the individual. I've tried my best to categorize them after receiving feedback from beginners to the field.

## **Tools and frameworks** :hammer_and_wrench:

I'd suggest everyone use [**The Volatility Framework**](https://github.com/volatilityfoundation/volatility/) for analysing the memory images.

Please execute the [**setup.sh**](./setup.sh) file to install all the required dependencies in your system.

> **Note**: Windows users can download the executable file from [here](https://www.volatilityfoundation.org/26).

As these labs are quite introductory, there is no need for installing more tools. However, if the user wishes, they can install many other forensic tools.

The preferred OS would be Linux. However, you can also use Windows (WSL) or macOS.

## **Flag submission** :triangular_flag_on_post:

Please mail the flags of each lab to <memlabs.submit@gmail.com>

Please have a look at the following example to better understand how to submit the solution.

Suppose you find 3 flags in a particular lab,

+ flag{stage1_is_n0w_d0n3}
+ flag{stage2_is_n0w_d0n3}
+ flag{stage3_is_n0w_d0n3}

Concatenate all the flags like this: **flag{stage1_is_n0w_d0n3} flag{stage2_is_n0w_d0n3} flag{stage3_is_n0w_d0n3}**

**Note**: Place the flags in the right order. The content inside the flags indicates their place. The flags must be space-separated.

All the labs will follow the same flag format unless specified otherwise.

### **Email format**

Please follow the following guidelines when sending the solution. Below is a sample:

**Email Subject**: [MemLabs Solution Submission] [Lab-x]

> **x** indicates the Lab number. Ex: 1,2,3 etc..

![Email-Picture](./Images/Submission.png)

Email your solution to memlabs.submit@gmail.com

If the solution is correct, then the participant will receive a confirmation mail.

## **Feedback & suggestions**

I'd love the community's feedback regarding these labs. Any suggestions or improvements are always welcome. Please email it to me or contact my via Twitter: [@_abhiramkumar](https://www.twitter.com/_abhiramkumar).

## **Resources** :rocket:

This section contains resources which I've composed myself and some others which I have used when I learnt memory forensics. I hope this resources will help everyone in not only solving these labs but also in exploring more areas in memory forensics.

+ [**Basics of Memory Forensics**](https://stuxnet999.github.io/volatility/2020/08/18/Basics-of-Memory-Forensics.html)
+ [**Volatility Windows Command Reference**](https://github.com/volatilityfoundation/volatility/wiki/Command-Reference)
+ [**Sans DFIR Memory Forensics cheat sheet**](https://digital-forensics.sans.org/media/volatility-memory-forensics-cheat-sheet.pdf)

If you're interested to play more CTFs or want to try more challenges,
+ [**AboutDFIR - Challenges & CTFs**](https://aboutdfir.com/education/challenges-ctfs/)
+ [**CTFtime.org**](https://ctftime.org/)

## **Usage**

MemLabs is completely free to anyone to use. If you wish to use MemLabs in your workshops, classes or use the labs anywhere else, it is my humble request to you to use the original links to the labs and please mention my name as well. For any other queries, please contact me.

## **Author** :bust_in_silhouette:

P. Abhiram Kumar

Digital Forensics, [**Team bi0s**](https://www.twitter.com/teambi0s)

+ Mail: **abhiram1999@gmail.com**
+ Twitter: [**@_abhiramkumar**](https://www.twitter.com/_abhiramkumar)
+ Personal Blog: [**stuxnet999.github.io**](https://stuxnet999.github.io)