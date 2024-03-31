<!-- Inspired by https://github.com/jennifertakagi/fitness-pass -->

<!-- PROJECT SHIELDS -->

[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]

<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="https://github.com/jennifertakagi/fitness-pass">
    <img src="docs/logo.png" alt="Logo" width="150">
  </a>

  <h3 align="center">Fitness API</h3>

  <p align="center">
    Check-in at your favorite gym!
    <br />
    <a href="https://github.com/jennifertakagi/fitness-pass"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/jennifertakagi/fitness-pass/issues">Report Bug</a>
    ·
    <a href="https://github.com/jennifertakagi/fitness-pass/issues">Request Feature</a>
  </p>
</p>

<!-- TABLE OF CONTENTS -->
<details open="open">
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
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgements">Acknowledgements</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->

## About The Project

Manage check-in in your gym with this API

Features:

- Route to check-in in a gym
- Route to get check-in history
- Route to get user metrics
- Route to validate a check-in

- Route to register a gym
- Route to get nearby gyms
- Route to search gym

- Route to authenticate a user
- Route to get a user profile
- Route to refresh user token
- Route to register a user

### Built With

- [Bcryptjs](https://www.npmjs.com/package/bcryptjs)
- [Node JS](https://nodejs.org/en/)
- [Prisma](https://www.prisma.io/)
- [Supertest](https://www.npmjs.com/package/supertest)
- [TypeScript](https://www.typescriptlang.org/)
- [Vitest](https://vitest.dev/)
- [Zod](https://zod.dev/)

<!-- GETTING STARTED -->

## Getting Started

### Prerequisites

- npm

  ```sh
  npm install npm@latest -g
  ```

- yarn

  ```sh
  npm install --global yarn
  ```

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/jennifertakagi/fitness-pass.git
   ```
2. Install packages

   ```sh
   yarn | npm install
   ```

3. Run the local environment
   ```sh
    yarn start:dev | npm run start:dev
   ```

<!-- ROADMAP -->

## Roadmap

See the [open issues](https://github.com/jennifertakagi/fitness-pass/issues) for a list of proposed features (and known issues).

<!-- CONTRIBUTING -->

## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<!-- LICENSE -->

## License

Distributed under the MIT License. See `LICENSE` for more information.

<!-- CONTACT -->

## Contact

Jennifer Takagi - [@jennitakagi](https://twitter.com/jennitakagi)

<!-- ACKNOWLEDGEMENTS -->

## Acknowledgements

- [ESLint](https://eslint.org/)
- [Prettier](https://prettier.io/)

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->

[contributors-shield]: https://img.shields.io/github/contributors/jennifertakagi/fitness-pass.svg?style=for-the-badge
[contributors-url]: https://github.com/jennifertakagi/fitness-pass/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/jennifertakagi/fitness-pass.svg?style=for-the-badge
[forks-url]: https://github.com/jennifertakagi/fitness-pass/network/members
[stars-shield]: https://img.shields.io/github/stars/jennifertakagi/fitness-pass.svg?style=for-the-badge
[stars-url]: https://github.com/jennifertakagi/fitness-pass/stargazers
[issues-shield]: https://img.shields.io/github/issues/jennifertakagi/fitness-pass.svg?style=for-the-badge
[issues-url]: https://github.com/jennifertakagi/fitness-pass/issues
[license-shield]: https://img.shields.io/github/license/jennifertakagi/fitness-pass.svg?style=for-the-badge
[license-url]: https://github.com/jennifertakagi/fitness-pass/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/jennifertakagi
