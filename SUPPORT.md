# CodeTwin ML Support

## Where to get help

- **Installation, build, and usage:** Start with [README.md](README.md) and [development setup](docs/development/SETUP.md).
- **Bugs:** Open an issue using the bug report form. Include the exact commit or version, platform, reproducible steps, expected versus actual results, and sanitized logs.
- **Feature requests:** Open an issue using the feature request form and describe the use case, constraints, and acceptance criteria.
- **Contributing:** Read [CONTRIBUTING.md](CONTRIBUTING.md) before opening a pull request.
- **Security:** See [SECURITY.md](SECURITY.md). Never post a vulnerability, credential, proprietary source, or exploit details in a public issue.
- **Release readiness:** See [release gates](docs/development/RELEASE_GATES.md). Development implementation is not a substitute for signed installer or end-to-end validation.

## Supported environments

CodeTwin ML is under active development. The Windows Tauri desktop is the primary integration target. Platform-specific capabilities vary, especially strict QA execution and native packaging. Do not assume that every feature available in code is independently validated in a production installer.

## Before submitting an issue

Check existing issues, test against the current `main` branch when practical, reproduce with a safe disposable project, and remove sensitive data from any shared screenshots or logs.
