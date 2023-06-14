# @lacrei/eslint-config

Default Lacrei ESLint config

## Installation

You'll first need to install [ESLint](https://eslint.org/) and [Prettier](https://prettier.io/):

```sh
npm i eslint prettier --save-dev
```

Next, install `@lacrei/eslint-config`:

```sh
npm install @lacrei/eslint-config --save-dev
```

## Usage

Add `@lacrei/eslint-config` to the extends section of your `.eslintrc` configuration file:

```json
{
    "extends": "@lacrei/eslint-config"
}
```

## Contributing

We welcome contributions to project! To get started, please follow these steps:

1. Clone this repository to your machine.
2. Create a new branch: `git checkout -b your-branch-name`
3. Make your changes, following the project's coding style and conventions.
4. Use [conventional commits](https://www.conventionalcommits.org/en/v1.0.0/) convention to ensure a successful automatic release. You can look at the [`.releaserc`](./.releaserc) file to know which commit types generate specific versions.
5. Commit your changes and push them to your branch.
6. Open a pull request (PR) against the `main` branch, describing your changes and why they are valuable. You can also open a PR for the `beta` branch if you want to test your changes.
7. Wait for review and approval from project maintainers before merging your changes.

> Please focus on line 4. You MUST commit using conventional commits convention.
> While `main` branch depends on code review, `beta` does not have this restriction so you can test freely.
