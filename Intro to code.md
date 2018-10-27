# Intro to code

### Coding environment

In order to write code that is visible in the browser we need an environment that allows us to write the code. There are a lot of different environments where you can write and execute code on. If you have any tech experience you may have come across IDE’s (integrated development environment) - where you are able to write, compile and execute code and text editors - which is a more basic and simplied version of an IDE.

But the easiest and the most accessible environment we are going to be using today will be **https://codepen.io/**

Codepen is an easy to use online editor that allows you to write and test code by being able to view changes you have made in real time. On the taps we see that we have options to write html and css. 

Let’s begin by writing some html! 

### Intro to HTML

HTML is defined as *Hypertext Markup Language* and its used to define how content is displayed in the html file. A html file is the basis of a webpage.

One of the easiest ways of understanding how coding languages are used, is by using the human body as an analogy - the skeleton is what defines the body. CSS which stands for  *cascading style sheet* would be what we look like as CSS is essentially about styling the webpage and if we really want to go indepth we can argue that our personalities and neural systems are frontend and backend languages!

To begin we need to our html boilerplate - this is the standard and foundation of every webpage. You could write out yourself or copy it from 
 

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
 
Inside our div container we enter another html attribute `<img>` tag. Go on your facebook/instagram or or even google images. Right click and click on "copy image address" then you paste this inside the src tag.
 
~~~
 <div>
    <img src="https://scontent-lhr3-1.xx.fbcdn.net/v/t1.0-1/c0.53.320.320/p320x320/24993311_10155139582001245_5253312607925111975_n.jpg?_nc_cat=111&_nc_ht=scontent-lhr3-1.xx&oh=4912ed97af1fbd8a2b64967027fa2831&oe=5C3DE992">
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

### CSS STYLING!

Now that have we have the basic skeleton of the web page done we are now going to move on to styling.

Syntax for CSS varies to the HTML, in that you define the HTML tag which we call the selector, have the curly brackets brackets and write the declaration. The declaration consists of a property and value.

~~~
body {
  background-color: #F5F5DC
}
~~~

### Styling the Nav Bar
We are going to apply the same logic on styling our nav bar. We start with the `<ul>` by firstly aligning our text to the center. Then we use the padding element to create space.

~~~
ul {
  text-align: center;
  padding: 15px
}
~~~

To remove the bullet points and move the text to eachother we use the display property.

~~~
li {
 display: inline-block;  
}
~~~

### Styling image

Next we want to move our image and text to the center of the page. Sometimes I like to add a background image on my div boxes so I can cleary where the container on my page are.

~~~
div {
  text-align: center;
  background: blue
}
~~~

### Appyling specific styling

Now when we are working with multiple div containers, there could be instances where we could like to apply styling to a specific container without it reflecting on the other div containers. We have two options which are **Classes** and **ID’s**, both being attributes. The difference between them is that a Class can be used across muliple elements and an ID can only be used once.

For this exercise we just use a class. We go back to our HTML and enter the class tag inside out div then back on to the CSS we define the class using `.` followed by the class name ie `.propertyName`.

Firstly, we want to align the text to the left. Then we add some spacing around the text using padding and give it 20px.

~~~[]()
.text {
  margin: 10px;
  padding: 20px;
  text-align: left;
}
~~~

[Finished page](https://output.jsbin.com/naxujok/1)

###Rescources

If you enjoyed this and you would like to more here are a list of rescources that really helped me

**Online**

* https://www.codecademy.com/

* https://www.w3schools.com/

* https://www.udemy.com/

* net ninja on youtube - https://www.youtube.com/channel/UCW5YeuERMmlnqo4oq8vwUpg


**Offline**

* https://codebar.io/

* https://www.meetup.com/Find-A-tech-Job-In-London/?_cookie-check=22ok73SiKkBx0VlL (and just meetup events in general)

* https://www.meetup.com/IBM-Code-London/


If you would like to connect with me/ need any help of advice feel free to follow me on twitter and send me a dm on [@bukikekere](https://twitter.com/bukikekere?lang=en) : )
