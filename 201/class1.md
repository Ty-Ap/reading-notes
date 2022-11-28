# class-01.md

## Getting Started with the Web

    Website building is no easy task. There are a myriad of tools, plug-ins, frameworks, and ideologies.
A website is made primarily of file. These files contain and interact with text content, code, stylesheets, media content, etc.
Due to the complex modular nature of websites, a solid framework or groundplan is second only to user experience.

## How the Web Works

    Devices connected to the internet are called clients and servers. Clients are usually user connected devices, such as laptops or phones. Servers are devices that store wep pages, data, or apps. When users access a webpage, they're actually viewing and interacting with a copy of the data sent from the server. This is further complicated via TSPs, IPs, DNSs etc. 
From MDN Web Docs;

- TCP/IP: Transmission Control Protocol and Internet Protocol are communication protocols that define how data should travel across the internet. This is like the transport mechanisms that let you place an order, go to the shop, and buy your goods. In our example, this is like a car or a bike (or however else you might get around).
- DNS: Domain Name System is like an address book for websites. When you type a web address in your browser, the browser looks at the DNS to find the website's IP address before it can retrieve the website. The browser needs to find out which server the website lives on, so it can send HTTP messages to the right place (see below). This is like looking up the address of the shop so you can access it.
- HTTP: Hypertext Transfer Protocol is an application protocol that defines a language for clients and servers to speak to each other. This is like the language you use to order your goods.
- Component files: A website is made up of many different files, which are like the different parts of the goods you buy from the shop. These files come in two main types:
- Code files: Websites are built primarily from HTML, CSS, and JavaScript, though you'll meet other technologies a bit later.
- Assets: This is a collective name for all the other stuff that makes up a website, such as images, music, video, Word documents, and PDFs.

Most websites are run on Javascript, which is a versatile code languag. more notes on javascript are in my 102 class notes file.

### Compose a short poem describing how HTTP sends data between computers

    Two paths diverged in a yellow wood, they both lead from a client to a server and the rules of the road are Hypertext Transfer Protocol. 

### Describe how HTML, CSS, and JS files are “parsed” in the browser

    parsing is just the order a data set is read in. The browser parses the HTML file first, and that leads to the browser recognizing any <link>-element references to external CSS stylesheets and any <script>-element references to scripts. from MDN Web Docs; As the browser parses the HTML, it sends requests back to the server for any CSS files it has found from <link> elements, and any JavaScript files it has found from <script> elements, and from those, then parses the CSS and JavaScript.The browser generates an in-memory DOM tree from the parsed HTML, generates an in-memory CSSOM structure from the parsed CSS, and compiles and executes the parsed JavaScript.As the browser builds the DOM tree and applies the styles from the CSSOM tree and executes the JavaScript, a visual representation of the page is painted to the screen, and the user sees the page content and can begin to interact with it. 
tldr; html>link elements and script(ie. .js or .css)>build-up

### How can you find images to add to a Website?

    I usually go on Unsplash, but you can either find royalty free images or pay for image usage on an image repository site.

### How do you create a String vs a Number in JavaScript?

    string; anything enclosed in single quotes. including numbers ''
    number; any integer without single quotes or other grouping.

### What is a Variable and why are they important in JavaScript?

    Variables are essentially containers for data or input. These can be put into functions or called back by user input, or any other number of interactions. They are "where the magic happens" so to speak.

### What is an HTML attribute?

An HTML attribute is a piece of markup language used to adjust the behavior or display of an HTML element.

### Describe the Anatomy of an HTMl element

opening tag, content, closing tag

### What is the Difference between article and section element tags?

articles are used for grouping and wrapping similar content, elements define sections of a page.

### What Elements does a “typical” website include?

header, footer, menu, images, content.

### How does metadata influence Search Engine Optimization?

it is data not seen by the client. it is still included in searches, so putting a popular search term in your header will net you more traffic.

### How is the meta HTML tag used when specifying metadata?

by the " </meta>" tags wrapped around content

### Why should you use a header1 element over a span element to display a top level heading?

because h1 elements have syntax built in, span is just an empty container

### What are the benefits of using semantic tags in our HTML?

keeps things organized and prevents internal code and syntax conflict. 

### Describe 2 things that require JavaScript in the Browser?

user input, and dynamic code responses

### How can you add JavaScript to an HTML document?

creating a .js file and using the script tags calling back to that file
