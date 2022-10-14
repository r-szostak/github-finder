[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![LinkedIn][linkedin-shield]][linkedin-url]
<br />

<div align="center">

<h3 align="center">Github finder app</h3>

  <p align="center">
     App to search Github users and display their info, repositories, details.
    <br />
    <br />
    <br />
    <a href="https://github-finder-app-theta-ten.vercel.app">View Demo</a>
    ·
    <a href="https://github.com/r-szostak/github-finder/issues">Report Bug</a>
    ·
    <a href="https://github.com/r-szostak/github-finder/issues">Request Feature</a>
  </p>
</div>

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
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->

## About The Project

[![Product Name Screen Shot][product-screenshot]](https://github-finder-app-theta-ten.vercel.app)

App to search Github users and display their info, repositories, details.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Built With

- [![React][react.js]][react-url] [![Tailwind CSS][tailwind-css]][tailwind-url]

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- GETTING STARTED -->

## Getting Started

Rename **_.env.example_** to **_.env_**

You can use the Github API without a personal token, but if you want to use your token, add it to the .env file

Learn how to create a token [here](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token)

### Prerequisites

- npm
  ```sh
  npm install
  ```

### Installation

1. Get a free token at [https://github.com](https://github.com)
2. Clone the repo
   ```sh
   git clone https://github.com/r-szostak/github-finder.git
   ```
3. Install NPM packages
   ```sh
   npm install
   ```
4. Enter your token in `.env` file
   ```js
   const REACT_APP_GITHUB_TOKEN = "ENTER YOUR API"
   ```

### Run

```sh
npm start
```

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTACT -->

## Contact

Rafał Szostak - rafal.szostak2@gmail.com
[![LinkedIn][linkedin-shield]][linkedin-url]

Project Link: [https://github.com/r-szostak/github-finder](https://github.com/r-szostak/github-finder)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->

[forks-shield]: https://img.shields.io/github/forks/r-szostak/github-finder.svg?style=for-the-badge
[forks-url]: https://github.com/r-szostak/github-finder/network/members
[stars-shield]: https://img.shields.io/github/stars/r-szostak/github-finder.svg?style=for-the-badge
[stars-url]: https://github.com/r-szostak/github-finder/stargazers
[issues-shield]: https://img.shields.io/github/issues/r-szostak/github-finder.svg?style=for-the-badge
[issues-url]: https://github.com/r-szostak/github-finder/issues
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/rsz/
[product-screenshot]: public/preview.png
[react.js]: https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB
[react-url]: https://reactjs.org/
[tailwind-css]: https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white
[tailwind-url]: https://tailwindcss.com
