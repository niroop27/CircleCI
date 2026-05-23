# GitHub + CircleCI Demo

This repository demonstrates a simple GitHub-to-CircleCI integration.

## What happens

- You push a change to GitHub.
- CircleCI automatically picks up the commit.
- The pipeline compiles and runs the Java program.
- The program output appears in the CircleCI job logs.

## Files

- `Add.java` - a tiny Java app that prints a demo message and a calculation.
- `.circleci/config.yml` - CircleCI pipeline configuration.

## Expected CircleCI output

When the pipeline runs, you should see output similar to:

```text
CircleCI demo pipeline ran successfully.
10 + 20 = 30
```

## How to use

1. Push this repository to GitHub.
2. Connect the repository to CircleCI.
3. Make any code change and push again.
4. Open the CircleCI job to see the build output in the logs.
