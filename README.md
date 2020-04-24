# GovernmentCIO Code Challenge: 3

## Your mission, should you choose to accept! (User Stories)

As a user, I want to be able to view all of the SpaceX launches between two dates I decide.

As a user, I want to be able to sort the SpaceX launches by their launch date (both ascending or descending).

--

Your team is planning on this being a MVP, but they are planning on adding other features later on. Be sure to create everything with maintainability and scalability in mind. If you don't have enough time to build everything you want for this, be sure you document what you _would do_ if you did have enough time in a readme.

This challenge should take between 2-4 hours. If it is taking longer than 4 hours, don't panic! At GovernmentCIO we truly value your time so please just send us what you have been able to accomplish.

## What we're looking for

1. How well you document code
1. How you architect a fresh React/Redux project
1. How you set up Redux and [if you follow best practices](https://redux.js.org/style-guide/style-guide)
1. How you choose dependencies and how you implement them
1. How proficient you are with JavaScript, React, Redux, HTTP requests, styling, etc.
1. How well your website runs against [Google Lighthouse audits](https://developers.google.com/web/tools/lighthouse)

## Requirements

1. Create the boilerplate (we recommend using something like [create-react-app](https://reactjs.org/docs/create-a-new-react-app.html)).
1. Update the website's title, meta tags, and favicon (be creative!).
1. Set up any architecture you want, but **you must use and implement Redux** (and ideally utilize one or more Redux middleware libraries).
1. When a user chooses a start date, an end date, and clicks a "Search" button, a request should be made to [the API endpoint `https://api.spacexdata.com/v3/launches`](https://docs.spacexdata.com/?version=latest).
1. While waiting for a response from the API, we should show a loading design.
1. Once we receive the response, we should show a list of all the results and store all fetched data in Redux.
1. Once we receive the response, if there are no results, we should show a no-results design.
1. The user should be able to sort the launches by their launch date.
1. The user should be able to search again for a different date range.
1. Please `git commit` early and often. Also, please do not squash commits as we enjoy seeing the evolution of the project!

The UI/UX is up to you, feel free to be as creative as you'd like! Rest assured that **you won't be penalized at all if you completely forgo styling** as we know it can be time-consuming.

## Dependencies you should include

1. `react`
1. `prop-types`
1. `redux`
1. `react-redux`
1. `redux-thunk` or `redux-saga` or `redux-observable` or another Redux middleware library

## How to submit the challenge

At GovernmentCIO, we ❤️ open-source and we know you do, too. Feel free to publish this project publicly on your GitHub and show it off in your portfolio!

You can submit the challenge either way:

#### Open-source GitHub repo

1. Send the link to the **public** GitHub repo in an email to [pshort@governmentcio.com](mailto:pshort@governmentcio.com?subject=Code%20challenge%203%20submission).

#### Emailing

1. Remove the `node_modules` directory.
1. Make sure you have commited everything.
1. Zip the entire code challenge directory.
1. Send the `code-challenge-3.zip` to [pshort@governmentcio.com](mailto:pshort@governmentcio.com?subject=Code%20challenge%203%20submission).
