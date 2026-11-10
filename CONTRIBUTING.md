# Contributing to {{PROJECT_NAME}}

Thanks for taking the time to contribute. This guide covers how to report problems, set up a development environment, and submit changes.

## Reporting bugs

Open an [issue](https://github.com/{{OWNER}}/{{REPO}}/issues) and include:

- What you expected to happen and what actually happened
- Steps to reproduce
- Your {{PROJECT_NAME}} version or commit, and how you run it (host OS, runtime or container engine)
- Relevant log output
<!-- TEMPLATE: add project specific details people should include (modes, configuration, integrations) -->

Remove passwords, tokens, keys, and private hostnames from anything you post.

**Security problems must not be reported in public issues.** Follow [SECURITY.md](SECURITY.md) instead.

## Suggesting features

Open an issue describing the problem you want solved before writing code. For larger changes this avoids work on something that doesn't fit the project.
<!-- TEMPLATE: add a link to Discord / Discussions / other community channel here if there is one -->

## Development setup

Requirements:

<!-- TEMPLATE: list the tooling needed (language runtime and version, package manager, build tools) -->
- {{REQUIREMENT_1}}
- {{REQUIREMENT_2}}

```bash
git clone https://github.com/{{OWNER}}/{{REPO}}.git
cd {{REPO}}
git checkout develop
{{SETUP_AND_BUILD_COMMANDS}}
```

## Project layout

<!-- TEMPLATE: describe the real layout, or delete this section for small projects -->

| Path | Purpose |
| ---- | ------- |
| `{{PATH_1}}` | {{PURPOSE_1}} |
| `{{PATH_2}}` | {{PURPOSE_2}} |

## Making changes

1. Fork the repository and create a branch from `develop`: `git checkout -b feature/short-description`
2. Keep the change focused. Don't mix unrelated fixes, refactors, or reformatting into the same pull request.
3. Match the surrounding code: naming, comment style, and error handling.
4. Comment new code properly, following the project's documentation style.
5. Run the checks below.

```bash
{{LINT_COMMAND}}
{{BUILD_COMMAND}}
```

Do not commit credentials, `.env` files, or generated artifacts such as build or coverage output.

## Pull requests

- Target the `develop` branch.
- Describe what changed and why, and link any related issue.
- Note how you tested the change.
- Keep the first line of each commit message short and in the imperative mood, for example `Fix crash when the config file is missing`.

Pull requests are reviewed as time allows. You may be asked for changes before a merge.

## License

By contributing, you agree that your contributions are licensed under the [MIT License](LICENSE).
