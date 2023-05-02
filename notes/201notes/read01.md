# Reading Class 01

## Getting Started

0. Understanding how the web works is important for this module because have a strong foundational knowledge of what we're manipulating inside of our website and how it interacts with the web will ensure we don't fall behind and are able to connect different concepts together into a cohesive understanding.

        HTTP, a link between two
        A bridge for data, through and through.
        A client sends, a server receives
        A request for data, it retrieves

        Back to the client, the data goes
        A web page or image, it then shows
        In bytes and bits, it's sent and received
        A digital dance, choreographed and weaved

        HTTP, the language of the web
        A world of data, to navigate and tread
        Simple yet powerful is this protocol
        From pole to pole, it connects us all

2. HTML, CSS, and JS files are parsed from top to bottom. Starting with HTML. When a CSS or JS link is found, the browser will make a request with the server for the information found within the link. Once the browser receives the data it then parses that new content, once it's done it commits that information to the DOM for HTML, CSSOM for the stylesheets into what is known as trees. Then compiles and executes the JavaScript. Once all the files are parsed, and all files and styles are in their respective tree, the browser displays the content into the viewport of the browser window.

3. You can find images by searching on google, and to be safe you can use the license filter to ensure you're not using licensed or copyrighted images.

4. A string must be encapsulated by quotation marks after you have named the variable. A number can just be assigned to a variable after the variable has been declared without quotes. Also it must a regular number, not including letters.

5. A variable is a container with a unique name that is stored in memory with a value attached to it. userName = "bob"; creates a container called userName with a value of bob inside of it.

## Introduction to HTML

1. An HTML attribute is a piece of information that can be added to an HTML element like a ```<p>``` or ```<div>``` element. This gives that element added functionality, like a class name that can be added to the style sheets to customize the look of that particular element, or a link to the .css files.

2. An HTML element's anatomy starts with an opening tag, this tells the browser what type of element it is going to be. like the ```<p>``` element from last question, it starts with an open chevron or angle bracket the type of element and then close chevron or angle bracket. Next is the content of the element, the strings, function names, or numbers. Lastly there's a closing tag which is the same as the opening tag except there is a / right after the opening < which looks like this ```</p>```.

3. A section is an element to define a generic section of a webpage. Consider it a container to house related content like paragraphs, or special lists before they're listed with ```<ul> or <ol>```. An article element is generally a part of the main body of the page itself that can generally be a standalone element within the greater webpage. Section groups related content, and article defines self-contained content.

4. The typical elements of the HTML document of a webpage are; the containing HTML element, the ```<header>```, the ```<nav>``` bar, the ```<main>``` content which may contain ```<article>```, ```<section>```, and ```<divs>```, possibly an ```<aside>``` for quoting things nicely, and then a ```<footer>``` at the bottom for copyright and links to social medias or FAQ pages.

5. The metadata affects how people will discover the page via search engines. The ```<title>``` element is what is displayed in the browser tab. Having a succint but informative ```<title>``` attribute within the metadata should help click rates to the page, driving more traffic. The ```content``` attribute within meta is what is displayed below the ```title``` on the search engine results webapge. This is where you can describe what your website is and what it does further affecting click rates. Lastly the ```author``` element contains the author. There's a few more but that's all for now, I'm getting sleepy.

6. The ```<meta>``` tag is used inside the ```<head>``` to write any information the browser, or search engine may need to display this content or help it show within the search engine results. There are also many accessibility functions contained within meta as well.

## Miscellaneous

### Design a website

1. The first step to designing a website is *project ideation*.
2. The most important question is to ask, what is my end goal or vision I want to achieve via the website.

### Semantics

1. The ```<h1>``` element should be used over ```<span>``` because the latter does not have any special attributes inherent to it's tag name. Therefore it will not show up in a larger font or in bold like the ```<h1>``` element tag will.
2. Semantic tag use is a benefit because it makes the webpage easier to understand, more descriptive, aids in SEO, and accessibility. It provies structure to the content on the webpage unlike non-semantic tags.

### What is JavaScript

1. Many things require JavaScript to be able to run, but 2 simple ones are. 
    + API integration, without JS we wouldn't be able to update webpage content without completely reloading the webpage. 
    + Client storge or Cookies, without JS the browser couldn't store data on the client side allowing the browser to maintain login information so the user doesn't have to login everytime they load a new webpage on the same website. 

## Things I want to know more about

  + Just about everything I want to know more about. The issue is I don't know if I completely understand some topics or not quite yet so it's hard to determine exactly what.
  + Cookies, browser cookies have been a hot topic and I hate clicking on those accept cookies popups on every website.