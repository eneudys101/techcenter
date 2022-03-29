<div id="top"></div>

[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]

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
All the files to get the project up and running have been provided in the repo. You can feel free to build the database and the python enviroment with any method but make sure that all the dependencies are using the versions this project uses. If you use the method below the dependencies will be created with the correct versions.

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/eneudys101/techcenter.git
   ```
2. Create Python virtual enviroment 
   ```sh
   python3 -m venv venv
   ```
3. activate virtual enviroment 
   - On Windows:
   ```sh
   venv\Scripts\activate.bat
   ```
   - On Unix, Linux or MacOS:
   ```sh
   source venv/bin/activate
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

Once the Project is installed for development follow these steps to get it running

1. Change directory to the `manage.py` file
   ```sh
   cd techcenter
   ```
2. run migragrate command to write database changes to your development database
   ```sh
   python manage.py migrate
   ```
3. run server
   ```sh
   python manage.py runserver
   ```
   
_For more examples, please refer to the [Documentation](https://example.com)_

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- ROADMAP -->
## Roadmap

- [ ] User Information System
- [ ] I.T. Ticketing System
- [ ] Printers Inventory/Inventory System

See the [open issues](https://github.com/eneudys101/techcenter/issues) for a full list of proposed features (and known issues).

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- CONTRIBUTING -->
## Contributing
For this project [git flow](https://www.atlassian.com/git/tutorials/comparing-workflows/gitflow-workflow) is used as a work flow for contributing.

![git-flow]

To contribute:

1. Pick an issue from [Issues][issues-url] 
   - If the change you want to make doesn't exist open a discussion. Based on the discussion a new issue will be created.
2. Fork the project
3. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
4. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
5. Push to the Branch (`git push origin feature/AmazingFeature`)
6. Open a Pull Request to the `develop` branch
7. Wait for review of changes

<p align="right">(<a href="#top">back to top</a>)</p>


[git-flow]: images/git_flow.svg
[contributors-shield]: https://img.shields.io/github/contributors/eneudys101/techcenter.svg?style=for-the-badge
[contributors-url]: https://github.com/eneudys101/techcenter/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/eneudys101/techcenter.svg?style=for-the-badge
[forks-url]: https://github.com/eneudys101/techcenter/network/members
[stars-shield]: https://img.shields.io/github/stars/eneudys101/techcenter.svg?style=for-the-badge
[stars-url]: https://github.com/eneudys101/techcenter/stargazers
[issues-shield]: https://img.shields.io/github/issues/eneudys101/techcenter.svg?style=for-the-badge
[issues-url]: https://github.com/eneudys101/techcenter/issues
[license-shield]: https://img.shields.io/github/license/eneudys101/techcenter.svg?style=for-the-badge
[license-url]: https://github.com/eneudys101/techcenter/blob/master/LICENSE.txt
