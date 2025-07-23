
<a id="readme-top"></a>

[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]


<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/MRBYT/QueueByt">
    <img src="/images/logo.png" alt="Logo" width="80" height="80">
  </a>

<h3 align="center">QueueByt</h3>

  <p align="center">
    Because waiting in scrim chat sucks.
    <br />
    <a href="https://github.com/MRBYT/QueueByt/README.MD"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://discord.com/oauth2/authorize?client_id=1396962875523858452&scope=applications.commands%20bot&permissions=536737213566">View Demo</a>
    &middot;
    <a href="https://github.com/MRBYT/QueueByt/issues/new?labels=bug&template=bug-report---.md">Report Bug</a>
    &middot;
    <a href="https://github.com/MRBYT/QueueByt/issues/new?labels=enhancement&template=feature-request---.md">Request Feature</a>
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
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

[![QueueByt Screen Shot][QueueByt-screenshot]](https://example.com)

QueueByt aims to empower competitive gaming communities by automating tedious coordination tasks, ensuring smooth event execution, and enhancing the overall user experience. This tool fosters organized, engaging, and scalable esports environments, encouraging active participation and growth.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



### Built With

This project leverages a robust and modern tech stack to deliver high performance, scalability, and seamless user experience. The core technologies include:

* [![Python][Python]][Python-url]
* [![React][React]][React-url]
* [![TypeScript][TypeScript]][TypeScript-url]
* [![JavaScript ][JavaScript]][JavaScript-url]
* [![Go][Go]][Go-url]
* [![discord.py][discord.py]][discord.py-url]
* [![PostgreSQL][PostgreSQL]][PostgreSQL-url]
* [![Celery][Celery]][Celery-url]



<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started

QueueByt is a Discord bot specifically engineered to streamline the process of scrim registration and tournament booking within competitive gaming communities. Designed for automation and operational efficiency, QueueByt eliminates the need for manual coordination by providing a centralized, intuitive interface for scheduling matches, managing team registrations, and organizing tournament brackets.

QueueByt functions as an infrastructure tool that integrates seamlessly with Discord servers, offering customizable queue systems, automated match pairing, and real-time registration tracking. The bot is particularly suited for esports organizations, gaming leagues, and community managers seeking to reduce administrative overhead and enhance the participant experience.

Key features typically include:

* Automated Scrim Scheduling: Enables teams to join or create scrim queues based on game titles, ranks, or availability.
* Tournament Booking Tools: Facilitates event registration, match generation, and bracket progression without requiring external platforms.
* Role & Permission Integration: Ensures that user access and actions are governed by server roles, preserving order and security.
* Real-Time Notifications: Provides timely alerts for upcoming matches, registration deadlines, and match confirmations.
* Admin Dashboard or Commands: Offers moderators and organizers granular control over queues, time slots, and participant data.

Overall, QueueByt serves as a scalable solution for competitive ecosystems aiming to foster organized, fair, and efficient gameplay environments within Discord.

### Prerequisites

1. Discord Account with Appropriate Permissions
    * You must have the “Manage Server” permission in the Discord server where you want to add QueueByt. This permission is necessary to authorize and configure the bot properly.
2. Essential Bot Permissions
    * When adding QueueByt via the invite link, ensure you grant the following permissions:
   ```sh
              Manage Roles – to assign and manage user roles related to queues and tournaments.
              Send Messages – for the bot to communicate in designated channels.
              Use Slash Commands – to allow interaction through slash commands like /setup and /help.
              Other permissions included in the invite will be requested automatically. Avoid removing any essential permissions after installation.
   ```
3. Server Environment
    * Avoid adding QueueByt to unmoderated servers or NSFW (Not Safe For Work) channels, as this may cause functionality restrictions or unexpected behavior.
    * The server should ideally have a clear structure for roles and channels to facilitate queue and tournament management.
4. Discord Client
    * A Discord client capable of using slash commands (Discord desktop app, browser version, or mobile app with updated features).

### Installation

Follow these steps to correctly install QueueByt in your Discord server:

1. Prerequisite Checks
    * Ensure you have the “Manage Server” permission in the Discord server where you want to install QueueByt.
    * Confirm you can configure roles and channels as needed for bot setup.

2. Add QueueByt to Your Server [https://example.com](https://example.com)
2. Clone the repo
   ```sh
   git clone https://github.com/MRBYT/QueueByt.git
   ```

4. Enter your API in `config.js`
   ```js
   const API_KEY = 'ENTER YOUR API';
   ```
5. Change git remote url to avoid accidental pushes to base project
   ```sh
   git remote set-url origin MRBYT/QueueByt
   git remote -v # confirm the changes
   ```

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- USAGE EXAMPLES -->
## Usage

Use this space to show useful examples of how a project can be used. Additional screenshots, code examples and demos work well in this space. You may also link to more resources.

_For more examples, please refer to the [Documentation](https://example.com)_

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ROADMAP -->
## Roadmap

- [ ] Feature 1
- [ ] Feature 2
- [ ] Feature 3
    - [ ] Nested Feature

See the [open issues](https://github.com/MRBYT/QueueByt/issues) for a full list of proposed features (and known issues).

<p align="right">(<a href="#readme-top">back to top</a>)</p>



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

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Top contributors:

<a href="https://github.com/MRBYT/QueueByt/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=MRBYT/QueueByt" alt="contrib.rocks image" />
</a>



<!-- LICENSE -->
## License

Distributed under the CC0 1.0 Universal. See `LICENSE` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Your Name - [@MRBYT3](https://twitter.com/MRBYT3) - pratapbhanu389@gmail.com

Project Link: [https://github.com/MRBYT/QueueByt](https://github.com/MRBYT/QueueByt)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

* []()
* []()
* []()

<p align="right">(<a href="#readme-top">back to top</a>)</p>



[contributors-shield]: https://img.shields.io/github/contributors/MRBYT/QueueByt.svg?style=for-the-badge
[contributors-url]: https://github.com/MRBYT/QueueByt/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/MRBYT/QueueByt.svg?style=for-the-badge
[forks-url]: https://github.com/MRBYT/QueueByt/network/members
[stars-shield]: https://img.shields.io/github/stars/MRBYT/QueueByt.svg?style=for-the-badge
[stars-url]: https://github.com/MRBYT/QueueByt/stargazers
[issues-shield]: https://img.shields.io/github/issues/MRBYT/QueueByt.svg?style=for-the-badge
[issues-url]: https://github.com/MRBYT/QueueByt/issues
[license-shield]: https://img.shields.io/github/license/MRBYT/QueueByt.svg?style=for-the-badge
[license-url]: https://github.com/MRBYT/QueueByt/blob/master/LICENSE
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/mrbyt3
[QueueByt-screenshot]: /images/logo.png
[Python]: https://img.shields.io/badge/Python-000000?style=for-the-badge&logo=python&logoColor=white
[Python-url]: https://www.python.org/
[React]: https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB
[React-url]: https://reactjs.org/
[TypeScript]: https://img.shields.io/badge/typescript-35495E?style=for-the-badge&logo=typescript&logoColor=4FC08D
[TypeScript-url]: https://www.typescriptlang.org/
[JavaScript]: https://img.shields.io/badge/JavaScript-DD0031?style=for-the-badge&logo=javascript&logoColor=white
[JavaScript-url]: https://www.javascript.com/
[Go]: https://img.shields.io/badge/Go-4A4A55?style=for-the-badge&logo=go&logoColor=FF3E00
[Go-url]: https://go.dev/
[discord.py]: https://img.shields.io/badge/Discord.py-FF2D20?style=for-the-badge&logo=discord&logoColor=white
[discord.py-url]: https://discordpy.readthedocs.io/en/stable/
[PostgreSQL]: https://img.shields.io/badge/PostgreSQL-563D7C?style=for-the-badge&logo=postgresql&logoColor=white
[PostgreSQL-url]: https://www.postgresql.org/
[Celery]: https://img.shields.io/badge/Celery-0769AD?style=for-the-badge&logo=celery&logoColor=white
[Celery-url]: https://docs.celeryq.dev/en/stable/#
