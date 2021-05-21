Frontend Challenge for Developer Candidates
===========================================

To better assess a candidates development skills, we would like to provide the following challenge. This is intendend to be developed in a pair programming session within an hour of time.

Prerequisites
-------------

* [Git](https://git-scm.com/)
* [Node.js](https://nodejs.org/)
* [npm](https://www.npmjs.com/)

Installation
------------

Clone the project

```bash
git clone git@github.com:AmbulnzLLC/frontend-challenge.git && cd frontend-challenge/
```

Install the dependencies

```bash
npm install
```

Start the server

```bash
node server.js
```

Visit [http://localhost:8080](http://localhost:8080)

**Please set up your working environment before the interview (working server, node, npm dependencies), so we don't spend time installing anything.**

Project description
-------------------

We want to develop a small web app that allows users to order pizza.

First of all we'll display the list of pizzas with ingredients and prices. Data will be loaded from `server/pizzas.json`.

When the user chooses something from the list the order summary will update dynamically.

There will be a button to confirm the order. An ajax call will be performed to `server/order.json` and the result will be displayed as a message like this: "Your order will be delivered in x minutes".

You can use any library/framework/plugin you want.

Please use some template library (http://handlebarsjs.com/, http://mustache.github.io/, ...) or a template engine from the framework.

The application must be single page and JS-based using Angular (1.x is fine if not familiar with >= 2.x) or ReactJS. That means that I load just one html file, if you want to add some navigation you have to implement it via JS.

If you can display discounts for pizzas it's a plus.

Evaluation
----------

Our goal is to find answers to those questions:

* Do you understand the JavaScript language and more in general web technologies?
* Can you judge which library/framework is the best fit for a job and use it correctly?
* Can you design interfaces that are clear and easy to use?
* Do you master your working environment?

Due to the limited time consider the followings:

* It is NOT important to have a fully functional application at the end
* We'll develop just for the latest version of Google Chrome (Chromium)

