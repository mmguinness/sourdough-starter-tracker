# sourdough-starter-tracker

## About

Web application to help you track your sourdough starter. A virtual twin for your sourdough starter that mocks the behaviour of your starter when you feed it, or not. 


## What is a sourdough starter?

[A sourdough starter](https://www.theperfectloaf.com/new-baker-start-here/) is a naturally fermenting mixture of flour and water. It hosts a stable blend of beneficial bacteria and wild yeasts. This mixture is continually maintained with regular refreshments (or feedings) and is used to leaven and flavor new bread dough.


## MVP

* Single page web-app, graphics should update to reflect the status of the starter. 
* Tracks and sends a reminder when you need to feed your starter.
* Two modes - **in fridge** or at **room temperature**
* If in the fridge - nothing happens, sourdough is stable and not growing. Send a text reminder after a week to feed.
* If at room temperature - starter must be fed once a day, at the same time of day. Send text reminder if not fed by 10am.
* Keeps a log of all feedings and time spent in fridge.

## Tech Stack

Proposed:
- Express web framework for Node.js
- Nodemon to reload the server automatically.
- React to render interactive UIs.
- Mongoose to model objects in MongoDB.
- Jest for testing.
- Cypress for end-to-end testing.
- ESLint for linting.
