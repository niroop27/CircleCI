# DevOps ABA CI Demo

[![CircleCI](https://circleci.com/gh/niroop27/DevOps-ABA.svg?style=shield)](https://app.circleci.com/pipelines/github/niroop27/DevOps-ABA)
[![Travis CI](https://travis-ci.com/niroop27/DevOps-ABA.svg?branch=main)](https://app.travis-ci.com/github/niroop27/DevOps-ABA)

This repository contains a minimal Java program and CI configuration for GitHub, CircleCI, and Travis CI.

## Run locally

```bash
javac add.java
java add
```

## GitHub and CI setup

1. Create a GitHub repository for this project.
	- Use the name `DevOps-ABA` under the `niroop27` account.
2. Connect your local repo to GitHub:

```powershell
git remote add origin https://github.com/niroop27/DevOps-ABA.git
git branch -M main
git push -u origin main
```

3. Connect the repository to CircleCI and enable the project.
	- Sign in to CircleCI with GitHub and select the repository.
4. Connect the repository to Travis CI and enable builds for the repo.
	- Sign in to Travis CI with GitHub and turn on the repository.
5. Push a change and confirm both pipelines compile and run `add.java`.

## Files

- add.java: simple Java program that prints the sum of two integers.
- .circleci/config.yml: CircleCI pipeline that compiles and runs the program.
- .travis.yml: Travis CI pipeline that compiles and runs the program.