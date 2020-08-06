# Team Fuze Overwatch Teambuilder

<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a>
    <img src="public/image/FUZE2.png" alt="Logo" width="80" height="80">
  </a>
</p>



<!-- TABLE OF CONTENTS -->
## Table of Contents

* [About the Project](#about-the-project)
  * [Built With](#built-with)
* [Getting Started](#getting-started)
  * [Prerequisites](#prerequisites)
  * [Installation](#installation)
* [Usage](#usage)
* [Contributers](#contributers)

<!-- ABOUT THE PROJECT -->
## About The Project

![FUZE](public/image/sign-in.png)
Fuze is a web-application for a user to find a team for Overwatch on what criteria a user is looking for.

Once a user is sign up and logged in they can create a team or join a team. 

The creation of this project came about of our hobby of playing video games.

[Link to deployed project](https://fuzeteam.herokuapp.com/signin)
### Built With
* [Bootstrap](https://getbootstrap.com)
* [Javascript](https://www.javascript.com/)
* [jQuery](https://jquery.com/)
* [Passport](http://www.passportjs.org/)
* [Handlebars](https://handlebarsjs.com/)
* [Express](https://expressjs.com/)
* [Node](https://nodejs.org/en/)
* [Overwatch API](https://ow-api.com)

<!-- GETTING STARTED -->
## Getting Started

### Prerequisites

Have Visual Studio Code installed or similar application

### Installation

In your favorite terminal do the following:

1. Clone the repo
```sh
git clone https://github.com/Jcabs14/Fuze.git
```
2. Install NPM packages
```sh
npm install
```
3. Start locally
```sh
npm start (When you are in the applications folder)
```

<!-- USAGE EXAMPLES -->
## Usage

1. ***A user will be instructed to sign in, if a user doesn't have a log in they can created a account by clicking the sign up button.***

2. ***Once logged in a user will be redirected to the team list page***

3. ***On the team list page a user can do the following:***
    1. **Create a team**
        1. A team can be created by entering a team name and a description
        2. Then clicking submit
        3. The team will be added to the List of Teams
    2. Look at a created team already by clicking it and a user will be sent to the team lobby page

4. ***On the team lobby page a user can do the following:***
    1. **Join a team by clicking join a team button**
        1. Once a user joins a team they will be inserted into a slot on the team where their battle-tag will be shown
            1. Users then can invite each other on Overwatch using their battletag

<!-- CONTRIBUTERS -->
## Contributers

Adrian Situ - Javascript & Handlebars

Jared Cabanilla - Overwatch API

Rachel Gundy - User Interface

Tim Holeski - Passport authentication






