<a name="readme-top"></a>
<!-- PROJECT SHIELDS -->
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]


<!-- PROJECT LOGO -->
<br />
<div align="center">

  <h3 align="center">Boss Machine</h3>

  <p align="center">
    Node.js/express API (CRUD) and front-end React project
    <br />
    <br />
    <!-- <a href="#">View Live</a>  -->
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#project-Requirements">Project Requirements</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project
[![Product Name Screen Shot][product-screenshot]]()

I was assigned this project as part of Codecademy's Full stack engineering bootcamp. I had to create an entire API to serve information to a Boss Machine, a unique management application for today's most accomplished (evil) entrepreneurs. Leveraging Express.js I created routes to manage the 'minions', the brilliant 'million dollar ideas', and to handle all the annoying meetings that keep getting added to the busy schedule.

<p align="right">(<a href="#readme-top">back to top</a>)</p>


### Built With

[![Express][Express.js]][Express-url]
[![Node][Node.js]][Node-url]
[![React][React.js]][React-url]
[![Redux][Redux.js]][Redux-url]
[![JavaScript][JavaScript]][JavaScript-url]
[![CSS][CSS]][CSS-url]
[![HTML][HTML]][HTML-url]

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started

This is an example of how you may give instructions on setting up your project locally.
To get a local copy up and running follow these simple example steps.

### Prerequisites

* Google Chrome (at least version 60) or Firefox (at least version 55)
* npm
  ```sh
  npm install npm@latest -g
  ```

### Installation

1. Download the project
2. Install NPM packages
   ```sh
   npm install
   ```
3. If you have problems, you may have to
   ```sh
   npm install --force
   ```
4. Start local development server 
   ```sh
   npm run start
   ```
5. View on http://localhost:4001/
6. To run testing 
  ```sh
   npm run test
   ```


<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- PROJECT REQUIREMENTS -->
## Project Requirements
1. Intial Setup
- [ x ] Set up body-parsing middleware with the body-parser package.
- [ x ] Set up CORS middleware with the cors package. You can use the default settings.
- [ x ] Mount the existing apiRouter at /api. This router will serve as the starting point for all your API routes.
- [ x ] Start the server listening on the provided PORT. Make sure to use the PORT constant and not a hard-coded number, as this is required for tests to run.

2. Minions Routes
- [ x ] GET /api/minions to get an array of all minions.
- [ x ] POST /api/minions to create a new minion and save it to the database.
- [ x ] GET /api/minions/:minionId to get a single minion by id.
- [ x ] PUT /api/minions/:minionId to update a single minion by id.
- [ x ] DELETE /api/minions/:minionId to delete a single minion by id.

3. Ideas Routes
- [x] GET /api/ideas to get an array of all ideas.
- [x] POST /api/ideas to create a new idea and save it to the database.
- [x] GET /api/ideas/:ideaId to get a single idea by id.
- [x] PUT /api/ideas/:ideaId to update a single idea by id.
- [x] DELETE /api/ideas/:ideaId to delete a single idea by id.

4. Meetings Routes
- [x] GET /api/meetings to get an array of all meetings.
- [x] POST /api/meetings to create a new meeting and save it to the database.
- [x] DELETE /api/meetings to delete all meetings from the database.

5. Custom Middleware
- [x] Create custom middleware function to ensure that any new or updated idea is worth at least a million dollars.

6. Bonus
- [x] Create work routes that allow bosses to add and remove work from their minions' backlogs.

See the [open issues](https://github.com/Patchalv/boss-machine/issues) for a full list of proposed features (and known issues).

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- CONTACT -->
## Contact

Patrick Alvarez Eades - p.alvarezeades@gmail.com

Project Link: [https://github.com/Patchalv/boss-machine](https://github.com/Patchalv/boss-machine)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

A big shout out to [Codecademy](https://www.codecademy.com/) who I'm currently doing the Full-Stack Engeineer career path with!

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/Patchalv/boss-machine.svg?style=for-the-badge
[contributors-url]: https://github.com/Patchalv/boss-machine/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/Patchalv/boss-machine.svg?style=for-the-badge
[forks-url]: https://github.com/Patchalv/boss-machine/network/members
[stars-shield]: https://img.shields.io/github/stars/Patchalv/boss-machine.svg?style=for-the-badge
[stars-url]: https://github.com/Patchalv/boss-machine/stargazers
[issues-shield]: https://img.shields.io/github/issues/Patchalv/boss-machine.svg?style=for-the-badge
[issues-url]: https://github.com/Patchalv/boss-machine/issues
[license-shield]: https://img.shields.io/github/license/Patchalv/boss-machine?label=license&style=for-the-badge
[license-url]: https://github.com/Patchalv/boss-machine/blob/master/LICENSE.md
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/patrickalvarezeades/
[product-screenshot]: ./public/img/screenshot.png
[Next.js]: https://img.shields.io/badge/next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white
[Next-url]: https://nextjs.org/
[React.js]: https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB
[React-url]: https://reactjs.org/
[Redux.js]: https://img.shields.io/badge/Redux-593D88?style=for-the-badge&logo=redux&logoColor=white
[Redux-url]: https://redux.js.org/
[Bootstrap.com]: https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white
[Bootstrap-url]: https://react-bootstrap.netlify.app/
[Express.js]: https://img.shields.io/badge/Express.js-404D59?style=for-the-badge
[Express-url]: https://expressjs.com/
[Node.js]: https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white
[Node-url]: https://nodejs.org/
[HTML]: https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white
[HTML-url]: #
[CSS]: https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white
[CSS-url]: #
[JavaScript]: https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E
[JavaScript-url]: #
