# GitHubCI_CD

This repository demonstrates the setup of Continuous Integration (CI) and Continuous Deployment (CD) using GitHub Actions.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Setup](#setup)
- [Usage](#usage)
- [Workflows](#workflows)
- [Contributing](#contributing)
- [License](#license)

## Introduction

This project showcases how to use GitHub Actions to automate the CI/CD pipeline for a project. It includes workflows for testing, building, and deploying the project.

## Features

- **Automated Testing**: Runs tests on every push to ensure code quality.
- **Automated Deployment**: Deploys the application automatically after successful tests.
- **Branch Management**: Automatically merges changes from `master` to `main`.

## Setup

To set up the project locally, follow these steps:

1. **Clone the repository**:
    ```sh
    git clone https://github.com/tdat3023/GitHubCI_CD.git
    cd GitHubCI_CD
    ```

2. **Install dependencies** (if applicable):
    ```sh
    # For Node.js projects
    npm install
    ```

3. **Configure GitHub Secrets**:
    - Go to your repository on GitHub.
    - Navigate to `Settings` > `Secrets and variables` > `Actions`.
    - Add the required secrets such as `GITHUB_TOKEN` for pushing changes.

## Usage

### Running Tests

To run tests locally before pushing changes:

```sh
# For Node.js projects
npm test
