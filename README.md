# ☕️ Java Toolbox

<img width="300" alt="toolbox" src="https://github.com/user-attachments/assets/d6bb0f76-08cd-4bfb-8059-6739f8bc7048">

> This repository contains utilities for the DHBW Karlsruhe programming exam of the first two semesters.

[**Visit documentation**](https://dhbw-inf.github.io/Toolbox/)

## Features

- [x] *`FileUtils`*: Utilities for reading and writing files.
- [x] *`ArrayUtils`*: Utilities for working with arrays.
- [x] *`ConsoleUtils`*: Utilities for printing and reading to and from the console.
- [x] *`RandomUtils`*: Utilities for getting random numbers and objects.

## How to use the utilities

Every release contains a zip file with the source code. To use the utils just copy the source code into your exam project.

All utils are dependency free.

## How to contribute

Open a new Issue with a feature you want to implement. Fork the project, make your changes and open a pull request linking to your issue. Make sure your feature does not need any external dependencies and is covered by unit tests. Finally add the topic of your feature(s) to the [list of features](https://github.com/DHBW-Inf/Toolbox#features) in this README and mark it as done as soon as this topic is completely covered.
Open a new Issue with a feature you want to implement. Fork the project, make your changes and open a pull request linking to your issue. Make sure your feature does not need any external dependencies and is covered by unit tests. Finally add the topic of your feature(s) to the [list of features](https://github.com/DHBW-Inf/Toolbox#features) in this README and mark it as done as soon as this topic is completely covered.

## Automatic versioning

This repository is using [thenativeweb/get-next-version](https://github.com/thenativeweb/get-next-version) to automatically release new versions when commiting on `main`. Therefore it is important to mark commits with a corresponding prefix:

- `chore:` – used for maintenance, does not result in a new version
- `fix:` – used for bug fixes, results in a new patch version (e.g. from `1.2.3` to `1.2.4`)
- `feat:` – used for introducing new features, results in a new minor version (e.g. from `1.2.3` to `1.3.0`)
- `feat!:` – used for breaking changes, results in a new major version (e.g. from `1.2.3` to `2.0.0`)
