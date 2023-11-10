# social-media-client

This is a project to demonstrate workflows and automated testing for a CSS framework application.

## Features

- Front-end login/logout functionality.
- CRUD operations for a specific object type.
- Profile page management.

## Installation

To get started with this project, clone the repository and install the dependencies.

```bash
git clone https://github.com/Queenen/social-media-client.git
cd social-media-client
npm install
```

## Usage

To run the project locally, use:

```bash
npm start
```

To build the project, use:

```bash
npm run build
```

## Configuration

Code Quality Tools

- ESLint: For linting JavaScript files.
- Prettier: For formatting code.

Commit Hooks

- Husky: To apply Prettier and ESLint before commits.

## Running Linters

To run ESLint:

```bash
npm run lint
```

To run Prettier:

```bash
npm run format
```

## Workflow and Status Badges

[![Build and Deploy to GitHub Pages](https://github.com/Queenen/social-media-client/actions/workflows/deploy.yml/badge.svg)](https://github.com/Queenen/social-media-client/actions/workflows/deploy.yml)

[![Unit Tests](https://github.com/Queenen/social-media-client/actions/workflows/unit-test.yml/badge.svg)](https://github.com/Queenen/social-media-client/actions/workflows/unit-test.yml)

## Testing

Unit Testing

To run unit tests:

```bash
npm test
```

End-to-End Testing

To run end-to-end tests:

```bash
npm run e2e
```

## Deployment

The project is configured to automatically deploy to GitHub Pages upon merges to the main branch.

## Contributing

Contributions are welcome. Please fork the repository and create a pull request with your changes.

## Bugs and Issues

Please report bugs and issues in the project's Issues tab on GitHub.

## License

Distributed under the ISC License. See LICENSE for more information.
