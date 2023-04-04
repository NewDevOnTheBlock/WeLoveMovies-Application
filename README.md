<br/>
<p align="center">
  <a href="https://github.com/NewDevOnTheBlock/https://github.com/NewDevOnTheBlock/WeLoveMovies-Application">
    <img src="images/logo.png" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">We Love Movies!</h3>

  <p align="center">
    A web based theatre application that gives the movies and showtimes currently showing in theatres, displays relevant information dependent upon whether or not the movie is currently showing per theatre. 
    <br/>
    <br/>
    <a href="https://github.com/NewDevOnTheBlock/https://github.com/NewDevOnTheBlock/WeLoveMovies-Application"><strong>Explore the docs »</strong></a>
    <br/>
    <br/>
    <a href="https://github.com/NewDevOnTheBlock/https://github.com/NewDevOnTheBlock/WeLoveMovies-Application">View Demo</a>
    .
    <a href="https://github.com/NewDevOnTheBlock/https://github.com/NewDevOnTheBlock/WeLoveMovies-Application/issues">Report Bug</a>
    .
    <a href="https://github.com/NewDevOnTheBlock/https://github.com/NewDevOnTheBlock/WeLoveMovies-Application/issues">Request Feature</a>
  </p>
</p>

![Downloads](https://img.shields.io/github/downloads/NewDevOnTheBlock/https://github.com/NewDevOnTheBlock/WeLoveMovies-Application/total) ![Contributors](https://img.shields.io/github/contributors/NewDevOnTheBlock/https://github.com/NewDevOnTheBlock/WeLoveMovies-Application?color=dark-green) ![Issues](https://img.shields.io/github/issues/NewDevOnTheBlock/https://github.com/NewDevOnTheBlock/WeLoveMovies-Application) ![License](https://img.shields.io/github/license/NewDevOnTheBlock/https://github.com/NewDevOnTheBlock/WeLoveMovies-Application) 

## Table Of Contents

* [About the Project](#about-the-project)
* [Built With](#built-with)
* [Getting Started](#getting-started)
  * [Prerequisites](#prerequisites)
  * [Installation](#installation)
* [Usage](#usage)
* [Roadmap](#roadmap)
* [Contributing](#contributing)
* [License](#license)
* [Authors](#authors)
* [Acknowledgements](#acknowledgements)

## About The Project

![Screen Shot](https://we-love-movies-frontend-qip9.onrender.com)

You can view a deployed version of this app at: 
https://we-love-movies-frontend-qip9.onrender.com

Note: Render can take a minute to show relevant information retrieved from the DB. This is a common issue with deployment on Render, but rest assured that the app is functioning and does indeed work properly. If all else fails, try either refreshing the page, or loading in from a new window.

This is a full-stack application that allows users to view movies, showtimes, and reviews of movies. If given a query parameter (isShowing?=true), it will only display movies that are showing currently in the theatre. Each movie has a list of reviews made by critics that can be updated depending up on who attempts to make changes. 

A user can:
- View which movies are playing
- View what times movies are playing
- See reviews for said movies
- See the critic who made the review
- See a list of critiques a given critic has made

This application was made using a relational database and a RESTful API that utilized Express.js for API development and Knex.js for DB querying on API endpoint access. The database was developed using a relational database (PostgreSQL). It mainly allows you to list and read information from the db.

## Built With

Front-End Technologies Used:
- HTML/CSS/JavaScript
- React.js
- React-Router-Dom
- Bootstrap (style)

Back-End Technologies Used:
- PostgreSQL (Relational Database)
- Express.js (RESTful API development)
- Knex.js (database querying)
- Cors
- dotenv
- path
- lodash
- nodemon (server used for development)

## Getting Started

To get started locally, you can fork the repo or download the .zip (be sure to extract it!) as normal, then after you use the command line to cd your way into the directory. After doing so, a simple "npm i" is more than enough to get the project up and running. 

To run the front-end, just enter "npm run start:react"
to run the back-end, just use "npm run start:dev"

### Prerequisites

This is an example of how to list things you need to use the software and how to install them.

* npm

```sh
npm install npm@latest -g
```

### Installation

1. Clone the repo

```sh
git clone https://github.com/your_username_/Project-Name.git
```

2. Install NPM packages

```sh
npm install
```

## Usage

The purpose of this project was to develop a RESTful API that allows a user to retrieve and render information to a web based application via a fetch request made in a useEffect() react hook. This application allows a user to view what movies are playing, what time they are playing, and see any critiques about a movie they may be interested in. It also allowed me to create a relational database that uses 3 different tables joined together for: Theatres, Movies, and Critics during the queries. 

## Roadmap

See the [open issues](https://github.com/NewDevOnTheBlock/https://github.com/NewDevOnTheBlock/WeLoveMovies-Application/issues) for a list of proposed features (and known issues).

## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.
* If you have suggestions for adding or removing projects, feel free to [open an issue](https://github.com/NewDevOnTheBlock/https://github.com/NewDevOnTheBlock/WeLoveMovies-Application/issues/new) to discuss it, or directly create a pull request after you edit the *README.md* file with necessary changes.
* Please make sure you check your spelling and grammar.
* Create individual PR for each suggestion.
* Please also read through the [Code Of Conduct](https://github.com/NewDevOnTheBlock/https://github.com/NewDevOnTheBlock/WeLoveMovies-Application/blob/main/CODE_OF_CONDUCT.md) before posting your first idea as well.

### Creating A Pull Request

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

Distributed under the MIT License. See [LICENSE](https://github.com/NewDevOnTheBlock/https://github.com/NewDevOnTheBlock/WeLoveMovies-Application/blob/main/LICENSE.md) for more information.

## Authors

* **Pierce DeAnda** - *Full-Stack Engineer* - [Pierce DeAnda](https://github.com/NewDevOnTheBlock/) - *Primary Contributor and Programmer*

## Acknowledgements

* [Pierce DeAnda](https://github.com/NewDevOnTheBlock/)
* [Keith Van](https://github.com/https://github.com/NVious7/)
* [PostgreSQL docs](https://www.postgresql.org/)
* [React Docs](https://legacy.reactjs.org/docs/getting-started.html)
