Custom Commission Discord Bot

> **Note:** This repository serves as a portfolio showcase. The source code is closed and kept private, as this bot was exclusively developed as a custom commission for a specific community.

## About The Project

Application is a highly customized, multi-functional Discord bot designed to completely automate and manage a large-scale gaming community. Instead of relying on generic public bots, this project was built from the ground up to seamlessly bridge the gap between a live game server and a Discord community, providing specialized moderation, dynamic user engagement, and real-time data synchronization.

This showcase demonstrates my ability to design, architecture, and deploy complex backend systems and Discord applications using modern JavaScript environments.

## Key Capabilities & Features

Although the code is private, the bot actively handles the following complex operations:

* **Live Game Server Synchronization:** Features a built-in Express.js REST API that listens for real-time HTTP POST requests from the game server to update Discord about live player stats, active staff, and current game statisticcs.
* **Advanced Registration System:** A fully interactive, button and modal-driven onboarding process that securely logs and manages user data via local databases.
* **Dynamic Application System:** Allows users to apply for staff or specific roles entirely through Discord UI components. Includes an admin dashboard to review, approve, or reject applications with automated logging.
* **Dedicated Support Tickets:** A structured ticket management system with customized categories, auto-transcripts, and role-based staff access.
* **Automated Private Voice Channels:** Users can generate and manage their own private voice channels dynamically, ensuring clean and organized voice channel categories.
* **Security & Role Guard:** Monitors and protects critical server roles, preventing unauthorized administrative actions and maintaining a secure hierarchy.
* **Moderation & Warning Database:** A custom warning infrastructure with persistent SQLite storage to track user infractions over time.

## Tech Stack

<div align="center">
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="Node.js" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/Discord.js-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord.js" />
  <img src="https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white" alt="Express.js" />
  <img src="https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white" alt="SQLite" />
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL" />
</div>

<br>

* **Core Foundation:** Built natively on **Node.js** using modern **JavaScript**.
* **Bot Framework:** Utilizing **Discord.js (v14)** for robust interactions, slash commands, and modular UI components.
* **API Bridge:** Custom **Express.js** REST API designed to catch live data webhooks directly from the game server.
* **Database Architecture:**
  * **Better-SQLite3:** Employed for lightning-fast, synchronous local storage for settings, ticket states, and moderation logs.
  * **MySQL2:** Integrated for seamless external database querying and synchronization.
* **Network Operations:** Integrated **Gamedig** to actively ping and monitor external game server health and live player counts via raw socket requests.

## Documentation & Legal

Even as a private bot, it operates under strict guidelines regarding user data and server interaction. You can review the official policies below:

* [Terms of Service](TERMS_OF_SERVICE.md)
* [Privacy Policy](PRIVACY_POLICY.md)
