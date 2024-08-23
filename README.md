# Dialosoft Forum Software

<p align="center">
    <a href="https://github.com/Dialosoft/frontend"><img src="https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript"></a>
    <a href="https://github.com/Dialosoft/backend"><img src="https://img.shields.io/badge/Java-21-ED8B00?style=flat-square&logo=openjdk&logoColor=white" alt="Java 21"></a>
    <a href="https://github.com/Dialosoft/backend"><img src="https://img.shields.io/badge/Golang-1.23.0-00ADD8?style=flat-square&logo=go&logoColor=white" alt="Go 1.23.0"></a>
    <a href="#"><img src="https://img.shields.io/badge/build-passing-brightgreen.svg?style=flat-square" alt="Build Status"></a>
    <a href="https://gradle.org/"><img src="https://img.shields.io/badge/Gradle-8.7-02303A?style=flat-square&logo=gradle&logoColor=white" alt="Gradle 8.7"></a>
    <a href="https://www.docker.com/"><img src="https://img.shields.io/badge/Docker-25.0.2-blue.svg?style=flat-square" alt="Docker"></a>
    <a href="https://www.gnu.org/licenses/gpl-3.0"><img src="https://img.shields.io/badge/License-GPLv3-blue.svg?style=flat-square" alt="License: GNU GPLv3"></a>
</p>

Welcome to the main repository of the Dialosoft Forum Software. Here you can deploy and access everything related to the app.

Let's get started!

## Requirements:

- Docker must be installed on the machine running the software
- At least 2GB of RAM
- At least 1GB of disk space
- At least 1 available CPU core

## Deployment

Follow the appropriate commands to get the latest recommended version of this software.

```bash
git clone --recurse-submodules https://github.com/Dialosoft/app
```
Once you've cloned the repository, make sure to edit the example.env file. Add the necessary data here. We recommend leaving it unchanged if you're unsure, but it's very important to rename the file to .env, removing example or any other name!

After ensuring Docker is installed, make sure you also have Docker Compose, and then simply run the following command:

For Windows:
```powershell
./run.ps1
```

For Linux:
```sh
./run.sh
```

We appreciate you using Dialosoft, please leave a star on the repository!
