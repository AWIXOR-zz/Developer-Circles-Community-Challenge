# The birth of React

##### Table of Contents

1. [Section 1: History](#history)<br>

- [What is ReactJs](#what-is-react-js)<br>
- [History](#history)<br>
  - [Before REACT](#before-react)<br>
  - [The birth of SPA](#the-birth-of-SPA)<br>
- [The birth of React](#the-birth-of-react)<br>

2. [Section 2: React](#the-birth-of-react)<br>

- [React Concepts](#react-concepts)<br>
  - [Declarative programming vs Imperative in React](#declarative-programming-vs-imperative-in-react) <br>
  - [Virtual DOM](#virtual-dom)<br>
  - [How to be a great React Developer](#how-to-be-a-great-react-developer)<br>

3. [Section 3: Into React](#virtual-dom)<br>

---

# What is React js

[React](https://reactjs.org) is a JavaScript library for building user interfaces. It's maintained by [Facebook](https://github.com/facebook/react/) and a community of individual developers and companies. React can be used as a base in the development of single-page or mobile applications.

# History

_Some History won't hurt!_

`Browsers back then`: send all data for every Request.

<a href="#"><img src="https://github.com/awixor/React-Track/blob/master/assits/client_server.png" ></a>

Let's see where/when the story began

- `1993` : Mosaic 💥, the first web browser, but no JS ❌ yet. Only the DOM (Document Object Model) but non-standardized yet.
- `1994` : Netscape 🚀, was the dominant web browser in terms of usage share after the 1994.
- `May 1995` : Java appeared, and Netscape wanted to add **interations** to the webpages.
- `Mid 1995` : MOCHA was created by _Brendan Eich_ during his time at Netscape. It was inspired by Java, Scheme and [Self](http://www.selflanguage.org). Mocha syntactically was just like Java {curly bracket language}, but already contains many features that we know and love in modern JS.
- `Sep 1995` : mocha's renamed to LiveScript and shipped in the first beta releases of [Netscape Navigator 2.0](https://tidbits.com/1995/11/13/netscape-2-0b2-available/) <a href="#"><img src="https://github.com/awixor/React-Track/blob/master/assits/netscape_website.png" ></a>

- `Dec 1995` : JavaScript name appeared, no longer LiveScript. This name was because back then java was the most popular programming language.
- `1996` : After Microsoft released Internet Explorer, MS reversed engineer JavaScript and they named it `jscript`, so now we have almost two identical languages:`JavaScript` and `Jscript`, and with the internet growing rapidly, people realized that there would be a need to standardize JavaScript.
- `1997` : EcmaScript is born.

## Before REACT

So as time goes many browsers appeared and JavaScript gains more interest, but the problem was that each one of these browsers works differently from each other, so as we wanted to use more and more javascript in our web pages we had to account for all these browsers, and accommadate javascript to work with them.

- `2006` : jQuery came out and changed alot.Allowed developers to easly interact with the `DOM` across all browsers.
  <a href="#"><img src="https://github.com/awixor/React-Track/blob/master/assits/jquery.png" ></a>

So with the power that jQuery gave to developers, they bigan to build bigger and bigger apps like Facebook where you had so many features.
Instead of just requesting more and more pages like a blog, users can now interact with these apps.

- `2010`: [BackboneJs](https://github.com/jashkenas/backbone) came out. Because JavaScript files started getting bigger and bigger, so libraries like backboneJs allowed us to orginize these `JS files`.
  <a href="#"><img src="https://github.com/awixor/React-Track/blob/master/assits/backbone.png" ></a>

## The birth of SPA

Traditionally we just had HTML files for each page and everytime we move to a different page we request from the server the `HTML` file, `CSS` and `JS` (which usually contains jQuery) but with more advancement like we had with `jQuery`, `Backbone` and `Ajax` too, we now had a different system.
Generally what happend is that we focus less on `HTML` and alot more on `JS`.
So the principe behind `SPAs` is, you only load the application code once, and instead of leoding all files everytime returning a new document, our app now acts more like a desktop app where we stay on the same page the entire time, and JavaScripts simply changes or updates the DOM to display new things. This way of writing apps became really really popular.

<a href="#"><img src="https://github.com/awixor/React-Track/blob/master/assits/traditional-and-spa.jpg" ></a>

- `oct 2010` : [AngularJs](https://github.com/angular/angular.js) was created by Google and beacame the standard way of building applications or SPAs. But inlike jQuery Angular allowed developers to build these large apps by forming these containers that will wrapp your project. Because AngularJs was created by Google, it had a lot of power.
  <a href="#"><img src="https://github.com/awixor/React-Track/blob/master/assits/angular.png" ></a>

Now we have things like Controllers, Views, Models (MVC), so the way of orginizing code and dividing it into different things depending of what it does, made it much easier to work with as teams gets larger and larger.
**But another problem appeared!**
things started getting more and more complex because of this. As things get bigger and bigger more things have to happen. We have more and more complexity now and although frameworks like `AngularJS` came out people started to notice it's getting harder and harder to find bugs in the code and understand how each part of the app was affecting the other (Data was flowing everywhere).

---

# The birth of React

- `2013`: Facebook released [React](https://github.com/facebook/react), Facebook presented a very good solution, and everyone started to use it, because React come with a whole new way to build front-end applications.
  One year after, Gooogle realesed that the way that they architected AngularJs is not effetient to be used for building good applications anymore, so they decided to rewrite the whole liberary and called it Angular, but because of amount of time the rewrite will take, many people moved to React.
  The good principales introduced by React made it the most popular front-end tool with the most job demand across the world.

<a href="#"><img src="https://github.com/awixor/React-Track/blob/master/assits/react.png" ></a>

**More than 8000 campanies are using React in their tech stacks including:**

- Facebook
- Uber
- Airbnb
- Netflix
- Discord
- Snapchat
- Coursera
- Shopify
- Reddit
- Twitter
- Paypal
- Figma
- Slack
- [View more](https://stackshare.io/react)

# React Concepts

    1. React handles the DOM for you!
    2. Build websites like lego blocks (Reuseble components)
    3. Unidirectional data flow
    4. Handles only the UI.

## Declarative programming vs Imperative in React

<dl>
  <dt>Imperative:</dt>
  <dd>Directly change individuel part of the app in response of variant user events, it's like telling the app how to do something when something happens, and as a result what you want to happen will happen.</dd>

  <dt>Declarative:</dt>
  <dd>Unlike imperative it's like telling the app what you would like to happen, and let it figure out how to do it. React uses what we call <em>state</em>.</dd>
</dl>

> The state: is an object where you store property values that belongs to the component. When the state object changes, the component re-renders

<a href="#"><img src="https://github.com/awixor/React-Track/blob/master/assits/imp_vs_dec.jpg" ></a>

You can learn more about Imperative and Declarative in React in this article:
[Imperative vs Declarative](https://dev.to/itsjzt/declarative-programming--react-3bh2)

## Virtual DOM

The virtual DOM is a javascript version of the DOM (Document Object Model). React use this virtual DOM to know how it should update the DOM.

<a href="#"><img src="https://github.com/awixor/React-Track/blob/master/assits/Vdom.png" ></a>

So what React does is: when the state object that we mentioned above changes React updates only the components related to that state change unlike traditional apps which re-rendres the whole DOM.

## How to be a great React developer

1. Decide on components
2. Decide the state and where it lives
3. What changes when state changes
