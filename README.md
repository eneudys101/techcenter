<div id="top"></div>

[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]



<br />
<div align="center">

<h3 align="center">TechCenter</h3>

  <p align="center">
    TechCenter is a system designed for school district I.T. departments.
    <br />
    <a href="https://github.com/eneudys101/techcenter-2.0"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/eneudys101/techcenter-2.0/issues">Report Bug</a>
    ·
    <a href="https://github.com/eneudys101/techcenter-2.0/issues">Request Feature</a>
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
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

The purpose of this project is to build a platform where I.T. departments in school districts can keep information about their users, printers, and inventory of any kind. TechCenter will include a ticketing system that will tie in with the inventory and users system.

<p align="right">(<a href="#top">back to top</a>)</p>



### Built With

* [Django](https://www.djangoproject.com)
* [Bootstrap](https://getbootstrap.com)

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started
These steps are for development installation only and should not be followed for production.
To start create a folder where the project will recide. For the presequisite you can create your own database or use the provided `docker-compose` file.

### Prerequisites

Required 

Make sure docker is up and running if you go the `docker-compose` route 

1. Setup database
   
   A postgres database setup is 

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/eneudys101/techcenter-2.0.git
   ```
2. Create Python virtual enviroment 
   ```sh
   python3 -m venv name-of-environment
   ```
3. activate virtual enviroment 
   - On Windows:
   ```sh
   name-of-environment\Scripts\activate.bat
   ```
   - On Unix, Linux or MacOS:
   ```sh
   source tutorial-env/bin/activate
   ```
4. Install python modules
   ```sh
   pip install -r requirements.txt
   ```
5. Setup database
   ```sh
   docker-compose up
   ```
<p align="right">(<a href="#top">back to top</a>)</p>



<!-- USAGE EXAMPLES -->
## Usage

Use this space to show useful examples of how a project can be used. Additional screenshots, code examples and demos work well in this space. You may also link to more resources.

_For more examples, please refer to the [Documentation](https://example.com)_

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- ROADMAP -->
## Roadmap

- [ ] Feature 1
- [ ] Feature 2
- [ ] Feature 3
    - [ ] Nested Feature

See the [open issues](https://github.com/eneudys101/techcenter-2.0/issues) for a full list of proposed features (and known issues).

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Your Name - [@twitter_handle](https://twitter.com/twitter_handle) - email@email_client.com

Project Link: [https://github.com/eneudys101/techcenter-2.0](https://github.com/eneudys101/techcenter-2.0)

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

* []()
* []()
* []()

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/eneudys101/techcenter-2.0.svg?style=for-the-badge
[contributors-url]: https://github.com/eneudys101/techcenter-2.0/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/eneudys101/techcenter-2.0.svg?style=for-the-badge
[forks-url]: https://github.com/eneudys101/techcenter-2.0/network/members
[stars-shield]: https://img.shields.io/github/stars/eneudys101/techcenter-2.0.svg?style=for-the-badge
[stars-url]: https://github.com/eneudys101/techcenter-2.0/stargazers
[issues-shield]: https://img.shields.io/github/issues/eneudys101/techcenter-2.0.svg?style=for-the-badge
[issues-url]: https://github.com/eneudys101/techcenter-2.0/issues
[license-shield]: https://img.shields.io/github/license/eneudys101/techcenter-2.0.svg?style=for-the-badge
[license-url]: https://github.com/eneudys101/techcenter-2.0/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/linkedin_username
[product-screenshot]: images/screenshot.png
