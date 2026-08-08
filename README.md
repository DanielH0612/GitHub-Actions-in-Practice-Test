# GitHub Actions in Practice Test

A simple JavaScript project created to practise version control, code quality tools, testing, Git hooks, and GitHub Actions.

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

Prettier is used to ensure consistent code formatting.

Run:

```bash
npm run format
```

## ESLint

ESLint is used to check the JavaScript code for problems and maintain consistent code quality.

Run:

```bash
npm run lint
```

## Testing

Jest is used to test the JavaScript code.

Run:

```bash
npm test
```

The project contains a simple `add` function in `math.js` and a corresponding test in `math.test.js`.

## Husky and lint-staged

Husky is used to create a Git pre-commit hook.

Before a commit is completed, Husky runs lint-staged.

lint-staged runs Prettier and ESLint on staged JavaScript and JSON files.

This helps ensure that code is formatted and checked before it is committed to the repository.

## GitHub Actions

A GitHub Actions workflow is included in the `.github/workflows` directory.

The workflow automatically runs project checks when changes are pushed to the repository.

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

This project was created as part of a lesson about version control, clean code, testing, GitHub, and workplace development best practices.

The repository can also be used as a template for future JavaScript projects.
