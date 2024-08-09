# Contributing Guidelines

Welcome to the Odestry open source collective! We're thrilled that you're interested in contributing to our projects. This document provides comprehensive guidelines for contributing to any Odestry project. By following these guidelines, you help maintain the quality of our codebase and ensure a positive experience for all contributors.

## Table of Contents

1. [Code of Conduct](#code-of-conduct)
2. [Getting Started](#getting-started)
3. [How to Contribute](#how-to-contribute)
4. [Development Workflow](#development-workflow)
5. [Coding Standards](#coding-standards)
6. [Commit Guidelines](#commit-guidelines)
7. [Pull Request Process](#pull-request-process)
8. [Code Review Process](#code-review-process)
9. [Issue Reporting Guidelines](#issue-reporting-guidelines)
10. [Security Vulnerabilities](#security-vulnerabilities)
11. [Documentation](#documentation)
12. [Testing](#testing)
13. [Versioning](#versioning)
14. [Community](#community)
15. [License](#license)

## Code of Conduct

We are committed to fostering an open and welcoming environment in the Odestry community. All contributors are expected to adhere to our [Code of Conduct](https://github.com/odestry/.github/blob/main/CODE_OF_CONDUCT.md). Please read it thoroughly before participating in our projects.

## Getting Started

1. Ensure you have a [GitHub account](https://github.com/signup/free).
2. Fork the desired Odestry repository to your GitHub account.
3. Clone your fork locally:
   ```
   git clone https://github.com/your-username/repository-name.git
   ```
4. Set up your development environment as described in the project's README.
5. Create a new branch for your work:
   ```
   git checkout -b feature/your-feature-name
   ```

## How to Contribute

1. Check the project's issue tracker for open issues or feature requests.
2. If you're working on a new feature or significant change, open an issue to discuss it first.
3. Make your changes in your feature branch.
4. Test your changes thoroughly.
5. Commit your changes (see [Commit Guidelines](#commit-guidelines)).
6. Push your branch to your fork on GitHub.
7. Submit a pull request to the main repository.

## Development Workflow

1. Always pull the latest changes from the main branch before starting new work.
2. Create a new branch for each separate piece of work.
3. Make logical atomic commits throughout your work.
4. Push your work to your fork at least once a day.
5. When your feature is complete, rebase your branch onto the latest main.
6. Make sure all tests pass and add new tests for your feature if applicable.

## Coding Standards

- Follow the existing code style and conventions used in the project.
- Use meaningful and descriptive names for variables, functions, and classes.
- Write self-documenting code where possible.
- Keep functions small and focused on a single task.
- Use appropriate design patterns and SOLID principles.
- Avoid duplicate code (DRY principle).
- Handle errors and edge cases appropriately.
- Write comments for complex logic or when the code's purpose is not immediately clear.

## Commit Guidelines

- Use the present tense ("Add feature" not "Added feature").
- Use the imperative mood ("Move cursor to..." not "Moves cursor to...").
- Limit the first line to 72 characters or less.
- Reference issues and pull requests liberally after the first line.
- Use semantic commit messages:
  - `feat:` for new features
  - `fix:` for bug fixes
  - `docs:` for documentation changes
  - `style:` for formatting changes
  - `refactor:` for code refactoring
  - `test:` for adding or modifying tests
  - `chore:` for maintenance tasks

Example:
```
feat: Add user authentication system

- Implement JWT token-based authentication
- Create login and registration endpoints
- Add middleware for protected routes

Closes #123
```

## Pull Request Process

1. Ensure your PR adheres to the [Coding Standards](#coding-standards).
2. Update the README.md or relevant documentation with details of changes, if applicable.
3. Add or update tests for your changes.
4. Ensure the test suite passes and the application runs without errors.
5. Fill in the provided pull request template.
6. Include screenshots or animated GIFs in your pull request if it includes UI changes.
7. Make sure your PR is up-to-date with the main branch. If not, rebase your branch.
8. Be responsive to feedback and be prepared to make additional changes if requested.

## Code Review Process

1. At least one core team member must approve the pull request before merging.
2. Reviewers will look for code quality, test coverage, and adherence to project standards.
3. Address all comments and suggestions from reviewers.
4. Once approved, a core team member will merge your PR.

## Issue Reporting Guidelines

1. Use the provided issue template when creating a new issue.
2. Clearly describe the issue, including steps to reproduce for bugs.
3. Include relevant information such as operating system, browser, or package versions.
4. Tag the issue with appropriate labels (e.g., bug, enhancement, documentation).
5. Be responsive to any follow-up questions or requests for additional information.

## Security Vulnerabilities

If you discover a security vulnerability, please DO NOT open an issue. Email weodestry@gmail.com instead. We will work with you to address the vulnerability promptly.

## Documentation

- Keep README files, API documentation, and inline comments up-to-date.
- Document all public APIs, classes, and methods.
- Provide examples and use cases in the documentation where appropriate.
- Use clear and concise language, and proofread your writing.

## Testing

- Write unit tests for all new code.
- Aim for high test coverage (at least 80% for new code).
- Write integration and end-to-end tests for critical paths.
- Ensure all tests pass before submitting a pull request.
- Do not decrease the overall test coverage of the project.

## Versioning

We follow [Semantic Versioning (SemVer)](https://semver.org/) for all our projects. Please ensure that version bumps are appropriate for the changes made.

## Community

- Join our [Discord server](https://odestry.com/community) to connect with other contributors.
- Participate in discussions on GitHub issues and pull requests.
- Help answer questions from other community members.
- Share your Odestry project contributions on social media.

## License

By contributing to Odestry projects, you agree that your contributions will be licensed under the MIT License. All Odestry projects are released under the MIT License, and your contributions will be no exception.

---

Thank you for contributing to Odestry! Your efforts help us build better commerce tools together. If you have any questions or need further clarification on these guidelines, please don't hesitate to reach out to the community on our Discord server or open an issue in the repository.

Happy coding, and let's make commerce better, together!
