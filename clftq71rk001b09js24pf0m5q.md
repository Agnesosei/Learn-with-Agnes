---
title: "C Programming"
datePublished: Wed Mar 29 2023 13:31:39 GMT+0000 (Coordinated Universal Time)
cuid: clftq71rk001b09js24pf0m5q
slug: c-programming
tags: c

---

**Why not?**

If you are reading this article, I believe it is safe to assume that you understand English. I am communicating with you right now in English. Just as humans have their own languages, so do computers. If I want you to buy me an orange, I would simply say: "buy me an orange". You may or may not do as I asked, but you would definitely understand me. However, communicating with your computer goes beyond using your everyday sentences. Your computer only understands zeros and ones, also known as binary. If you want to give your computer any instruction, you must speak binary. Just kidding... You will need a way to convert your instruction into binary, which we will henceforth refer to as machine code. Still, this does not mean you can just write your everyday English and have it converted into machine code... no sir. You will write your instruction in a programming language which is readable to humans, henceforth known as source code, but needs to be compiled into machine code.

Source code can be written in many languages. Each language has its own syntax and rules. Examples of languages include Python, JavaScript, the good old C, among many others.

The C language has been around for many years, thanks to Dennis M. Ritchie who built upon Ken Thompson's B language.

Today, most programming languages and operating systems are built on C. If you want a deeper understanding of the code you are writing in any language, learning C will be a good bet. Who knows? You might end up building your own new language or helping to improve upon existing ones!

## How to start programming in C

To start programming in C, we would first need a text editor. If you were thinking Microsoft Word, repent - Notepad would be a better option. What we need is a plain editor like **vim, emacs or notepad**. Other editors like VScode are also freely available for download. We will type our source code in this text editor, after which we will save the file with a **.c** extension. For example, to create a C file named agnes, we will save it as **agnes.c** .

After creating our file, we will need a compiler to convert our source code to machine code. The compiler we will be using in this series is the gcc compiler. However, feel free to use [Replit](http://www.replit.com) if you do not need to install a compiler just yet. You could also install **codeblocks**, which will come with both an editor and a compiler. For now, do not worry about these.

## Compilation Process

Because C is a compiled language, our source code in our .c file will go through a number of stages before it finally becomes an executable file. Let's say we have our source code in a file called **agnes.c** .

**The first is the preprocessing stage**. Here the preprocessor will obey directives given in our header file in agnes.c; then remove comments and expand macros. Don't worry if you do not know what a header file is. We will come back to it in subsequent lessons.

Next, the **actual compilation** is done. This is where the source code in agnes.c is checked for syntax and semantics and then converted into an intermediate language or an assembly code, also known as object code.

Then, the code goes through the **assembling stage**. Here, the assembly code is converted into machine code, also known as object code.

Finally, agnes.c will go through the linking stage, where all object codes are linked and library files are included to produce an executable file.

Our executable file will no longer be called agnes.c. If we compiled our source code without specifying an output name, the executable file will be known as a.out. However if we specified a name, then that will be the name of our new file. For example if we compiled agnes.c this way: `gcc agnes.c -o agnes`, our executable file will be called agnes. You will understand this more as we look at further lessons.

I hope you enjoyed this lesson.

In our next lesson, we will be writing and compiling our first C program.

Thank you for joining me on this learning journey. Please do comment and send me hi on [Twitter](https://twitter.com/agadosei).

Until we meet again in our next lesson, happy learning!