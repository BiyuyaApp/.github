![2](https://github.com/BiyuyaApp/.github/assets/43304840/7027ce1c-904d-41d5-91b4-d87d6c86e30d)
# Biyuya Organization
Welcome to the Biyuya organization's repository! This document serves as a guide to help you understand our projects, contribution guidelines, and more.

## Table of Contents

- [About Us](#about-us)
- [Projects](#projects)
- [Contribution Guidelines](#contribution-guidelines)
- [Branch Naming Convention](#branch-naming-convention)
- [License](#license)
- [Contact](#contact)

## About Us

Biyuya is an organization dedicated to developing high-quality software solutions. Our projects range from web and mobile applications to libraries and tools that aim to improve developers' productivity.

## Projects


## Contribution Guidelines

We welcome contributions from the community. Please follow these steps to contribute:

1. **Fork the repository** you want to contribute to.
2. **Clone your fork** to your local machine.
3. **Create a new branch** using the branch naming convention (see below).
4. **Make your changes** and commit them with clear and descriptive messages.
5. **Push your changes** to your fork.
6. **Create a pull request** to the main repository.

## Commits

1. Create your feature branch

   ```bash
   git checkout -b [EXA-123]-my-new-feature
   ```

2. Add files to commit

   ```bash
   git add [path]
   ```

3. Commit your changes

   ```bash
   git commit -m "feat[EXA-123]: description"
   ```

4. Push to the branch

   ```bash
   git push
   ```

#### Examples using [conventional commits](https://www.conventionalcommits.org/en/v1.0.0/)

| Type     | Commit                                   | Description                                                                         |
| -------- | ---------------------------------------- | ----------------------------------------------------------------------------------- |
| feat     | feat: add new feature example            | Introduces a new feature/component/functionality into the project                   |
| fix      | fix: fix foo to enable bar               | Fixes an error in your code base                                                    |
| chore    | chore: add file to gitignore             | Routine tasks not specific to a feature                                             |
| build    | build: change scripts to builds          | Changes affecting the project's compilation                                         |
| ci       | ci: add new step to workflow ci          | Changes affecting configuration files and scripts related to continuous integration |
| style    | style: format functionality code         | Changes in readability or code formatting that do not affect functionality          |
| refactor | refactor: change component example       | Code change that neither fixes errors nor adds functionality, but improves the code |
| perf     | perf: using new pattern to optimize code | Used for performance improvements                                                   |
| revert   | revert: revert last version              | Reverts PR changes or if the commit reverts a previous commit                       |
| docs     | docs: update readme                      | When only documentation is modified                                                 |
| merge    | merge: update with main                  | Update active branch with main or another necessary branch                          |
| test     | test: improve test coverage              | Changes affecting tests and update snapshots                                        |

