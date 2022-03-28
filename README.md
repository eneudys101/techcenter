<div id="top"></div>

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
All the files to get the project up and running have been provided in the repo. You can feel free to build the database and the python enviroment with any method but make sure that all the dependencies are using the versions this project uses. If you use the method below the dependencies will be created with the correct versions.

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/eneudys101/techcenter-2.0.git
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

See the [open issues](https://github.com/eneudys101/techcenter-2.0/issues) for a full list of proposed features (and known issues).

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- CONTRIBUTING -->
## Contributing
For this project [git flow](https://www.atlassian.com/git/tutorials/comparing-workflows/gitflow-workflow) is used as a work flow for contributing.
![git-flow]

To contribute:

1. Pick an issue from [Issues][issues-url] and assign to yourself. 
   - If the change you want to make doesn't exist open a discussion. Based on the discussion a new issue will be created.
2. Move issue to `in progress` in the project it resides
2. Create a new branch from the `develop` branch
3. Commit changes
4. Push to the branch
5. Open a Pull Request to the `develop` branch
6. Wait for review of changes
7. Move issue in the project to `Done`

<p align="right">(<a href="#top">back to top</a>)</p>


[git-flow]: images/git_flow.svg
[issues-url]: https://github.com/eneudys101/techcenter-2.0/issues
