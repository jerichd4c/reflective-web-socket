<a id="readme-top"></a>

<!-- PROJECT SHIELDS -->
<div align="center">

[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]

</div>

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <h3 align="center">Reflective Socket Project</h3>

  <p align="center">
    A Java application that uses reflection and sockets to invoke methods on remote objects dynamically.
    <br />
    <a href="https://github.com/jerichd4c/ReflectiveSocketProyect"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/jerichd4c/ReflectiveSocketProyect/issues">Report Bug</a>
    &middot;
    <a href="https://github.com/jerichd4c/ReflectiveSocketProyect/issues">Request Feature</a>
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
    <li><a href="#usage">Usage</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->
## About The Project

This project demonstrates a distributed system where a client can invoke methods on server-side objects using Java Reflection. The server hosts various business objects, and the client communicates over TCP sockets to execute logic remotely.

### Built With

* [![Java][Java-shield]][Java-url]

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- GETTING STARTED -->
## Getting Started

To get a local copy up and running, follow these steps.

### Prerequisites

* Java Development Kit (JDK) 8 or higher.

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/jerichd4c/ReflectiveSocketProyect.git
   ```
2. Compile the project (if using an IDE like IntelliJ, it will handle this automatically).
3. Run the `BusinessApp` class located in `src/BusinessApp.java`.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- USAGE EXAMPLES -->
## Usage

When you run `BusinessApp`, you will see a menu to interact with different remote services:

1. **Calculator**: Perform arithmetic operations.
2. **Text Modifier**: Manipulate strings.
3. **Converter**: Convert data formats.

The application starts three socket servers on ports 5000, 5001, and 5002 to handle these requests.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTACT -->
## Contact

Your Name - [@twitter_handle](https://twitter.com/twitter_handle) - email@example.com

Project Link: [https://github.com/jerichd4c/ReflectiveSocketProyect](https://github.com/jerichd4c/ReflectiveSocketProyect)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- MARKDOWN LINKS & IMAGES -->
[contributors-shield]: https://img.shields.io/github/contributors/jerichd4c/ReflectiveSocketProyect.svg?style=for-the-badge
[contributors-url]: https://github.com/jerichd4c/ReflectiveSocketProyect/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/jerichd4c/ReflectiveSocketProyect.svg?style=for-the-badge
[forks-url]: https://github.com/jerichd4c/ReflectiveSocketProyect/network/members
[stars-shield]: https://img.shields.io/github/stars/jerichd4c/ReflectiveSocketProyect.svg?style=for-the-badge
[stars-url]: https://github.com/jerichd4c/ReflectiveSocketProyect/stargazers
[issues-shield]: https://img.shields.io/github/issues/jerichd4c/ReflectiveSocketProyect.svg?style=for-the-badge
[issues-url]: https://github.com/jerichd4c/ReflectiveSocketProyect/issues
[license-shield]: https://img.shields.io/github/license/jerichd4c/ReflectiveSocketProyect.svg?style=for-the-badge
[license-url]: https://github.com/jerichd4c/ReflectiveSocketProyect/blob/master/LICENSE.txt
[Java-shield]: https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white
[Java-url]: https://www.oracle.com/java/
