# General tips on becoming a better competitive coder - 

Regularly give contests, div2 or div3 contests are held on codeforces around twice a week. Be consistent. 

Don’t give up on a problem in 5-10 minutes, spend a decent amount of time on it before seeing the solution. After seeing the solution, try to code it yourself. 

No matter how many problems you solve in the contest, always try to solve one additional problem after the contest. Spend some time on it, and afterward, if you can’t, see the contest editorial. 

You should even see editorials of problems you have solved in the contest, you might learn something new.

# Setting Up -
You have a lot of choices to write and test your code locally, before submitting it to contests! Some people use a simple text editor such as NotePad and run their code on an online compiler. But most people set up a full fledged IDE (like VSCode/CLion) and use a compiler locally to test their code (GNU C++20 or Clang).

We too prefer the latter as it provides a plethora of features like multi-language support, intellisense, debugging, extensions, and countless other things that really speed up how fast you code.

Why MinGW? - We prefer MinGW over Clang, because Clang does not support important headers such as <bits/stdc++.h>

Why VSCode? - VSCode offers a great number of extensions, like Code Runner, Intellisense and especially CPH which is very helpful as you get better at competitive programming. But again, any other IDE would work just fine! (it's a matter of personal preference :))

So, here we have linked a video to provide you a walkthrough for setting up your C++ compiler (MinGW) and VSCode.

https://www.youtube.com/watch?v=j8nAHeVKL08

You need to watch this video from 10:45 till the end to set up your MinGW and VSCode.

# Language - 

C++ is the language of choice for competitive programmers, mainly because it’s the fastest (running time of your code is very important).

Java is slightly slower than C++, and you also have to write much more code, so I wouldn’t recommend it personally

Python requires much less code to write than Java or C++, but is slow. In basic/intermediate problems, this won’t matter much, but later on you will have to switch to C++. Recommended resource to learn - CoreySchafer (YouTube channel)

I personally started coding in Python and then switched to C++.

If you have no prior experience in coding, start from https://www.w3schools.com/

# Registration-

1.First go to Codeforces.

2.Click on the Register button on the top right corner.

3.Fill in the required credentials to create an account.

4.Use either your personal or BITS mail to make the account.You are done!


# Ebooks -

There are many, many great textbooks available. These two are my personal recommendations as I learnt from them.
An Introduction to The USA Computing Olympiad (comes in two versions - C++ or Java) - https://darrenyao.com/usacobook/cpp.pdf

Competitive Programmer’s Handbook - https://cses.fi/book/book.pdf

# Websites - 
https://cp-algorithms.web.app/ - one of the best websites to learn intermediate to advanced algorithms. It also contains a list of questions at the end of each topic that you can practice.

To learn a specific language or topic, more beginner oriented - https://www.hackerrank.com/
Questions for “standard” problems, intended for all levels (beginner to advanced) - CSES Problemset - https://cses.fi/problemset/

https://www.geeksforgeeks.org/ is a popular website, but not always reliable (I’ve found wrong code for a particular question multiple times) so be careful.

CodeNCode on YouTube, for those who prefer video lectures  - https://www.youtube.com/channel/UC0zvY3yIBQTrSutsV-4yscQ/about

https://www.learncpp.com/ is a website you can use to learn C++ in depth.

# Practice for beginners - 

Note that practice is extremely important. You can’t just learn a topic and expect to solve questions on it, it takes a lot of practice.

Questions on https://www.hackerrank.com/
Div3 contests on https://www.codeforces.com. 
Starter contests on https://www.codechef.com. 
Google Kickstart - https://codingcompetitions.withgoogle.com/kickstart

# Some basic topics - 
These are some of the concepts that you should know before starting intermediate topics like Graph Theory / Dynamic Programming. You can use this as a sort of checklist.

1.Assessing the time complexity of your code; knowing when a particular time complexity will work and when it will give TLE.

2.When and how to apply data structures such as Vector, Stack, Queue, Priority Queue, Set and Map

3.Sorting and searching

4.Greedy Algorithms

5.Basic number theory - 
Checking if a number is prime, 
Sieve of eratosthenes, 
finding GCD, 
finding prime factorization of a number, 
finding all divisors of a number, 
modular arithmetic including modular inverse

6.Bitwise operations such as AND, OR, XOR, Left shift and right shift; converting decimal to binary and vice versa

7.Binary Exponentiation

8.Binary Search

9.Two Pointers

10.Prefix Sums

# Extensions 
I use VSCode, it’s lightweight, flexible and has powerful extensions that can make coding easier. 

I’ve found the following extensions useful - 

Competitive Programming Helper by Divyanshu Agrawal
Code Runner by Jun Han
C/C++ by Microsoft for intellisense (25M+ downloads on VSCode)
Pitch Black Theme by Viktor Qvarfordt, my personal favourite colour theme :) 

Advanced - 
Sync your VSCode using your GitHub account and then you won’t have to set it up again, your settings will be saved.
Look up “User Snippets” in VSCode, you can use that feature to create custom snippets file for standard functions such as binary search, binary exponentiation, segment tree, etc.


# Compilers to use for different languages on coding platforms

While submitting solution to a problem, you are required to choose a compiler of your preference using which your code will be run, so, here we have listed suitable compilers for different languages -

For C use GNU GCC C11 5.1.0
For C++ use GNU G++17 7.3.0
For Java use Java 11.0.6
For Python use PyPy 3.7 (7.3.0) or Python 3.8.10

# Fast Input/Output methods for different languages

Why fast I/O?
For each question in contests, there is almost always a time-limit within which your code should finish execution on the online judge. Fast I/O helps to reduce the execution time of the code with some optimisations in especially large inputs/outputs.

For C++ -
scanf()/printf() work faster than cin/cout, so if you already use the prior (scanf()/printf()) for input/output then you should continue to do so.
If you use cin/cout and are reluctant to shift to scanf()/printf(), then you can attach a piece of code into your main() function, and cin/cout will now process much faster. (but still a bit slower than scanf()/printf())
Just paste the following inside of your main() function, and then use cin, cout normally as you would (recommended).
   std::ios::sync_with_stdio(false);
   cin.tie(0);
   cout.tie(0);

Example Code:https://pastebin.com/am1A6MLL
Read about it on https://www.geeksforgeeks.org/fast-io-for-competitive-programming/.

For Python -
Read about it on https://www.geeksforgeeks.org/fast-i-o-for-competitive-programming-in-python/.

# How to take multiple inputs in a single line in Python -

Other languages like Java, C++, C etc. take input on the basis of space and line separation, for example, 3 5 7 will be taken as three different inputs.
But Python takes input on the basis of endline separation only, so we need to accommodate a piece of code into our program so that space separated values are taken as different inputs.
Read about it on Multiple inputs from https://www.geeksforgeeks.org/taking-multiple-inputs-from-user-in-python/.

# Other miscellaneous C++ tips/tricks-
Most of us have been using C++ for competitive coding, here are some features of C++ that we have used extensively:

The one header that has it all - bits/stdc++.h
This header file includes every standard library that you would require in competitive programming. It would be a good idea to include this in your code! 

Warning: Clang compiler does not recognise this header, so make sure you have a GNU compiler (and submit to codeforces on a non-Clang compiler).

Instead of using a character array (char []) for taking in string input, use the “string” datatype instead (which has a lot of in-built functions associated with it)

Efficient use of the functions and containers in STL, would help save a ton of time.