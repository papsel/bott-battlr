#  Code Challenge: Bot Battlr
Welcome to **Bot Battlr**, the one and only spot in the known universe where you can custom build your own Bot Army! This is our app:
This project was bootstrapped with [Create React App]

Here's the scenario: a galactic overlord has hired you, a galactic web developer, to develop a galactic web app that will allow them to browse through a list of robots, view a robot's details, and, enlist a bot into their army.
## Instructions
For this project, you’ll be building out a React application that displays a list of available bots, among other features. Try your best to find the right places to insert code into the established code base.

Part of what this code challenge is testing is your ability to follow given instructions. While you will definitely have a significant amount of freedom in how you implement the features, be sure to carefully read the directions for setting up the application.

## Setup

After cloning down the project:

1. Run `npm install` in your terminal
2. Run `npm start`: This will open both your React page
In the project directory, you can run:

The base URL for your backend is: `http://localhost:6001`

These are the endpoints you might need:

- GET: `/bots`
- POST: `/bots`
- DELETE: `/bots/:id`
# Core Deliverables
You already have the following 
BotPage` is the highest component below App, and serves as the main container for all of the pieces of the page.

`BotCollection` and `YourBotArmy` are container components, which are children of `BotPage`. `BotCollection` is where all the bots will be displayed, while `YourBotArmy` (the green portion on the top of the screen) will only display the bots that have been selected by the user.

`BotCard` and `BotSpecs` are presentational components that have been provided for you that will render out information about an individual bot formatted for a list view and for a full view, respectively. They are pre-styled, and it is your responsibility to get the data into them.

All of the code to style the page has been written for you, meaning that you should be adding to the code rather than editing it; however, if your finished product has some styling issues, don't worry too much about it.
As a user, I should be able to:

- See profiles of all bots rendered in `BotCollection`.
- Add an individual bot to my army by clicking on it. The selected bot should render in the `YourBotArmy` component. The bot can be enlisted only **once**. The bot **does not** disappear from the `BotCollection`.
- Release a bot from my army by clicking on it. The bot disappears from the `YourBotArmy` component.
- Discharge a bot from their service forever, by clicking the red button marked "x", which would delete the bot both from the backend and from the `YourBotArmy` on the frontend.
## Requirements
To run this program you need to have a mobile phone / a computer that has stable internet connection