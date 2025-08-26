# CCV - Conventional Commits Versioner

![GitHub Actions](https://img.shields.io/badge/GitHub-Actions-brightgreen.svg) ![Continuous Delivery](https://img.shields.io/badge/Continuous%20Delivery-blue.svg) ![Git](https://img.shields.io/badge/Git-black.svg) ![GitHub](https://img.shields.io/badge/GitHub-lightgrey.svg)

Welcome to the **CCV** repository! This project focuses on streamlining the versioning process in your development workflow using Conventional Commits. By adopting a standardized commit message format, you can automate versioning and changelog generation, making your release process smoother and more efficient.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Releases](#releases)
- [Contributing](#contributing)
- [License](#license)

## Introduction

In today's fast-paced development environment, maintaining a clear and consistent versioning strategy is crucial. **CCV** leverages the Conventional Commits specification to enhance your versioning process. This repository integrates seamlessly with GitHub Actions, allowing for automated workflows that reduce manual errors and save time.

### What are Conventional Commits?

Conventional Commits is a specification for writing standardized commit messages. This approach helps in automatically determining the type of changes made in your project. It categorizes commits into types like `feat`, `fix`, and `chore`, which makes it easier to understand the history of your project.

## Features

- **Automated Versioning**: Automatically increment your version number based on commit types.
- **Changelog Generation**: Create changelogs based on commit messages.
- **GitHub Actions Integration**: Use GitHub Actions for continuous delivery.
- **Customizable**: Easily adapt the configuration to suit your project's needs.

## Installation

To get started with **CCV**, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/Kaks734/ccv.git
   ```

2. Navigate to the project directory:
   ```bash
   cd ccv
   ```

3. Install the necessary dependencies:
   ```bash
   npm install
   ```

## Usage

Once you have installed **CCV**, you can start using it in your project. 

1. **Set up your commit message format**. You can use the following types:
   - `feat`: A new feature
   - `fix`: A bug fix
   - `chore`: Changes to the build process or auxiliary tools

2. **Make your commits** using the conventional format:
   ```bash
   git commit -m "feat: add new user authentication"
   ```

3. **Run the versioning command** to update your version based on the commits:
   ```bash
   npm run version
   ```

4. **Generate a changelog** with the following command:
   ```bash
   npm run changelog
   ```

## Releases

For the latest releases and updates, visit our [Releases](https://github.com/Kaks734/ccv/releases) section. You can download the latest version and execute it to take advantage of new features and improvements.

If you are looking for a specific release, please check the [Releases](https://github.com/Kaks734/ccv/releases) section for detailed information.

## Contributing

We welcome contributions to enhance the **CCV** project. If you want to contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature:
   ```bash
   git checkout -b feature/my-feature
   ```
3. Make your changes and commit them:
   ```bash
   git commit -m "Add my feature"
   ```
4. Push to your forked repository:
   ```bash
   git push origin feature/my-feature
   ```
5. Create a pull request.

Please ensure that your code adheres to the project's coding standards and includes appropriate tests.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

Thank you for checking out **CCV**! We hope this tool makes your versioning process easier and more efficient. Happy coding!