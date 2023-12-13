# GitHub Actions Template

This repository contains GitHub Actions configurations for CI/CD automation in personal projects. It is designed to perform the following tasks:

1. Run the solution to check for any issues.
2. Execute tests and verify if all pass.
3. Open a Pull Request from the feature branch to develop when tests are successful.
4. Open a Pull Request from develop to main when the feature PR is completed.

## How to Use

1. Copy the contents of the `.github/` file to the `.github/` directory in your project.

2. Customize the environment variables in those file according to the specific settings of your project.

3. Make sure to have the `feature`, `develop`, and `main` branches created in your repository.

4. Trigger the workflow when making changes and commits. The configured actions will be triggered automatically.
