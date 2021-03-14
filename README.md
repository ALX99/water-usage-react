# Water usage react

A simple react app that displays news regarding the Earth's water, water usage by country and a quiz.  
This was crearted for the course Agile software project management - DIT257

## Demo

[![Endor preview](http://i3.ytimg.com/vi/r_L4iqSjTN4/hqdefault.jpg)](https://www.youtube.com/watch?v=r_L4iqSjTN4)

## Running our project

### Dependencies

1. Install [nodejs](https://nodejs.org/en/download/)
2. install [yarn](https://classic.yarnpkg.com/en/docs/install)
3. Navigate to app/ inside the repo
4. `yarn upgrade`
5. (for production build) `npm i -g serve`

### Testing (Inside of app/)

`yarn test --env jest-environment-jsdom-sixteen`

### Running (Inside of app/)

#### Development build

`yarn start`

#### Production build

1. `yarn build`
2. `serve -s build -l [port]`
