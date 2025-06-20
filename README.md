# mygitactions

This repository demonstrates the use of [GitHub Super-Linter](https://github.com/github/super-linter) with GitHub Actions.

## Features

- Automatic code linting on push and pull request to `main` and `develop` branches.
- Uses [Super-Linter](https://github.com/github/super-linter) for multi-language linting.

## GitHub Actions Workflow

The workflow is defined in [`.github/workflows/superlineter.yml`](.github/workflows/superlineter.yml):

- **Triggers:** On push or pull request to `main` or `develop`.
- **Jobs:**
  - Checks out the code.
  - Runs Super-Linter.

## Usage

1. Push code to `main` or `develop` branches, or open a pull request targeting these branches.
2. The Super-Linter will automatically run and report any linting issues.

## License

MIT
