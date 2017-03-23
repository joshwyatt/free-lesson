# Learn to Code - JavaScript and Web Development Basics

By the end of this lesson you will be able to:

- Give a high level description of modern web applications
- Describe why JavaScript is uniquely relevant to web development
- Be able to speak about JavaScript functions
- Be able to use some built-in JavaScript functions
- Be able to define and use your own functions

## Modern Web Applications

The web has come an exceptionally long way since its inception. Originally intented to be a way for people to share static files with each other over remote locations, the web now contains incredibly sophisticated programs capable of much more than providing users with static pages. On the web, users can now play games with thousands of other people, make incredibly sensitive financial transactions, watch movies, video conference with dozens of other people, and much more. These web applications need to:

- Handle tremendous amounts of traffic
- Be aesthetically pleasing
- Allow for user-specific experiences
- Interact with other web applications
- Secure sensitive information
- Be actively developed and improved
- Be reliably deployed
- Provide real time data to other sophisticated data analysis programs

## The Components of a Web Application

So what is going on behind that web page you're looking at through your browser? When you enter an web address into your browser and hit enter:

- The web browser (a program on your computer) asks your computer to send some *request* data, using an agreed upon format called the *HTTP protocol*, to a program running at the address that you entered into the browser. The address contains the location of a specific computer, and, a specific program on that computer. This program (and also sometimes the computer that it is running on) is refered to as a *server*, while the web browser, which is sending a request to the *server* is refered to as a *client*.
- Your computer converts the client request from the browser into zeroes and ones and sends it to a sophisticated network of programs, scattered all throughout the world, that work to deliver the request data to the server running at the given address.
- The server, depending on the information in the request, builds up and sends back a *response* to the client (the web browser on your computer in this example). This initial response tends to be an HTML page.
  - Most likely the server also interacts with other programs to store information from the request, retrieve information to be sent back in the response, log information about what is happening, and send information to other programs for analysis.
- When the web browser receives the response back from the server, most likely containing HTML, it renders this HTML onto the screen.
- In reading this HTML the browser most likely will find that it also needs other assets like images, stylesheets and JavaScript files. The browser then sends additional requests to the server for these additional resources, and upon receiving them in responses, renders them onto the screen.

## Where JavaScript Fits In

In the process described above, dozens of different programming languages are utilized during different parts of the process. Different programming languages have different strengths and weaknesses and are more or less well suited for various operations. At the very least, all programming languages keep us humans from having to read and write in zeroes and ones.

HTML is the original language of the web. It is a language that lets programmers declare the structure of a web page, as well as some very simple user interactions such as using a link, or submitting a form.

CSS was added as a second language that browsers could understand in order to separate the styling of the page from its structure.

Both CSS and HTML are still present in practically all web pages.

JavaScript was the next language written specifically for web browsers, the Netscape browser specifically. Mostly on account of market dynamics and then later, precedence, it remains to this day the only language in addition to HTML and CSS that browsers can read. If for no other reason than this, JavaScript is absolutely central to web development.

While HTML and CSS both allow programmers to make statements about what a web page should *look like*, JavaScript allows programmers to make statements about what web pages should *do*. Over the last several decades developers have pushed this concept of making web pages *do* things to unforseen extremes, and will surely continue to do so.

For a long time, and to some degree this still holds true, JavaScript was viewed as a rather easy language to learn, and not as "sophisticated" as some other languages that interacted more directly with a computer's hardware, the fact that it was restrained to being run inside of browsers exasperated this sentiment. In the last 10 years however (2009 in fact) a project was completed that allowed JavaScript to be run outside of browsers. This project was called *NodeJS*. NodeJS opened the door for all kinds of computer programs to be written in JavaScript, most notably, web servers interacting with client-side JavaScript applications. This was largely done so that companies could hire a single developer to work on both the "front-end" (client side) and "back end" (server side) of web applications, even if the developer "only" knew JavaScript.

These days JavaScript is used extensively (though by no means uniquely) as a server side language as well as for standalone desktop applications, and even *native* programs that run inside devices like smartphones and tablets.

Given its ubiquity in the web development landscape, its ability to give programmers access to programming on the full application stack, and its relatively easy (at first) learning curve, JavaScript is an excellent choice as a first language for deep study as a prospective web developer.

## A Brief Intro to JavaScript Functions

Think about a function as a mini program that we can provide information to inform how it runs. The use of functions involves 2 main steps, which must happen **in order**:

1) Define the function, including what kinds of information users can give it to affect how it runs.
2) Use the function, giving it the kinds of information it was defined to receive, in order to affect how it runs.

Regarding step 1, we can either define functions ourselves, or use functions that others have already defined. More on defining our own functions later.

Regarding step 2, we can use functions between 0 and many times. Depending on how the function was defined, we can provide it with different information each time we run it, in order to use it in different ways. Using a function is also called *running* a function, *calling* a function or *invoking* a function.

The way to call a function in JavaScript is to give its name, followed by a pair of parenthesis `()`. Inside the parenthesis, we provide the information that the function expects to receive, each specific bit of information separated by a comma. Each of these pieces of "information" is called an *argument*.

Let's do some coding! [Click here to go to a shared JavaScript coding environment](https://repl.it/G97W).
