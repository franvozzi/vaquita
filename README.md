<div align="center">
  <img src="/logo.png" alt="Vaquita Logo" width="400"/>
</div>

# Vaquita - Cryptocurrency-Based Crowdfunding Platform

Vaquita is an innovative crowdfunding platform that uses blockchain technology to facilitate secure and transparent fundraising. Inspired by the Argentine lunfardo phrase "Hagamos una vaquita" (let's chip in), the project aims to combine the ease of crowdfunding with the flexibility and security of cryptocurrencies.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Architecture](#architecture)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contribution)
- [License](#license)
- [Contact](#contact)

## Overview

Vaquita aims to provide an easy-to-use platform for projects seeking funding through cryptocurrency contributions. It offers an intuitive interface for both project creators and donors, backed by smart contracts to ensure transparency and security of transactions.

## Features

- **Project Creation:** Users can create crowdfunding campaigns with detailed descriptions, goals, and deadlines.
- **Cryptocurrency Contributions:** Support for various cryptocurrencies to contribute to projects.
- **Transparency and Security:** Use of smart contracts to manage contributions and ensure compliance with terms.
- **Intuitive Interface:** User-friendly frontend design with React for a smooth user experience.
- **User Management:** Secure authentication and authorization using JWT.
- **Project Visualization:** Listing and viewing of active, ongoing, and completed projects.

## Technologies used

- ![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=white)
- ![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
- ![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
- ![Express](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)
- ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
- ![Solidity](https://img.shields.io/badge/Solidity-363636?style=for-the-badge&logo=solidity&logoColor=white)
- ![Ethereum](https://img.shields.io/badge/Ethereum-3C3C3D?style=for-the-badge&logo=ethereum&logoColor=white)
- ![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=json-web-tokens&logoColor=white)
- ![Heroku](https://img.shields.io/badge/Heroku-430098?style=for-the-badge&logo=heroku&logoColor=white)
- ![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
- ![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)

## Architecture

The project uses a microservices architecture for the backend, with a PostgreSQL database for data storage. Smart contracts on the Ethereum blockchain manage contributions and transparency. The frontend application is built with React and communicates with the backend through a REST API.

## Installation

### Prerequisites

- [Node.js](https://nodejs.org/) v16 or higher
- [PostgreSQL](https://www.postgresql.org/) v12 or higher
- [Truffle](https://www.trufflesuite.com/truffle) for smart contracts
- [Ganache](https://www.trufflesuite.com/ganache) for blockchain testing
  
### Cloning the Repository

```bash
git clone https://github.com/franvozzi/vaquita.git
cd vaquita
```
## Installing Dependencies
### Frontend Dependencies
```
cd frontend
npm install
```
### Backend Dependencies
```bash
cd ../backend
npm install
```

### Environment Setup
Copy the example configuration file and adjust the variables:
```bash
cp backend/.env.example backend/.env
cp frontend/.env.example frontend/.env
```
Edit the .env files to include your database configuration and API keys.

### Starting the Frontend
```bash
cd frontend
npm start
```

### Starting the Backend
```bash
cd ../backend
npm start
```

## Usage
- Create an Account: Register on the platform to create and manage projects.
- Create a Project: Fill in the project details and publish to receive contributions.
- Contribute to a Project: Browse available projects and contribute with cryptocurrencies.
- Monitor Contributions: Check the status of contributions and project progress.

## Contribution
Contributions are welcome. To contribute to the project, please follow these steps:

  1. Fork the repository.
  2. Create a branch for your feature or bugfix (git checkout -b feature/new-feature).
  3. Make your changes and commit (git commit -am 'Add new feature').
  4. Push the branch to the remote repository (git push origin feature/new-feature).
  5. Create a pull request on GitHub.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Contact
Francisco Vozzi - franciscovozzi@outlook.com
GitHub: franvozzi
Thank you for your interest in Vaquita! We hope you find this cryptocurrency-based crowdfunding platform useful and exciting.

This README.md provides an overview of the project, details on installation and usage, and how to contribute. Be sure to customize any specific details as the project develops.
