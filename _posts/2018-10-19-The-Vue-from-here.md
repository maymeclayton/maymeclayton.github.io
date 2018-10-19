---
layout: page
---

# Learning Vue.js

We're winding down week 5 of Bootcamp and I can hardly believe it. Time is flying and the material continues
to build and build. The last 3 weeks have been focused on using Vue.js as our JavaScript framework. One of the
ideas for learning the material shared with us recently by some Bootcamp Alumni was to talk to someone about
the material we are learning. I am going to attempt to do that via a blog post in the hopes that some of the
material may sink in a little more : )

Vue.js is a progressive JavaScript framework. I had to read that sentence on the Vue.js homepage about 15 times
before it even started to make sense. What I've come to learn is that it simply means you don't have to use the
entire framework right out of the box. You can use bits and pieces of it throughout your project. "Incrementally adoptable"
is the technical phrasing and this inherent trait is what has made it digestible for this newbie.

Getting started with Vue is relatively simple, copy the CDN script tag directly from their site and paste it into your HTML index page.
There are two CDNs available: one for development and the other for production. The development CDN provides helpful console warnings and the production version is optimized for speed and size. Additionally, the documentation for Vue is incredibly helpful. Even as someone very new to web development and frameworks I had an easy time understanding the material presented.

***

While I am sure there are innumerable ways to utilize Vue our introduction has mostly used the following:
- Templating/Declarative Rendering:
- Conditionals and Loops
- Handling User Input

Templating/Declarative Rendering is essentially declaring a variable in your Vue Instance/javascript and then using that within your HTML to pull that data in. There is  directive that you use within the HTML called v-bind to tie these pieces together.

Conditionals and Loops have directives of v-if and v-for that allow you to put if statements and for loops directly into the HTML. Pretty nifty and, once I figured out exactly how to do it, it made life significantly easier.

Vue handles user input via a directive called v-on to attach event listeners to allow user interaction. Another directive for user input is v-model which provides two way binding between input and the app itself.

While there is so much more I could talk about I think this is a good first start at an explanation. Hopefully as I learn more and continue to use the framework I will build on this knowledge and be able to share more!
