# Nest Docker CI Tests

This repository contains a development environment base for the NestJS framework using Docker. It also includes continuous integration (CI) of automated tests.

The goal of this project is to provide an initial out-of-the-box setup, allowing you to quickly start developing with NestJS in a Dockerized environment and run integration tests in an automated fashion.

# Requirements

Before you start using this repository, make sure you have the following requirements installed on your local machine:

- Git
- Node.js
- Docker
- Docker compose

# Settings

Follow the steps below to set up and run the development environment:

1 - Clone this repository on your local machine:

```bash
git clone https://github.com/Miguel-Leite/nest-docker-ci-tests.git
```

2 - Navigate to the project's root directory::

```bash
cd nest-docker-ci-tests.git
```

3 - Run the ``` docker run -p80:3000 nest-docker-ci-tests ``` command to build and start Docker containers:

```bash
docker run -p80:3000 nest-docker
```

Access the application in the browser at http://localhost to verify that it is working correctly.

# Contribution

If you want to contribute to this project, please follow these steps:

1 - Fork this repository.

2 - Create a new branch with your contribution:

```bash
git checkout -b my-contribution
```

3 - Make the desired changes and commit them.

4 - Push the changes to your repository fork:

```bash
git push origin my-contribution
```

5 - Open a Pull Request on this original repository.

6 - Wait for your contribution to be reviewed and discussed.

# License

This project is licensed under the MIT license. See the LICENSE file for more information.