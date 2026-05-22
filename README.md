# DevOps ABA CI Demo

This repository contains a minimal Java program and CI configuration for GitHub, CircleCI, and Travis CI.

## Run locally

```bash
javac add.java
java add
```

## GitHub and CI setup

1. Create a GitHub repository for this project.
2. Connect your local repo to GitHub:

```powershell
git remote add origin https://github.com/niroop27/DevOps-ABA.git
git branch -M main
git push -u origin main
```

3. Connect the repository to CircleCI and enable the project.
4. Connect the repository to Travis CI and enable builds for the repo.
5. Push a change and confirm both pipelines compile and run `add.java`.

## Files

- add.java: simple Java program that prints the sum of two integers.
- .circleci/config.yml: CircleCI pipeline that compiles and runs the program.
- .travis.yml: Travis CI pipeline that compiles and runs the program.