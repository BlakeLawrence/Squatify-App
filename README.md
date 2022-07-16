# Squatify

This is an app that tracks your daily squats.
At the School of Code, it's a tradition to kick every morning off with a bunch of squats done to a song of choice.
As students of the School of Code, we created this app as a nod to this tradition.




## See It Live

Click this link to test the app. https://squatify.netlify.app/
## Installation

First, clone the frontend and backend repositories.

```bash
git clone https://github.com/anastasia-starostina/Squatify-App.git
git clone https://github.com/DHawkesford/squatify-backend.git
```

Within each repo, run the following command to install the necessary dependencies.

```bash
npm i
```
### If you'd like to connect this app to your own database, follow the steps below (we used Heroku).


Create your own .env file at the root level of your repository and add your database URI in here.

```bash
DATABASE_URL=<add your database uri>
```
DATABASE_URL is the variable being called in the connection pool in squatify-backend\db\connection.js


## Tech Stack

**Client:** React, styled components

**Server:** Node, Express, PostgreSQL

**Database** Heroku


## What We Learnt

- Used styled components for the first time
- Cemented various React concepts (state, props, useEffect)
- Figma collaboration (wireframes)

## Challenges

- Infinite loop caused by incorrect use of useEffect hook (We used a piece of boolean state to fix this. See useful links section below on useEffect loops)
- Deployment of backend repository on heroku (Environment variabled needed amending in .env file)
- Initial rendering of styled components (Read through the docs and overcame this fairly quickly)

## Take Aways
This experience has helped us reinforce our learning of working in an Agile environment.
We used various project managements tools such as Trello and Figjam. 
We stuck to Agile principles (ticket backlogs, retrospective and stand-up discussions)
Took on an iterative approach to our project build which paid off.

Focused on Team work and collaboration.

Our ability to work with React and deploy full stack applications has become more natural.

## Useful Links



- [styled components](https://styled-components.com/docs)
- [How to Solve the Infinite Loop of React.useEffect()](https://dmitripavlutin.com/react-useeffect-infinite-loop/)
## Authors

- [@anastasia-starostina](https://www.github.com/anastasia-starostina)
- [@BlakeLawrence](https://www.github.com/BlakeLawrence)
- [@DHawkesford](https://github.com/DHawkesford)
- [@AureaFlamme](https://github.com/AureaFlamma)
