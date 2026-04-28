## Question 1
JavaScript's asynchronous nature can be a pain point because the order 
of code execution is hard to predict. For example, like we saw in Q19, 
setTimeout runs later, even with a 0ms delay, which can cause unexpected bugs.

Loose typing is also tricky because JavaScript automatically converts types 
without warning. Like we saw in the lab, '2' + 2 gives '22' instead of 4, 
which can cause hard-to-find bugs.

The web platform is a pain point because JavaScript has to run on many 
different browsers, and sometimes the same code behaves differently depending on the browser.

## Question 2
I think the developers made JavaScript loosely typed because the web needs 
to handle all kinds of user input flexibly. If every type had to match 
exactly, simple web forms would be really annoying to code.

Asynchronous features were added so that web pages don't freeze while 
waiting for a server response. Without async, every fetch request would 
freeze the entire page.

## Question 3
A compiled language translates the entire code into machine code before 
running it. An interpreted language runs the code line by line while executing.

JavaScript is interpreted, which means it can run directly in the browser 
without a separate compile step. The benefit is faster development and 
easy testing, but the drawback is that it can be slower than compiled languages.

## Question 4
I think the professor focuses on vanilla JavaScript because you need to 
understand the fundamentals before using frameworks. If you jump straight 
into React or Vue without knowing vanilla JS, you won't understand what's 
happening under the hood.

The benefit of mastering vanilla JS first is that you can debug better and 
understand any framework more easily. The drawback of not learning a 
framework is that building large projects from scratch takes much more time.

## Question 5
This lab directly relates to our project because we will be using JavaScript 
to build our web app. Understanding variable scoping, type conversions, and 
debugging with DevTools will help us write cleaner code and fix bugs faster. 
The pipeline section also showed us how automated testing works, which we 
will need to implement in our project as well.
