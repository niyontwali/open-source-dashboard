# Open Source Dashboard

## Overview

This open-source dashboard project, crafted with React/Vite and styled using Tailwind CSS, is specifically designed to serve as a valuable reference for developers grappling with dashboard challenges. Whether you're seeking a reliable point of reference or aiming to integrate it directly into your projects and gigs, this dashboard offers flexibility and customization to meet your unique needs.

## Table of Contents

- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Development](#development)
  - [Running Locally](#running-locally)
  - [Environment Variables](#environment-variables)
- [Contributing](#contributing)
  - [Branching Strategy](#branching-strategy)
  - [Pull Requests](#pull-requests)
- [Continuous Integration/Continuous Deployment (CI/CD)](#continuous-integrationcontinuous-deployment-cicd)
- [Versioning](#versioning)
- [License](#license)

## Getting Started

### Prerequisites

### Prerequisites

Before diving into the setup, ensure that your machine is equipped with the following:

- [Node.js](https://nodejs.org/): Verify that you have Node.js installed, with a minimum version of 20.10.0
- [npm](https://www.npmjs.com/) or [Yarn](https://yarnpkg.com/): If you've successfully installed Node.js, npm is included; otherwise, you can opt for Yarn as your package manager.

### Installation

1. Clone the repository:

```bash
git clone https://github.com/niyontwali/open-source-dashboard.git
```

or

```bash
git clone git@github.com:niyontwali/open-source-dashboard.git
```

2. Install dependencies:

```bash
cd open-source-dashboard
npm install # or yarn install
```

## Development

### Running Locally

To run the dashboard locally, use the following command:

```bash
npm run dev # or yarn dev
```

This will initiate the development server, allowing you to access the dashboard at [http://localhost:5173](http://localhost:5173). If your port was configured differently, be sure to adjust the URL accordingly to match your specified port.

### Environment Variables

Before proceeding, set up essential environment variables by creating a `.env` file in the project's root directory. Utilize the provided template in the `.env.example` file as a reference.

Additionally, to simplify this process, you can run the following script in your terminal to automatically copy the content from `.env.example` to `.env`:

```bash
cp .env.example .env
```

This script ensures that your `.env` file is initialized with the necessary variables, streamlining the setup for you.

## Contributing

### Branching Strategy

- `main`: The main branch, used for production-ready releases.
- `release.version`: Release branches for specific versions (e.g., `release.1.0.0`).
- `develop`: The development branch where all contributors should clone the repository.

### Pull Requests

1. Fork or clone the repository.
2. Create a new branch from `develop`.
3. Make your changes.
4. Create a pull request targeting the `develop` branch.

## Continuous Integration/Continuous Deployment (CI/CD)

This project employs GitHub Actions for automated testing and deployment. For more detailed information, refer to the CI/CD configuration files.

## Versioning

This project follows [Semantic Versioning](https://semver.org/) for version numbering. Release branches (`release.version`) indicate specific versions.

## License

This project is licensed under the [LICENSE] - see the [LICENSE.md](LICENSE.md) file for details.
