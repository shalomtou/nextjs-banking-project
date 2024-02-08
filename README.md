# Next.js Banking Project

Welcome to our Next.js Banking Project! This project aims to provide a modern and secure web application for managing banking transactions using Next.js and a PostgreSQL database.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Project Structure](#project-structure)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)

## Introduction

The Next.js Banking Project is a full-stack web application built on the Next.js framework, with a PostgreSQL database for storing and managing user transactions. The project focuses on providing a user-friendly interface for banking operations while ensuring the security of user data.

## Features

- User authentication and authorization
- Account overview and transaction history
- Funds transfer between accounts
- Bill payments
- Responsive design for a seamless user experience on various devices

## Getting Started

### Prerequisites

Before you begin, ensure you have the following tools installed:

- [Node.js](https://nodejs.org/)
- [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/)

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/shalomtou/nextjs-banking-project.git
   ```

2. Navigate to the project directory:

   ```bash
   cd nextjs-banking-project
   ```

3. Install dependencies:

   ```bash
   npm install
   # or
   yarn
   ```

4. Configure the PostgreSQL database connection in the `.env` file.

5. Run the development server:

   ```bash
   npm run dev
   # or
   yarn dev
   ```

6. Open your browser and navigate to [http://localhost:3000](http://localhost:3000).

## Project Structure

The project structure follows a standard Next.js application layout:

- `pages/`: Contains the Next.js pages.
- `components/`: Reusable React components.
- `scripts/`: Reusable script to seed database.
- `public/`: Static assets.
- `styles/`: Global and component-specific styles.
- `lib/`: Utility functions, database connections, etc.
<!-- - `api/`: API routes for server-side functionality. -->

## Technologies Used

- [Next.js](https://nextjs.org/)
- [React](https://reactjs.org/)
- [PostgreSQL](https://www.postgresql.org/)

## Contributing

We welcome contributions! If you'd like to contribute to the project, please follow our [contribution guidelines](CONTRIBUTING.md).

## License

This project is licensed under the [MIT License](LICENSE).

Feel free to explore the project, contribute, and make it better! If you have any questions or suggestions, please open an issue. Happy coding!
