# Contributing to Our Projects

Thank you for your interest in contributing to our organization! This document provides guidelines and instructions to help make the contribution process clear and effective for everyone involved.

## Table of Contents

- [Code of Conduct](#code-of-conduct)
- [Getting Started](#getting-started)
- [How to Contribute](#how-to-contribute)
  - [Reporting Bugs](#reporting-bugs)
  - [Suggesting Features](#suggesting-features)
  - [Pull Requests](#pull-requests)
- [Development Workflow](#development-workflow)
  - [Setting Up Your Environment](#setting-up-your-environment)
  - [Branching Strategy](#branching-strategy)
  - [Commit Guidelines](#commit-guidelines)
- [Communication Channels](#communication-channels)
- [Project Structure](#project-structure)
- [Documentation](#documentation)
- [Licensing and Contributor Agreement](#licensing-and-contributor-agreement)
- [Accessibility Considerations](#accessibility-considerations)
- [Recognition](#recognition)

## Code of Conduct

This project and everyone participating in it is governed by our [Code of Conduct](CODE_OF_CONDUCT.md). By participating, you are expected to uphold this code. Please report unacceptable behavior to coc@spicycentral.org.

## Getting Started

### New to Open Source?

If you're new to open source contributions, these resources might help:
- [How to Contribute to Open Source](https://opensource.guide/how-to-contribute/)
- [First Contributions](https://github.com/firstcontributions/first-contributions) - A hands-on tutorial
- [Good First Issues](https://goodfirstissues.com/) - Find beginner-friendly issues

### Prerequisites

TODO:
- [List required software, tools, accounts, etc.] 
- [Include version requirements if applicable]

## How to Contribute

### Reporting Bugs

Bug reports help us improve our projects. When reporting bugs, please:

1. **Check Existing Issues** to avoid duplicates
2. **Use the Bug Report Template** when creating a new issue
3. **Provide Clear Steps** to reproduce the problem
4. **Include Environment Details** (OS, browser, versions)
5. **Add Screenshots** if applicable

### Suggesting Features

We welcome feature suggestions that align with our project goals. When suggesting features:

1. **Check Existing Issues** to avoid duplicates
2. **Use the Feature Request Template**
3. **Describe the Problem** your feature solves
4. **Outline Proposed Solution**
5. **Discuss Alternatives** you've considered

### Pull Requests

1. **Start with an Issue** - Discuss changes before coding
2. **Fork the Repository**
3. **Create a Branch** (`git checkout -b feature/your-feature-name`)
4. **Make Changes** following our code style
5. **Run Tests** to ensure they pass
6. **Submit Your PR** using our pull request template
7. **Respond to Feedback** during code review

All pull requests will be squashed into a single commit when merged. This keeps our commit history clean and focused on completed features. Please ensure:

1. Your PR title follows the [Conventional Commits](https://www.conventionalcommits.org/) format since it will become the squashed commit message
2. All individual commits in the PR are signed-off (using `git commit -s`)
3. The PR description provides context and summarizes the changes appropriately

## Development Workflow

### Setting Up Your Environment

TODO:
```bash
# Clone the repository
git clone https://github.com/organization/repository.git
cd repository

# Install dependencies
npm install  # or equivalent for your stack

# Run setup script
./scripts/setup.sh
```

### Branching Strategy

- `main` - Production-ready code
- `develop` - Integration branch for features
- `feature/name` - New features
- `fix/name` - Bug fixes
- `docs/name` - Documentation changes

### Commit Guidelines

We follow [Conventional Commits](https://www.conventionalcommits.org/):

```text
<type>(<scope>): <description>

[optional body]

[optional footer]
```

Types include: `feat`, `fix`, `docs`, `style`, `refactor`, `test`, `chore`

Example: `feat(auth): add multi-factor authentication option`

## Communication Channels

- **Issues** - Feature discussions and bug reports
- **Pull Requests** - Code review discussions
- **[Chat Platform]** - Quick questions and community discussions
- **[Mailing List/Forum]** - Long-form discussions and announcements

## Project Structure

```text
project/
├── docs/            # Documentation
├── src/             # Source code
├── tests/           # Test suite
├── examples/        # Example usage
└── scripts/         # Utility scripts
```

## Documentation

Documentation is crucial for our project. Please:

- Update README.md with any relevant changes
- Add code comments that explain "why" not just "what"
- Update API documentation for any changed interfaces
- Include examples for new features

## Licensing and Contributor Agreement

Our projects are dual-licensed under:

1. **MIT License** - For open source usage
2. **Commercial License** - For commercial applications

### Contributor License Agreement (CLA)

Before your contributions can be merged, you must sign our Contributor License Agreement. This agreement ensures that:

1. You have the legal right to make your contribution
2. You grant us permission to use your contribution under both our open source and commercial licenses
3. You understand that your contribution may be used in commercial products

The CLA signing process is automated through our CLA bot when you open your first pull request.

### Developer Certificate of Origin (DCO)

We require all commits to be signed off, certifying that you have the right to submit your contribution. Add the `-s` flag to your commits:

```bash
git commit -s -m "Your commit message"
```

This adds a `Signed-off-by` line to your commit message, confirming you adhere to the [Developer Certificate of Origin](https://developercertificate.org/).

## Accessibility Considerations

We're committed to making our projects accessible to everyone:

- Ensure UI components meet WCAG 2.1 AA standards
- Provide alternative text for images in documentation
- Use semantic HTML in web interfaces
- Test with screen readers when applicable
- Maintain sufficient color contrast ratios

## Recognition

Contributors are recognized in several ways:

- Added to the CONTRIBUTORS.md file
- Mentioned in release notes
- Opportunity to become project maintainers based on consistent contributions

---

Thank you for contributing to our community!
