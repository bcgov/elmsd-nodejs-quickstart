# ELMSD NodeJS Quickstart

A [cookiecutter](https://github.com/cookiecutter/cookiecutter) template to bootstrap a NodeJS monorepo with support for:
* Changelogs and versioning use [Changesets](https://github.com/changesets/changesets)
* [ESLint](https://github.com/eslint/eslint), [Prettier](https://github.com/prettier/prettier) and [lint-staged](https://github.com/okonet/lint-staged)
* Git hooks managed by [husky](https://github.com/typicode/husky)
* [Typescript](https://github.com/microsoft/typescript)

## Usage

Click `Use this template` from the top of this repository, or select the `@bcgov/eslmd-nodejs-quickstart` template when creating a new repository.

The generated repository requires an initial build step which is initiated by the `cookiecutter.yaml` workflow.  Once this workflow finishes, the repository will be ready for use.

## References

* Willison, Simon "Dynamic content for GitHub repository templates using cookiecutter and GitHub Actions" _Simon Willison's Weblog_ 28 August 2021 https://simonwillison.net/2021/Aug/28/dynamic-github-repository-templates/