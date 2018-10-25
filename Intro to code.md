# Intro to code

### Coding environment

In order to write code that is visible in the browser we need an environment that allows us to write the code. There are a lot of different environments where you can write and execute code on. If you have any tech experience you may have come across IDE’s (integrated development environment) - where you are able to write, compile and execute code and text editors - which is a more basic and simplied version of an IDE.

But the easiest and the most accessible environment we are going to be using today will be **https://jsbin.com/**

Jsbin is an easy to use online editor that allows you to write and test code by being able to view changes you have made in real time. On the taps we see that we have options to write html, css and other languages. 

Let’s begin by writing some html! 

### Intro to HTML

HTML is defined as *Hypertext Markup Language* and its used to define how content is displayed in the html file. A html file is the basis of a webpage.

One of the easiest ways of understanding how coding languages are used, is by using the human body as an analogy - the skeleton is what defines the body. CSS which stands for  *cascading style sheet* would be what we look like as CSS is essentially about styling the webpage and if we really want to go indepth we can argue that our personalities and neural systems are frontend and backend languages!

When you first open up JSBin you already see that it has the some code already in it. This is the standard html you will see on every web page and it is called a html boiler plate. 

The `<!DOCTYPE html>` declaration defines this document to be HTML5.
The `<html>` element is the root element of an HTML page.
The `<head>` element contains meta information about the document
The `<title>` element specifies a title for the document
The `<body>` element contains the visible page content

### Nav Bar
Now inside the body tag we are going to begin by constructing a nav bar.

An HTML element usually consists of a start tag and end tag, with the content inserted in between.
 
First, we begin with the nav tag `<nav> </nav>` and within the the nav tag we add our content. The nav bar is going to contain a list of links.
 
To define lists `<ul> </ul>` is used, which stands for unordered lists. Then we define the inidvdual list content we use `<li>`.
 
We are going to take it further by adding links on to your li tag with the use of attributes.
 
Attributes provide additional information about HTML elements.
 
Inside the li tag we insert the `< a href =” ”>` link used to insert links
 

~~~
<nav>
    <ul>
    	<li><a href="http://output.jsbin.com/piyagon/">Home</a></li>
		<li><a href="https://www.linkedin.com/">Social Media</a>
	</li>
		<li><a href="mailto:bukithompson@gmail.com?Subject=Hello%20again">Contact</a></li>
    </ul>
 </nav>
~~~

### Organise the layout and adding images

Now we are moving on to adding an image!
 
But before we do this we want to make sure that the layout of our page is laid out in an organised way. To ensure this we are going to use `<div>` tags.
 
Div stands for division and it helps us divide parts of a page. It can basically be seen as a container for content. 
 
Inside our div container we enter another html attribute `<img>` tag
 
~~~
 <div>
    <img src="http://via.placeholder.com/350x250">
  </div>
~~~

### Adding text!

Next we create another div box to add information on ourselves.
 
The `<hX>` element defines a large heading which spans from 1 - 6 - 1 being the largest and 6 the smallest.
The `<p>` element defines a paragraph. 
 
~~~
<div class="text">
    <h1>Buki Thompson</h1>
 
    <p>"Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do  eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris."</p>
</div>
~~~ 

When you develop websites that has alot of content we use plaecholder text for testing. One such type of placeholder text is called `lorem ipsum`.
 
Now the use of div tags may not seem like anything now but it will make more sense once we start on the css.

