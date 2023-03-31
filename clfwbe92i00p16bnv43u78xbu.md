---
title: "Our First Program in C"
datePublished: Fri Mar 31 2023 09:00:39 GMT+0000 (Coordinated Universal Time)
cuid: clfwbe92i00p16bnv43u78xbu
slug: our-first-program-in-c
tags: c

---

Yaaay!

Isn't it exciting? We are about to write our very first program. Watch out y'all! This should be fun!

As we saw in our previous lesson, we will need to write our source code in a plain text editor which should be saved with a.c extension. The compiler will then turn our code into machine code.

Are you ready?

Open your text editor. You can use [this.](https://www.replit.com) If you were using your own editor, you would have to ensure that you create a new file with a **.c** extension.

Next, tell the computer what anything you want… Go on, try it! Type "hey computer, what's up?" What do you think would happen if we ran this program?

OK. Let's be serious.

In your text editor, type the following code exactly as you see it here. Try as much as possible not to copy it. Why? Because we are learning! What kind of programs would we produce if we don't even know how to type our own code? As a learner, it is better to type it out yourself in the early stages before you become an expert who doesn't even know how "Hello World" is written.

```c
#include <stdio.h>
/*My first C program*/
int main(void)
{
    printf("Hey Agnes, Let's learn together\n");
    return (0);
}
```

### Compiling and Debugging

Since you are using the [online terminal](https://www.replit.com), click "run".

If you were using your local environment, you would compile it with GCC as we saw in the last lesson. For example, if this program was saved as agnes.c, you would type this in your terminal : `gcc agnes.c -o agnes.`

It is now time for our compiler to check our code and translate it into a language our computer can understand. Shoot! Did the compiler return an error message? Check what you typed again. Are you sure you typed exactly what I asked you to type? Check again. Let's look at your first line.

`#include <stdio.h>`. Are you sure you typed `stdio` and not studio? Oh, don't worry. It's a common error.

The first line `#include <stdio.h>` tells our compiler to literally include the standard input/out header. We will look more into this in subsequent lessons.

The next line is just a comment. We just added it to remind ourselves of what on earth we were trying to do with our code. It is not really part of the code, and can be omitted; but for your own sake, please don't. Our compiler will remove our comments from the message it's sending to the computer.

Wait. Did you get another error message? Let's see… Check whether you put a semi-colon at the end of your `printf` line (henceforth known as a statement). Was that it? Don't beat yourself. These errors are normal.

Now, compile your program again.

What happened? Nothing? Believe me when I say that it is a good thing. Your program has been created; but how do you know?

If you are using an [online compiler](https://replit.com), you will see Hey Agnes, Let's learn together printed on the output screen. However, if you manually typed `gcc` in your terminal, you will will need an extra step to see the output. Check the folder (directory) in which your C file was stored. You should find an executable file named **agnes.** If it's not there, perhaps you will find **a.out**.

Remember in our last lesson, we mentioned that if you do not specify a name for your output, the compiler will name it a.out.

Now (in your Linux terminal), type `./agnes` or `./a.out` depending on your output name. You should see `Hey Agnes, Let's learn together` printed.

Well done! You have successfully created your first C program.

However, if you are still getting errors, go through your code line by line. Have you spelt every word correctly? For example, `printf` not pprint or print or sprintf or printf…

Next, check your punctuations. The semicolons at the end of the `printf` statement and the return statement are very important. Then check your parentheses. About three different types have been used so far: {The curly braces}, (the brackets), and &lt;the angle brackets&gt;.

Make sure each of them both opens and closes.

Finally, check your quotation marks. Everything okay now? Good job!

Sometimes, you won't get any error message from the compiler; but your program still won't give you the output you were hoping for. Go through your code line by line and find the error.

You know what you just did? Debugging! That's right. You just removed the bugs in your code. There's more to debugging. We will understand better as we move on; but for now, I hope you can understand when someone says there's a bug in their code.

There's another thing we haven't looked at today: "\\n". Let's look more closely at the backslash n and others in our next lesson. We will also look more at the standard input / output header.

Thank you for joining me on this learning journey. Let's meet again in our next lesson.