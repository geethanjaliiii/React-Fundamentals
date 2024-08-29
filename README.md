React is the library for web and native user interfaces. Build user interfaces out of individual pieces called components written in JavaScript.

1.What is Emmet?

Emmet is a web-developer’s toolkit for boosting HTML & CSS code writing.

With Emmet, you can type expressions (abbreviations) similar to CSS selectors and convert them into code fragment with a single keystroke. For example, this abbreviation:

ul#nav>li.item$*4>a{Item $}

…can be expanded into:

<ul id="nav">
    <li class="item1"><a href="">Item 1</a></li>
    <li class="item2"><a href="">Item 2</a></li>
    <li class="item3"><a href="">Item 3</a></li>
    <li class="item4"><a href="">Item 4</a></li>
</ul>

2.Difference between a Library and Framework?

Both the framework vs library is precoded support programs to develop complex software applications.
However, libraries target a specific functionality, while a framework tries to provide everything required to develop a complete application.

3.what is CDN?Why do we use it?

A CDN (content delivery network), also called a content distribution network, is a group of geographically distributed and interconnected servers. 

They provide cached internet content from a network location closest to a user to speed up its delivery.

A content delivery network is crucial for providers and website owners because it makes it easier to transfer content -- such as images,
videos and website files -- to numerous servers spread out around the globe. This enhances user experience, 
especially for users who are located far from the origin server. It also speeds up web page loading times while reducing the strain on the main server.

4.What is crossorigin in script tag?

The crossorigin attribute sets the mode of the request to an HTTP CORS Request. Web pages often make requests to load resources on other servers. 
Here is where CORS comes in. A cross-origin request is a request for
a resource (e.g. style sheets, iframes, images, fonts, or scripts) from another domain.

5.What is diference between React and ReactDOM

While React provides the tools and concepts to define component-based user interfaces, ReactDOM handles the task of rendering those interfaces in a web environment.
Together, they form the foundation of React web applications.

● What is difference between react.development.js and react.production.js files via CDN?

In development mode, we can enable and utilize React developer tools, devtools profiler, debugging environment attached with source code. 
We can utilize various functionalities such as Hot Module Replacement, diagnostics so that development environment will help to debug code.

In production mode, compression and minification of Javascript and other resources happens to reduce size of the code which is not the case when it comes to development mode. 
Performance will be much faster in production mode when compared to development mode.

● What is async and defer?
  
Async: Executes scripts as soon as they are available, regardless of their order in the HTML document.
Defer: Executes scripts in the order they appear in the HTML document, after HTML parsing is complete.
