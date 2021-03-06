# <img src="https://www.kindpng.com/picc/m/67-678384_transparent-javascript-icon-png-png-download.png" width=70px alt="JavaScript" >Assignment For Day -1 

## 1. Explain the use of JavaScript ( or What you can do using a JavaScript): 
   JavaScript is a scripting programming language which is used to build both client and server side web components. 
   Using JavaScript we can make our web components or webpages more interactive and dynamic.
   
   
## 2. What is the difference between client-side and server-side?:

   ### Client-Side Programming:
   A client-side program, or client-side logic, builds or creates front-end web components through which our users interact.
   Client-Side programming or logic means to build or create front end web components through which our users interact. 
   Therefore, we can use JavaScript programming to create front-end components in order to add dynamic content to our web components (HTML files).
   There are several JavaScript front end frameworks or libraries that can be used to build front end components. 

   Examples include: Angular JS, Angular, React, Vue, Svelts, etc. These are the examples of frontend JavaScript frameworks which helps us to build fronend components     seamlessly.

   ### Server-Side Programming:
   Server-Side Programming, on the other hand, is used to build back-end components such as controller components, business components, persistence components, and        model components that interact with databases, manage cookies or security functions, and so on.
   There are several JavaScript back end frameworks or libraries that can be used to build back end components. 

   Examples inculde: Node JS, Express JS, Next JS etc. These are the backend JavaScript frameworks which helps us to create backend components seamlessly.
   
## 3. What is Nodejs?:
   Node JS is a server side JavaScript Programming language which provides JavaScript runtime environment to run or execute JS code from our system itself.
   Earlier what happened is that JS code was executed from the browser itself i.e. from the client side. 
   Different browser contains different JS engine which was responsible to execute JS code from the browser side itself.
   But since JS is so popular so it was required it to execute from the system itself just like any normal PL. For that purpose Node JS was introduced. 

## 4. Explain Scope in JavaScript:
   Scope means variable scope in JavaScript. Scope determines the  visibility(accissibility) of a variable in JavaScript. 
   JavaScript has mainly two types of variable scopes: or In JavaScript, a variable has two types of scope:

   1)Global Scope: A variable declared at the top of a program or outside of a function is considered a global scope variable.

   2)Local Scope: A variable declared inside the function is considered a local scope variable.
		
## 5. JavaScript is asynchronous or synchronous:
   Before knowing whether JavaScript is a Synchronour or Asynchronous let's firt understand what is Synchronous and Asynchronous means.
   
   ### Synchronous: 
   Synchronous code runs in sequence. Synchronous means as the name suggests, it means to be executed in a sequence, i.e. every statement of the code will be        executed one by one. 
   So, basically in a synchronous programming, the next statement has to wait for the present statement to get executed.
   Let us understand this with the help of an example.

   Example of Synchronous JavaScript: JavaScript is a Synchronous
	
   ```javascript 
    
     document.write("Hi");  //First
     document.write("<br>");
	  
     document.write("Hello") ;  //Second
     document.write("<br>");
		  
     document.write("How are you?"); //Third
   
   ```
    OUTPUT: HI
	    Hello
	    How are you?
	    
	    
   This is the example of Synchonous JavaScript because here each statements are executed from top to bottom one by one.
   Here the first line of the code Hi will be executed first then the second line Hello will be executed and then after its completion, 
   the third line would be executed How are you?.
   So as we can see here the codes work in a sequence. Every line of code waits for its previous one to get executed first and then it gets executed.
	
   ### Asynchronous:
   Asynchronous code runs in parallel. This means that the statement of the code will be executed while another statement of the code is still being processed.
	
   To understand Asynchronous code take this example:
   Example of Asynchronous JavaScript: JavaScript is an Asynchronous
       
 ```javascript 
 console.log('Hi');
 setTimeout(() => console.log('Hello'), 100);
 console.log('How are you?');
``` 
  OUTPUT: Hi   How are You? Hello
 	
Asynchronous code execution is often preferable in situations like where execution can be blocked indefinitely. 
Some of the examples of this are network requests, long-running calculations, file system operations etc.  
Using asynchronous code in the browser ensures the page remains responsive and the user experience is mostly unaffected.
So JavaScript is both synchronous and asynchronous programming language.
	

# 6. JavaScript is Single-threaded or Multi-threaded:
   Javascript is a single threaded programming language that can be non-blocking. Single threaded programming languange means it has only one call stack 
   and one heap memory that is used to execute a program.
   
   
# 7. Explain DOM in your own word:
   DOM stands for Document Object Model. It is basically an API or libraries of an HTML file using which we can actually access or manipulate the HTML elements
   during runtime.
   

[Visit My Website](https://github.com/rajnish-jha/java-script "JS")
