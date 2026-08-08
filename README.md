# GitHub Actions in Practice Test

This project was created to practise version control, clean code, testing, Git hooks, and GitHub Actions.

## Tools Used

* Git
* GitHub
* Node.js
* npm
* Prettier
* ESLint
* Husky
* lint-staged
* Jest
* GitHub Actions

## Installation

Clone the repository:

```bash
git clone <repository-url>
```

Navigate into the project:

```bash
cd GitHub-Actions-in-Practice-Test
```

Install the dependencies:

```bash
npm install
```

## Prettier

Prettier is used to keep the code formatting consistent.

Run Prettier with:

```bash
npm run format
```

## ESLint

ESLint is used to check the JavaScript code for errors and code-quality issues.

Run ESLint with:

```bash
npm run lint
```

## Testing

Jest is used for testing the JavaScript code.

Run the tests with:

```bash
npm test
```

The project contains a simple `add` function in `math.js` and a corresponding test in `math.test.js`.

## Husky and lint-staged

Husky is used to create a Git pre-commit hook.

When a commit is made, Husky runs lint-staged automatically.

lint-staged runs Prettier and ESLint on staged JavaScript and JSON files before the commit is completed.

This helps ensure that committed code is properly formatted and passes the linting checks.

## GitHub Actions

The project contains a GitHub Actions workflow inside:

```text
.github/workflows/main.yml
```

The workflow automatically runs checks when changes are pushed to the repository.

## Project Structure

```text
.github/
└── workflows/
    └── main.yml

.husky/
└── pre-commit

math.js
math.test.js
package.json
README.md
```

## Purpose

The purpose of this project is to practise setting up a JavaScript project using version control and common development tools.

The repository can also be used as a template for future JavaScript projects.
