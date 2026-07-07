<h1 align="center">
    <img src="docs/assets/logo.png" alt="Skeletor project logo" height="100px" align="center">
    Skeletor Template Repository
</h1>

![License](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey)

Mwahaha! Feast your eyes on the ultimate template repository, conjured from the depths of my sinister genius! This rad collection arms you with all the gnarly tools to dominate your project setup like never before!

## Features
- **Bodacious Issue and Pull Request Templates**: Predefined templates for efficient issue tracking and pull request submissions.
  - **Bug Reports**: Create detailed bug reports with our comprehensive template, or face my scorn!
  - **Feature Requests**: Propose new features and enhancements, if you dare.
  - **Support Requests**: Seek help or clarification for any issues you encounter, under my watchful eye.
  - **Pull Requests**: Ensure consistent and well-documented contributions, as decreed by Skeletor!
- **Spectacular Agents Documentation**: Guidelines for AI coding agents to maintain code quality, security, and readability.
- **Gnarly Citation file**: A citation file to give proper credit for using this repository, as demanded by Skeletor!
- **Righteous Code of Conduct**: A short, practical code for respectful and constructive collaboration, or suffer my wrath.
- **Radical Codeowners**: Clearly define code ownership and responsibilities, ensuring my minions know their duties.
- **Totally Tubular Contributing Guidelines**: Clear contribution flow for issues, commits, and focused pull requests, as decreed from Snake Mountain.
- **Rad Renovate Configuration**: Automated dependency updates with customizable reviewer settings, ensuring my approval.
- **Sinister Security Policy**: Private and minimal guidance for responsible vulnerability reporting - reveal secrets publicly and incur my wrath.
- **Diabolical Support & Help Guide**: The fast route for support requests, bug reports, and feature ideas, all routed through my dark command center.
- **Savage .gitignore File**: Prevents clutter by ignoring unnecessary files from IDEs, build tools, and operating systems, keeping your domain pristine!
- **Wicked .gitattributes File**: Enforces consistent line endings (LF) across all platforms and correctly marks binary files — no more CRLF chaos from Windows contributors!
- **Tubular .editorconfig File**: Enforces consistent formatting rules (indentation, charset, trailing whitespace) across all editors and IDEs without additional plugins!
- **Eerie GitHub Pages Template**: Summon a sinister project site with a pre-forged GitHub Pages template, ready to spread your dark influence across the web!
- **Diabolical SBOM Workflow**: Automatically generate a Software Bill of Materials in CycloneDX format for any language and upload it as a workflow artifact — no configuration required!
- **Ruthless Dependency Review Workflow**: Block pull requests that introduce vulnerable or incompatibly licensed dependencies across all supported ecosystems!

## Adjustments When Forking
When you fork this repository, you will need to update several files to match your project’s specific details. These include:
- **`CITATION.cff`**: Update the citation file with your project’s specific details.
- **`CODE_OF_CONDUCT.md`**: Adjust behavior and reporting text to match your project's tone and contact channel.
- **`CODEOWNERS`**: Update with the GitHub usernames of the people who will maintain the forked repository.
- **`CONTRIBUTING.md`**: Tailor the contributing guidelines to fit your project's contribution process.
- **`.editorconfig`**: Adjust the indent sizes to match your project's coding conventions.
- **Issue and Pull Request Templates**: Ensure that any URLs are updated to point to your project's resources. Also update the `contact_links` in `.github/ISSUE_TEMPLATE/config.yml` to point to your project's discussions and documentation.
- **`SUPPORT.md`**: Update any references for reporting and ensure the support guidelines match your project.
- **`SECURITY.md`**: Ensure that the contact information for reporting security vulnerabilities is updated to the appropriate contact for your project.
- **`README.md`**: Create your own readme file to reflect your project’s purpose and details.
- **URLs**: Search the entire repository for any URLs or references containing "skeletor" or "drachenpapa" and replace them with links pointing to your own project and profile.
- **Workflows**: Two ready-to-use workflows are included: an SBOM generator (`sbom.yml`) and a dependency review check (`dependency-review.yml`). Both are language-agnostic and require no configuration. When referencing GitHub Actions, always pin them to a full commit SHA instead of a mutable tag (e.g. `actions/checkout@<full-commit-sha>` instead of `actions/checkout@v4`) to protect against supply-chain attacks.
- **Renovate Configuration**: Remove the default.json and update configurations as needed.
- **GitHub Pages**: If you plan to use GitHub Pages, set it up in the repository settings and update the site content in the `docs` directory.

## Why *Skeletor*?
This repository contains all the necessary special files to kickstart a project on GitHub. It is meant to be the base, or a skeleton, hence the name *Skeletor*.

## License
This project is licensed under the Creative Commons Attribution 4.0 International (CC BY 4.0) License. For more details, visit the [full license text](https://creativecommons.org/licenses/by/4.0/legalcode).
