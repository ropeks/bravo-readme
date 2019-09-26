# Bravo
 You can find the deployed project at https://saybravo.io
## Contributors
|                                       [Samar Vir](https://github.com/samarv)                                        |                                       [Aaron Thompson](https://github.com/AaronJThompson)                                        |                                       [James Eneh](https://github.com/erozonachi)                                        |                                       [Borja Soler](https://github.com/borjasolerr)                                        |                                       [Johnson Ogwuru](https://github.com/ogwurujohnson)                                        |
| :-----------------------------------------------------------------------------------------------------------: | :-----------------------------------------------------------------------------------------------------------: | :-----------------------------------------------------------------------------------------------------------: | :-----------------------------------------------------------------------------------------------------------: | :-----------------------------------------------------------------------------------------------------------: |
|                      [<img src="https://www.dalesjewelers.com/wp-content/uploads/2018/10/placeholder-silhouette-male.png" width = "200" />](https://github.com/samarv)                       |                      [<img src="https://www.dalesjewelers.com/wp-content/uploads/2018/10/placeholder-silhouette-female.png" width = "200" />](https://github.com/AaronJThompson)                       |                      [<img src="https://www.dalesjewelers.com/wp-content/uploads/2018/10/placeholder-silhouette-male.png" width = "200" />](https://github.com/erozonachi)                       |                      [<img src="https://www.dalesjewelers.com/wp-content/uploads/2018/10/placeholder-silhouette-female.png" width = "200" />](https://github.com/borjasolerr)                       |                      [<img src="https://www.dalesjewelers.com/wp-content/uploads/2018/10/placeholder-silhouette-male.png" width = "200" />](https://github.com/ogwurujohnson)                       |
|                 [<img src="https://github.com/favicon.ico" width="15"> ](https://github.com/samarv)                 |            [<img src="https://github.com/favicon.ico" width="15"> ](https://github.com/AaronJThompson)             |           [<img src="https://github.com/favicon.ico" width="15"> ](https://github.com/erozonachi)            |          [<img src="https://github.com/favicon.ico" width="15"> ](https://github.com/borjasolerr)           |            [<img src="https://github.com/favicon.ico" width="15"> ](https://github.com/ogwurujohnson)             |
| [ <img src="https://static.licdn.com/sc/h/al2o9zrvru7aqj8e1x2rzsrca" width="15"> ](https://www.linkedin.com/) | [ <img src="https://static.licdn.com/sc/h/al2o9zrvru7aqj8e1x2rzsrca" width="15"> ](https://www.linkedin.com/) | [ <img src="https://static.licdn.com/sc/h/al2o9zrvru7aqj8e1x2rzsrca" width="15"> ](https://www.linkedin.com/) | [ <img src="https://static.licdn.com/sc/h/al2o9zrvru7aqj8e1x2rzsrca" width="15"> ](https://www.linkedin.com/) | [ <img src="https://static.licdn.com/sc/h/al2o9zrvru7aqj8e1x2rzsrca" width="15"> ](https://www.linkedin.com/) |
|                                       [__Maxime Salomon__](https://github.com/maximesalomon)                                        |                                       [__Noble Obioma__](https://github.com/nobioma1)                                        |                                       [__Petar Vlaisavljevic__](https://github.com/ropeks)                                        |
|                      [<img src="https://www.dalesjewelers.com/wp-content/uploads/2018/10/placeholder-silhouette-male.png" width = "200" />](https://github.com/maximesalomon)                       |                      [<img src="https://www.dalesjewelers.com/wp-content/uploads/2018/10/placeholder-silhouette-female.png" width = "200" />](https://github.com/nobioma1)                       |                      [<img src="https://www.dalesjewelers.com/wp-content/uploads/2018/10/placeholder-silhouette-male.png" width = "200" />](https://github.com/ropeks)                       |
|                 [<img src="https://github.com/favicon.ico" width="15"> ](https://github.com/maximesalomon)                 |            [<img src="https://github.com/favicon.ico" width="15"> ](https://github.com/nobioma1)             |           [<img src="https://github.com/favicon.ico" width="15"> ](https://github.com/ropeks)            |
| [ <img src="https://static.licdn.com/sc/h/al2o9zrvru7aqj8e1x2rzsrca" width="15"> ](https://www.linkedin.com/) | [ <img src="https://static.licdn.com/sc/h/al2o9zrvru7aqj8e1x2rzsrca" width="15"> ](https://www.linkedin.com/) | [ <img src="https://static.licdn.com/sc/h/al2o9zrvru7aqj8e1x2rzsrca" width="15"> ](https://www.linkedin.com/) |
## Project Overview
[Trello Board](https://trello.com/b/RmnRC4ez/labs) <br>
[Product Canvas](https://www.notion.so/Acknowledge-Coworkers-in-Slack-96c60f39816b477d9b81fe5d97a992ee) <br>
[UX Design files](https://www.figma.com/file/SbSjn8oAUtdWY1slSJeP9u/Bravo) <br>

Healthy office cultures often acknowledge good work from their coworkers and peers. Award your peers with acknowledgements that act like coins/points in Slack when they do awesome things - and never let the acknowledgement of their good work get lost in the shuffle again.
### Key Features
-    users can send public shoutouts to their teammates for their good work in Slack
-    users can see all the shoutouts for given teammate in Slack
-    for every shoutout, comment or reaction to shoutout users get bravos
-    users can see how many bravos they have in their wallet in Slack
-    users can see their Slack workspace leaderboard in Slack
-    users can see their and their teammates' profiles in the webapp
-    users can view single shoutout with comments and reactions in the webapp
-    users can see feed of all shoutouts in the webapp
-    users can see who is in their team (Slack workspace) in the webapp
-    users can see their Slack workspace leaderboard in the webapp
## Tech Stack
#### Front end built using:
-    _React_
-    _Slack API Auth_
-    _Styled-Components_
#### Front end deployed to `Netlify`
#### [Back end](https://github.com/bravolabs/bravo-be) built using:
-    _NodeJS (Express)_
-    _PostgreSQL_
# APIs
We use [Slack API](https://api.slack.com/) for both authentication and our Slack bot.
# Environment Variables
In order for the app to function correctly, the user must set up their own environment variables. There should be a .env file containing the following:

    REACT_APP_API_HOST = link to your API host
    REACT_APP_CLIENT_ID = your Slack app's client ID, can be found in you app's settings --> basic information
    REACT_APP_CLIENT_SECRET = your Slack app's client secret, can be found in you app's settings --> basic information

# Content Licenses

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

# Installation Instructions
## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

For development, you will only need Node.js installed on your environment.

    $ node --version
    v10.16.0

    $ npm --version
    6.10.3

### Installing

    $ https://github.com/bravolabs/bravo-fe.git
    $ cd bravo-fe
    $ npm install

### Starting Development Server

    $ npm start

Runs the app in the development mode.
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.
The page will reload if you make edits.

### Running the tests

    $ npm test

Launches the test runner in the interactive watch mode.

### Deployment / Build For Production

    $ npm run build

Builds the app for production to the `build` folder.

### Linting fix

    $ npm lint:fix

Fixes linting automatically.

### Coverage reporting

    $ npm coverage

Reports coverage with disabled test-watching.

### Eject hidden modules

    $ npm eject

Ejects hidden modules into `package.json`.

# Contributing
When contributing to this repository, please first discuss the change you wish to make via issue, email, or any other method with the owners of this repository before making a change.
Please note we have a [code of conduct](./CODE_OF_CONDUCT.md). Please follow it in all your interactions with the project.
## Issue/Bug Request
   
 **If you are having an issue with the existing project code, please submit a bug report under the following guidelines:**
 - Check first to see if your issue has already been reported.
 - Check to see if the issue has recently been fixed by attempting to reproduce the issue using the latest master branch in the repository.
 - Create a live example of the problem.
 - Submit a detailed bug report including your environment & browser, steps to reproduce the issue, actual and expected outcomes,  where you believe the issue is originating from, and any potential solutions you have considered.
### Feature Requests
We would love to hear from you about new features which would improve this app and further the aims of our project. Please provide as much detail and information as possible to show us why you think your new feature should be implemented.
### Pull Requests
If you have developed a patch, bug fix, or new feature that would improve this app, please submit a pull request. It is best to communicate your ideas with the developers first before investing a great deal of time into a pull request to ensure that it will mesh smoothly with the project.
Remember that this project is licensed under the MIT license, and by submitting a pull request, you agree that your work will be, too.
#### Pull Request Guidelines
- Ensure any install or build dependencies are removed before the end of the layer when doing a build.
- Update the README.md with details of changes to the interface, including new plist variables, exposed ports, useful file locations and container parameters.
- Ensure that your code conforms to our existing code conventions and test coverage.
- Include the relevant issue number, if applicable.
- You may merge the Pull Request in once you have the sign-off of two other developers, or if you do not have permission to do that, you may request the second reviewer to merge it for you.
### Attribution
These contribution guidelines have been adapted from [this good-Contributing.md-template](https://gist.github.com/PurpleBooth/b24679402957c63ec426).
## Documentation
See [Backend Documentation](https://github.com/bravolabs/bravo-be/blob/develop/README.md) for details on the backend of our project.
