<p align="center">
  <img src="https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png" width="200" alt="GitHub Official Logo">
</p>

<h1 align="center">GitHub Master Guide</h1>

<p align="center">
  <b>Complete GitHub Rules, Repository Guide, Licensing, Security & Developer Documentation</b>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Platform-GitHub-black?logo=github" alt="GitHub">
  <img src="https://img.shields.io/badge/Guide-English-blue" alt="English">
  <img src="https://img.shields.io/badge/License-GPL--3.0-blue" alt="GPL 3.0">
  <img src="https://img.shields.io/badge/Status-Documentation-success" alt="Documentation">
</p>

---

## 📖 About This Guide

GitHub is a powerful platform where developers publish and manage source code, projects, scripts, documentation, and open-source software.

The purpose of this repository is to explain GitHub's important features, rules, policies, limitations, and best practices in one place.

This guide covers each topic in English and is designed to help both beginners and experienced developers understand GitHub.

**In this guide, you will learn about:**

- GitHub account and profile management.
- Repository creation and management.
- Public and private repositories.
- Repository naming and file structure.
- README files and documentation.
- Open-source licenses and their legal requirements.
- Account flags, restrictions, and suspensions.
- Account recovery and appeals.
- Daily repository creation.
- File-size and upload limitations.
- Uploading large files with Git LFS.
- Git commands and version control.
- Forks, pull requests, and issues.
- Releases and GitHub Actions.
- Profile achievements and badges.
- Contribution graphs and profile optimization.
- Account security and responsible development.

---

# 📑 Table of Contents

1. [GitHub Introduction](#1-github-introduction)
2. [Difference Between Git and GitHub](#2-difference-between-git-and-github)
3. [Creating a GitHub Account](#3-creating-a-github-account)
4. [Account Security](#4-account-security)
5. [GitHub Profile](#5-github-profile)
6. [Introduction to Repositories](#6-introduction-to-repositories)
7. [Creating a Repository](#7-creating-a-repository)
8. [Public vs. Private Repositories](#8-public-vs-private-repositories)
9. [Repository Naming Rules](#9-repository-naming-rules)
10. [Repository File Structure](#10-repository-file-structure)
11. [README.md Guide](#11-readmemd-guide)
12. [Repository Upload Rules](#12-repository-upload-rules)
13. [Copyright Rules](#13-copyright-rules)
14. [Complete License Guide](#14-complete-license-guide)
15. [GNU GPL v3 Explained](#15-gnu-gpl-v3-explained)
16. [License Comparison](#16-license-comparison)
17. [GitHub Account Flags](#17-github-account-flags)
18. [Reasons for Account Suspension](#18-reasons-for-account-suspension)
19. [Account Recovery](#19-account-recovery)
20. [Appeal Process](#20-appeal-process)
21. [Daily Repository Creation](#21-daily-repository-creation)
22. [GitHub File Size Limits](#22-github-file-size-limits)
23. [Uploading Large Files](#23-uploading-large-files)
24. [Installing Git LFS](#24-installing-git-lfs)
25. [Uploading 2 GB Files](#25-uploading-2-gb-files)
26. [Git Push Limits](#26-git-push-limits)
27. [Repository Size Management](#27-repository-size-management)
28. [Git Commands](#28-git-commands)
29. [Commits and Branches](#29-commits-and-branches)
30. [Forks and Pull Requests](#30-forks-and-pull-requests)
31. [GitHub Issues](#31-github-issues)
32. [GitHub Releases](#32-github-releases)
33. [GitHub Actions](#33-github-actions)
34. [GitHub Discussions](#34-github-discussions)
35. [GitHub Pages](#35-github-pages)
36. [GitHub Stars and Followers](#36-github-stars-and-followers)
37. [GitHub Achievements](#37-github-achievements)
38. [GitHub Profile Badges](#38-github-profile-badges)
39. [Contribution Graph](#39-contribution-graph)
40. [GitHub Security Features](#40-github-security-features)
41. [Ethical Hacking Repository Rules](#41-ethical-hacking-repository-rules)
42. [.gitignore Guide](#42-gitignore-guide)
43. [Common GitHub Mistakes](#43-common-github-mistakes)
44. [Developer Best Practices](#44-developer-best-practices)
45. [Official GitHub Links](#45-official-github-links)
46. [Final Guidelines](#46-final-guidelines)

---

# 1. GitHub Introduction

GitHub is a cloud-based development platform that uses the Git version control system.

With GitHub, you can:

- Host projects online.
- Share source code.
- Maintain project history.
- Collaborate with a team.
- Contribute to open-source projects.
- Report bugs.
- Publish software releases.
- Automate testing and deployment.
- Build a professional developer portfolio.

**Official Website:**

https://github.com/

**Official Documentation:**

https://docs.github.com/

# 2. Difference Between Git and GitHub

### Git

Git is a distributed version control system.

Its responsibilities include:

- Tracking code changes.
- Creating commits.
- Managing branches.
- Restoring previous versions.
- Merging changes from different developers.

### GitHub

GitHub is an online platform that hosts Git repositories.

It provides additional features, including:

- Pull Requests.
- Issues.
- Discussions.
- Actions.
- Releases.
- Projects.
- Security alerts.

Git can work locally on your computer, while GitHub provides online collaboration features.

**Official Git Website:**

https://git-scm.com/

# 3. Creating a GitHub Account

Follow these steps to create a GitHub account:

1. Open https://github.com/.
2. Click **Sign Up**.
3. Enter your email address.
4. Create a strong password.
5. Choose a unique username.
6. Complete email verification.
7. Enable Two-Factor Authentication.

### Username Rules

- Choose a professional username.
- Do not copy another developer's identity.
- Avoid unnecessary numbers and symbols.
- Keep your username simple and memorable.

**Official Guide:**

https://docs.github.com/en/account-and-profile

# 4. Account Security

Keeping your GitHub account secure is essential.

### Important Security Rules

- Use a strong and unique password.
- Enable Two-Factor Authentication.
- Store recovery codes in a secure location.
- Remove unknown SSH keys.
- Revoke unknown Personal Access Tokens.
- Remove access for suspicious OAuth applications.
- Keep your account recovery email secure.
- Sign out when using a public computer.

### Two-Factor Authentication

2FA adds an additional layer of security to your account.

In addition to your password, a second verification method is required.

**Official Guide:**

https://docs.github.com/en/authentication/securing-your-account-with-two-factor-authentication-2fa

# 5. GitHub Profile

Your GitHub profile represents your developer identity.

Your profile can include:

- Profile Picture.
- Username.
- Display Name.
- Bio.
- Location.
- Website.
- Social Links.
- Profile README.
- Pinned Repositories.
- Contributions.
- Achievements.

### Profile README

Create a public repository with exactly the same name as your GitHub username, then add a `README.md` file to it.

Example:

```text
Username: KiraCyber

Repository: KiraCyber/KiraCyber

File: README.md
```

GitHub displays this README on your profile.

**Guide:**

https://docs.github.com/en/account-and-profile

# 6. Introduction to Repositories

A repository is a project folder together with its Git history.

It can contain source code, documentation, images, scripts, and configuration files.

Example:

```text
ByteBreaker/
│
├── README.md
├── LICENSE
├── install.sh
├── requirements.txt
├── .gitignore
│
├── src/
│   └── main.py
│
├── assets/
│   └── logo.png
│
└── docs/
    └── guide.md
```

# 7. Creating a Repository

Follow these steps to create a repository:

1. Sign in to GitHub.
2. Select **New Repository**.
3. Enter a repository name.
4. Add a description.
5. Select **Public** or **Private**.
6. Initialize the repository with a README if needed.
7. Select a license if appropriate.
8. Click **Create Repository**.

**Official Guide:**

https://docs.github.com/en/repositories/creating-and-managing-repositories/creating-a-new-repository

# 8. Public vs. Private Repositories

### Public Repository

A public repository can be viewed by people on the internet.

Features:

- Public visibility.
- GitHub users can fork it.
- It can receive stars and watchers.
- It can receive contributions.
- It can be used to publish open-source projects.

### Private Repository

A private repository is available only to authorized users.

Features:

- Restricted access.
- Team collaboration.
- Private development.
- Controlled access permissions.

### Important

A public repository does not mean that every user automatically receives legal permission to reuse its content in any way.

It is important to understand both the applicable license and GitHub's Terms.

# 9. Repository Naming Rules

A repository name should be meaningful.

**Good Examples:**

```text
GitHub-Complete-Handbook
ByteBreaker
Network-Scanner
Linux-Toolkit
Web-Security-Guide
Python-Automation
```

**Avoid:**

```text
test123
newrepo999
project-final-final
random-files
```

Tips:

- Make the project's purpose clear.
- Use short and professional names.
- Avoid misleading names.
- Do not create duplicate repositories unnecessarily.
- Avoid unnecessary special characters.

# 10. Repository File Structure

A professional repository should be properly organized.

Example:

```text
Project/
│
├── README.md
├── LICENSE
├── CHANGELOG.md
├── CONTRIBUTING.md
├── SECURITY.md
├── CODE_OF_CONDUCT.md
├── .gitignore
├── requirements.txt
│
├── src/
├── docs/
├── tests/
├── assets/
└── examples/
```

### Important Files

| File | Purpose |
|---|---|
| README.md | Project documentation |
| LICENSE | Usage and distribution permissions |
| CHANGELOG.md | Version changes |
| CONTRIBUTING.md | Contribution guidelines |
| SECURITY.md | Security reporting instructions |
| CODE_OF_CONDUCT.md | Community behavior rules |
| .gitignore | Specifies untracked files to ignore |
| requirements.txt | Python dependencies |

Not every project needs all of these files.

# 11. README.md Guide

A README is the main documentation file for a repository.

A good README should include these sections:

1. Project Name.
2. Description.
3. Features.
4. Requirements.
5. Installation.
6. Usage.
7. Commands.
8. Examples.
9. Screenshots.
10. Troubleshooting.
11. Disclaimer.
12. License.
13. Credits.
14. Author Information.

### Markdown Example

```markdown
# Project Name

Project description.

## Features

- Feature One
- Feature Two

## Installation

```bash
git clone REPOSITORY_URL
cd PROJECT
```

## Usage

```bash
python3 main.py
```

## License

GNU GPL v3.0
```

Keep your README simple, readable, and up to date.

**Official Guide:**

https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-readmes

# 12. Repository Upload Rules

### What Can You Upload?

- Original source code.
- Python scripts.
- Bash scripts.
- JavaScript applications.
- C and C++ projects.
- Ethical hacking tools.
- Educational cybersecurity projects.
- Documentation.
- Tutorials.
- Screenshots.
- Logos.
- Configuration files.
- Open-source projects.

### What Should You Not Upload?

- Stolen passwords.
- Leaked databases.
- Private personal information.
- Stolen source code.
- Unauthorized credentials.
- Private SSH keys.
- API secrets.
- Pirated software.
- Copyrighted files without permission.
- Harmful malicious content.
- Spam or misleading material.

Following GitHub's Acceptable Use Policy is essential.

https://docs.github.com/en/site-policy/acceptable-use-policies/github-acceptable-use-policies

# 13. Copyright Rules

Copyright protects ownership rights in original work.

Rules:

- Publish your own original code.
- Check the license before copying someone else's code.
- Preserve original copyright notices.
- Check the licenses of third-party dependencies.
- Do not redistribute copyrighted files without permission.
- Follow the applicable conditions when using external assets in your project.

A public repository does not eliminate copyright protection.

# 14. Complete License Guide

A license is a legal document that defines how other developers may use, modify, and distribute your project.

Without a license, default copyright rules apply.

Examples of common licenses available for use on GitHub include:

### 14.1 MIT License

MIT is a permissive open-source license.

Permissions:

- Commercial use.
- Modification.
- Distribution.
- Private use.
- Sublicensing.

Conditions:

- Preserve the copyright notice.
- Include the license notice.

The MIT License does not require modified software to remain open source.

https://opensource.org/license/mit

### 14.2 Apache License 2.0

Apache 2.0 is a permissive license.

Features:

- Commercial use is allowed.
- Modification is allowed.
- Distribution is allowed.
- Includes patent license provisions.
- Copyright notices must be preserved.
- Changes may need to be documented as required by the license.

https://www.apache.org/licenses/LICENSE-2.0

### 14.3 GNU GPL v2.0

GPL v2 is a copyleft license.

Features:

- You can use the software.
- You can modify it.
- You can distribute it.
- Covered modified versions must follow GPL v2 conditions when distributed.
- Applicable source-code requirements must be followed.

https://www.gnu.org/licenses/old-licenses/gpl-2.0.html

### 14.4 GNU GPL v3.0

GPL v3 is a strong copyleft open-source license.

Features:

- You can use the software.
- You can modify the source code.
- You can distribute copies.
- Commercial distribution is allowed.
- Covered modified versions must follow GPL v3 when distributed.
- Applicable source-code requirements must be met.
- It also includes patent and anti-tivoization provisions.

**Important:** GPL v3 does not prohibit copying or modification. It grants these permissions while imposing specific conditions on redistribution and modified versions.

https://www.gnu.org/licenses/gpl-3.0.en.html

### 14.5 GNU LGPL

LGPL is a library-oriented copyleft license.

Its purpose is to provide flexibility for using libraries with other software.

LGPL has its own conditions for linking, modification, and distribution.

https://www.gnu.org/licenses/lgpl-3.0.en.html

### 14.6 GNU AGPL v3

AGPL v3 introduces additional copyleft requirements for network-based software.

If users interact with covered modified software over a network, source-code offer requirements may apply.

https://www.gnu.org/licenses/agpl-3.0.en.html

### 14.7 BSD 2-Clause

This is a permissive license.

- Commercial use.
- Modification.
- Distribution.
- Preserve copyright and license notices.

https://opensource.org/license/bsd-2-clause

### 14.8 BSD 3-Clause

Like BSD 2-Clause, this is a permissive license. However, it also restricts using the names of the original contributors to endorse or promote derived products without permission.

https://opensource.org/license/bsd-3-clause

### 14.9 ISC License

ISC is a simple permissive license.

- Use is allowed.
- Modification is allowed.
- Distribution is allowed.
- Preserve the copyright and permission notice.

https://opensource.org/license/isc-license-txt

### 14.10 Mozilla Public License 2.0

MPL 2.0 is a file-level copyleft license.

When distributing modifications to covered files, you must follow the conditions of the MPL.

https://www.mozilla.org/en-US/MPL/2.0/

### 14.11 Creative Commons Licenses

Creative Commons licenses are generally used for documentation, articles, educational content, images, and other creative works.

Common options:

- CC BY: Attribution is required.
- CC BY-SA: Attribution and sharing under the same license are required.
- CC BY-NC: Non-commercial restrictions apply.
- CC BY-ND: No derivatives are permitted.
- CC0: A public-domain dedication framework.

**Official Website:**

https://creativecommons.org/share-your-work/cclicenses/

### 14.12 Unlicense

The Unlicense aims to provide maximum freedom through a public-domain dedication.

https://unlicense.org/

### License Comparison

| License | Commercial Use | Modification | Copyleft |
|---|---|---|---|
| MIT | Yes | Yes | No |
| Apache 2.0 | Yes | Yes | No |
| GPL v2 | Yes | Yes | Yes |
| GPL v3 | Yes | Yes | Yes |
| LGPL | Yes | Yes | Limited |
| AGPL | Yes | Yes | Strong |
| BSD 2-Clause | Yes | Yes | No |
| BSD 3-Clause | Yes | Yes | No |
| ISC | Yes | Yes | No |
| MPL 2.0 | Yes | Yes | File-level |
| CC BY | Yes | Yes | No |
| CC BY-SA | Yes | Yes | ShareAlike |

Read the complete legal terms before selecting a license.

**Official License Selector:**

https://choosealicense.com/

# 15. GNU GPL v3 Explained

The selected license for this repository is GNU GPL v3.0.

This means:

1. Users can make copies of the project.
2. Users can modify the source code.
3. Users can distribute modified versions.
4. Users can use the project for commercial purposes.
5. Applicable GPL conditions must be followed when distributing the software.
6. Requirements to provide covered source code may apply.
7. Copyright and license notices must be preserved.

### What Does GPL v3 Not Allow?

- It does not permit removing the original copyright notices.
- It does not permit distributing covered modified software while ignoring the license conditions.
- It does not generally permit converting GPL-covered work into a proprietary distribution without complying with the applicable conditions.

### Important Clarification

Users can fork a public GitHub repository under GitHub's Terms.

GPL v3 goes further by defining the rights and conditions for copying, modifying, and distributing the licensed work.

If your goal is to prevent copying and modification, GPL v3 is not suitable for that purpose.

# 16. How to Add a License

When creating a new repository:

1. Open **Create Repository**.
2. Open the **Add a license** option.
3. Select **GNU General Public License v3.0**.
4. Create the repository.

For an existing repository:

1. Click **Add file**.
2. Select **Create new file**.
3. Name the file `LICENSE`.
4. Add the official GPL v3 license text.
5. Commit the changes.

**Official GPL Text:**

https://www.gnu.org/licenses/gpl-3.0.txt

# 17. GitHub Account Flags

An account flag, restriction, and suspension are not the same thing.

GitHub may take moderation action against content or an account in different circumstances.

Possible effects:

- Content visibility may be restricted.
- A repository may be disabled.
- Some account activities may become unavailable.
- An account may be suspended or terminated.

A reported repository does not automatically mean that the account will be suspended.

# 18. Reasons for Account Suspension

Possible reasons include:

### Spam Activity

- Repeated spam content.
- Fake promotional activity.
- Automated abusive activity.
- Unnecessary repeated issues.
- Misleading repositories.

### Copyright Violations

- Unauthorized distribution of copyrighted software.
- Ignoring valid takedown notices.
- Violating another person's intellectual property rights.

### Security Violations

- Distributing stolen credentials.
- Unauthorized harmful activity.
- Distributing malicious content.
- Violating users' privacy.

### Harassment

- Threatening behavior.
- Targeted harassment.
- Doxxing.
- Violations of community guidelines.

### Suspicious Activity

- Compromised accounts.
- Unauthorized access.
- Suspicious automated behavior.

### Legal Restrictions

Additional restrictions may apply according to applicable laws and GitHub policies.

**Official Policies:**

https://docs.github.com/en/site-policy/acceptable-use-policies/github-acceptable-use-policies

https://docs.github.com/en/site-policy/github-terms/github-community-guidelines

# 19. Account Recovery

If your account becomes restricted or compromised:

### Step 1: Check Your Email

Check your official email from GitHub.

Also check your Spam and Junk folders.

### Step 2: Secure Your Account

- Change your password.
- Review unknown sessions and applications.
- Remove unknown SSH keys.
- Revoke Personal Access Tokens.
- Secure your email account.
- Enable 2FA.

### Step 3: Understand the Restriction

Read the reason provided in GitHub's notification.

### Step 4: Make Required Changes

If content violates a policy, complete the required corrective actions.

### Step 5: Submit an Official Appeal

https://support.github.com/contact/reinstatement

### Step 6: Wait for Review

The GitHub team will review your appeal.

Recovery is not guaranteed.

**Important:** Do not attempt to bypass a suspension by creating a new account.

# 20. Appeal Process

An appeal means challenging a GitHub moderation decision.

Reinstatement means requesting the restoration of account or content access after completing the required changes.

When submitting an appeal:

- Mention your GitHub username.
- Explain the restriction details.
- Provide relevant evidence.
- Explain if your account was compromised.
- Use professional language.
- Do not provide false information.

According to GitHub's published process referenced in this guide, an appeal request may be submitted within six months of a moderation decision.

**Official Guide:**

https://docs.github.com/en/site-policy/acceptable-use-policies/github-appeal-and-reinstatement

# 21. Daily Repository Creation

GitHub does not specify a general published daily repository-creation quota for personal accounts.

This does not mean unlimited automated activity is permitted.

### Recommended Practices

- Create meaningful repositories.
- Avoid empty repositories.
- Do not create duplicate projects.
- Avoid spam activity.
- Write a description for every repository.
- Maintain a README.
- Organize each project properly.

### Quality vs. Quantity

One complete, useful, and well-documented repository is better than several empty repositories.

This is a recommendation, not an official GitHub daily quota.

# 22. GitHub File Size Limits

Different upload methods on GitHub have different limits.

| Upload Method | Limit |
|---|---:|
| Browser upload | 25 MiB per file |
| Normal Git file | 100 MiB maximum |
| Git warning | Above 50 MiB |
| GitHub Free LFS | 2 GB per file |
| GitHub Pro LFS | 2 GB per file |
| GitHub Team LFS | 4 GB per file |
| GitHub Enterprise Cloud LFS | 5 GB per file |

Files larger than 100 MiB cannot be uploaded using normal Git.

Use Git LFS for large files.

**Official Guide:**

https://docs.github.com/en/repositories/working-with-files/managing-large-files/about-large-files-on-github

# 23. Uploading Large Files

If a file is larger than 100 MiB, use Git LFS instead of normal Git.

Git LFS stores large files separately and maintains pointer files in the Git repository.

Benefits:

- Manage large binary files.
- Keep repository clones manageable.
- Track large project assets.
- Manage files with version control.

# 24. Installing Git LFS

Ubuntu / Debian:

```bash
sudo apt update

sudo apt install git-lfs
```

Verify the installation:

```bash
git lfs version
```

Initialize Git LFS:

```bash
git lfs install
```

**Official Website:**

https://git-lfs.com/

# 25. Uploading 2 GB Files

GitHub Free and Pro support a maximum individual Git LFS file size of 2 GB.

### Step 1: Clone the Repository

```bash
git clone https://github.com/USERNAME/REPOSITORY.git

cd REPOSITORY
```

### Step 2: Initialize Git LFS

```bash
git lfs install
```

### Step 3: Track Large Files

```bash
git lfs track "*.zip"
```

Or track a specific file:

```bash
git lfs track "large-file.zip"
```

### Step 4: Add Attributes

```bash
git add .gitattributes
```

### Step 5: Add the File

```bash
git add large-file.zip
```

### Step 6: Commit

```bash
git commit -m "Add large file using Git LFS"
```

### Step 7: Push

```bash
git push origin main
```

### Important

- The file must not exceed the 2 GB per-file limit.
- Check your storage quota.
- Check your bandwidth quota.
- Use a stable internet connection.
- Git LFS must be installed.

**Git LFS Billing:**

https://docs.github.com/en/billing/concepts/product-billing/git-lfs

# 26. Git Push Limits

GitHub has a maximum size limit of 2 GiB for a single Git push.

This is not a per-file limit.

If a push exceeds 2 GiB:

- Divide the push into smaller commits.
- Push in smaller batches.
- Remove unnecessary files.
- Use Git LFS for large binaries.

**Official Guide:**

https://docs.github.com/en/get-started/using-git/troubleshooting-the-2-gb-push-limit

# 27. Repository Size Management

Keeping GitHub repositories small is recommended.

Official recommendations:

- Ideally, keep a repository smaller than 1 GB.
- Keeping it smaller than 5 GB is strongly recommended.

Tips:

- Remove unnecessary binaries.
- Do not commit temporary files.
- Ignore build directories.
- Manage dependencies with a package manager.
- Avoid unnecessarily large Git history.
- Consider Git LFS or Releases for large files.

**Official Guide:**

https://docs.github.com/en/repositories/creating-and-managing-repositories/repository-limits

# 28. Git Commands

### Install Git

Ubuntu / Debian:

```bash
sudo apt install git
```

### Check Version

```bash
git --version
```

### Configure Username

```bash
git config --global user.name "Your Name"
```

### Configure Email

```bash
git config --global user.email "your@email.com"
```

### Initialize a Repository

```bash
git init
```

### Check Status

```bash
git status
```

### Add All Files

```bash
git add .
```

### Commit

```bash
git commit -m "Initial commit"
```

### Add Remote

```bash
git remote add origin https://github.com/USERNAME/REPOSITORY.git
```

### Rename Branch

```bash
git branch -M main
```

### Push

```bash
git push -u origin main
```

### Clone

```bash
git clone https://github.com/USERNAME/REPOSITORY.git
```

**Official Git Documentation:**

https://git-scm.com/doc

# 29. Commits and Branches

### Commit

A commit is a saved record of project changes.

Good commit messages:

```text
Initial commit
Add installation script
Fix bugs
Update README
Improve performance
Add new feature
Update dependencies
```

### Branch

A branch is a separate line of development.

Example:

```bash
git branch
git branch development
git switch development
```

Merge a branch:

```bash
git switch main
git merge development
```

Branches allow you to work on development without directly affecting the main project.

# 30. Forks and Pull Requests

### Fork

A fork is a copy of another repository on GitHub under your own account.

### Pull Request

A Pull Request is a request to merge your changes into the original repository.

### Contribution Rules

- Give credit to the original author.
- Follow the project's guidelines.
- Submit meaningful changes.
- Avoid unnecessary pull requests.
- Respect the code review process.

**Official Guide:**

https://docs.github.com/en/pull-requests

# 31. GitHub Issues

Issues are used to discuss project bugs and improvements.

Issues can be used for:

- Bug Reports.
- Feature Requests.
- Questions.
- Documentation Problems.
- Improvements.

When creating an issue:

1. Write a clear title.
2. Explain the problem.
3. Provide steps to reproduce it.
4. Describe the expected result.
5. Describe the actual result.
6. Add relevant screenshots or logs.

**Official Guide:**

https://docs.github.com/en/issues

# 32. GitHub Releases

Releases are used to publish stable versions of a project.

Example:

```text
v1.0.0
v1.1.0
v1.2.0
v2.0.0
```

A release can include:

- Version number.
- Release notes.
- Bug fixes.
- New features.
- Installation instructions.
- Downloadable assets.

GitHub Releases can be useful for distributing large binary files. Each individual asset must remain within the Git LFS maximum file-size limit for the applicable plan.

**Official Guide:**

https://docs.github.com/en/repositories/releasing-projects-on-github

# 33. GitHub Actions

GitHub Actions is used for automation and CI/CD.

You can use it for:

- Automated testing.
- Code quality checks.
- Build automation.
- Deployment.
- Scheduled workflows.
- Release automation.

Example workflow:

```yaml
name: Python Check

on:
  push:
    branches: [main]

jobs:
  test:
    runs-on: ubuntu-latest

    steps:
      - uses: actions/checkout@v4

      - name: Setup Python
        uses: actions/setup-python@v5
        with:
          python-version: "3.12"

      - name: Check Python
        run: python --version
```

Security note: Verify the authenticity and permissions of third-party Actions before using them. Never expose secrets in logs.

**Official Guide:**

https://docs.github.com/en/actions

# 34. GitHub Discussions

Discussions are designed for community conversations.

They can be used for:

- General Questions.
- Announcements.
- Ideas.
- Community Help.
- Q&A.

**Official Guide:**

https://docs.github.com/en/discussions

# 35. GitHub Pages

GitHub Pages is a service for hosting static websites.

You can use it to publish:

- Documentation websites.
- Portfolios.
- Project landing pages.
- Tutorials.
- Static HTML websites.

**Official Guide:**

https://docs.github.com/en/pages

# 36. GitHub Stars and Followers

### Stars

A star is used to bookmark a repository or show appreciation for it.

### Followers

Followers are users who follow your GitHub activity.

### Watchers

Watchers are users who subscribe to notifications from a repository.

### Important Rules

- Do not buy fake stars.
- Do not create fake followers.
- Avoid star-exchange spam.
- Do not use misleading promotion.
- Focus on genuine projects and contributions.

# 37. GitHub Achievements

GitHub Achievements are profile badges that recognize specific actions and milestones.

Achievements may appear in the sidebar of your profile.

Clicking or hovering over an achievement can show its description and details about the related activity.

### Important Achievement Examples

**1. Quickdraw**

An achievement related to responding quickly in a specific GitHub contribution event.

**2. Pull Shark**

An achievement related to getting Pull Requests merged.

**3. YOLO**

An achievement related to merging a specific Pull Request without the required review condition.

**4. Galaxy Brain**

An achievement related to accepted answers and helpful contributions in GitHub Discussions.

**5. Starstruck**

An achievement related to milestones in the number of stars received by your repository.

**6. Pair Extraordinaire**

An achievement related to co-authored contributions.

**7. Mars 2020 Helicopter Contributor**

An achievement awarded for qualifying historical contributions to the NASA Mars Helicopter open-source repositories. This event has ended and is no longer available.

### How to Unlock Achievements

- Contribute to open-source projects.
- Submit Pull Requests.
- Perform useful code reviews.
- Provide helpful answers in GitHub Discussions.
- Co-author commits with other developers.
- Publish useful original projects.
- Collaborate genuinely with the community.

### Important

- Achievement thresholds and availability may change.
- Not every achievement is automatically available to every user.
- Do not attempt to obtain achievements through fake activity.
- Some achievements are in public preview.

**Official Achievement Reference:**

https://docs.github.com/en/account-and-profile/reference/profile-reference

# 38. GitHub Profile Badges

In addition to achievements, GitHub profiles may display badges related to specific programs.

Examples:

### Developer Program Member

A badge for registered developers participating in the GitHub Developer Program and building applications with the GitHub API.

https://github.com/developer

### PRO Badge

Users with a GitHub Pro subscription may see a PRO badge on their profile.

https://github.com/pricing

### Security Bug Bounty Hunter

Related to eligible security research contributions through the GitHub Security program.

https://bounty.github.com/

### GitHub Campus Expert

For eligible members participating in the GitHub Campus Program.

https://education.github.com/

### Security Advisory Credit

Credit may be given for submitting an accepted security advisory to the GitHub Advisory Database.

https://github.com/advisories

**Note:** Profile badges and Achievements are not the same thing. Their eligibility requirements are different.

# 39. Contribution Graph

The GitHub contribution graph displays your contribution activity in a calendar format.

Different eligible activities may count as contributions, including:

- Commits.
- Pull Requests.
- Issues.
- Discussions.

### Green Squares

Different shades on the graph represent different levels of activity.

### Contribution Rules

- The commit email address must be linked to your GitHub account.
- Contributions must be made to an eligible repository and branch.
- The default branch and qualifying conditions matter.
- You can choose to display private contributions in your settings.
- Contribution dates may be calculated according to UTC and commit timestamps.

### How to Improve Your Contribution Graph

- Code regularly.
- Develop original projects.
- Contribute to open-source projects.
- Submit meaningful bug fixes.
- Improve documentation.
- Collaborate genuinely.

Do not create fake commits just to fill the graph with green squares.

**Official Guide:**

https://docs.github.com/en/account-and-profile/concepts/contributions-on-your-profile

# 40. GitHub Security Features

GitHub provides multiple security features.

### Dependabot

Helps identify security vulnerabilities and updates in project dependencies.

https://docs.github.com/en/code-security/dependabot

### Secret Scanning

Helps detect exposed secrets in repositories.

https://docs.github.com/en/code-security/secret-scanning

### Code Scanning

Helps identify potential security vulnerabilities in source code.

https://docs.github.com/en/code-security/code-scanning

### Security Advisories

Used to document and report security vulnerabilities responsibly.

https://docs.github.com/en/code-security/security-advisories

### Important

- Do not commit passwords.
- Do not upload API keys.
- Do not expose private keys.
- Ignore `.env` files.
- Do not ignore security alerts.

# 41. Ethical Hacking Repository Rules

Publishing cybersecurity and ethical hacking projects requires additional responsibility.

### Recommended Content

- Educational security tools.
- Authorized penetration-testing utilities.
- Network auditing scripts.
- Vulnerability research.
- Defensive security tools.
- Log analysis utilities.
- Linux security automation.
- Documentation and tutorials.

### Important Requirements

- Explain the purpose of the tool.
- Provide an installation guide.
- Mention dependencies.
- Explain the requirement for authorized testing.
- Include a legal disclaimer.
- Respect user privacy.
- Do not promote unauthorized access.
- Do not upload stolen credentials or private databases.

### Example Disclaimer

```text
DISCLAIMER:

This project is intended for educational
purposes and authorized security testing.

Users must obtain proper permission before
testing any system or network.

The author does not support unauthorized
access, data theft, or illegal activities.

Users are responsible for their own actions
and compliance with applicable laws.
```

A disclaimer does not make illegal activity legal. The tool's actual behavior and distribution are also relevant.

# 42. .gitignore Guide

A `.gitignore` file tells Git which untracked files should not be included in the repository.

Example:

```gitignore
# Environment Files
.env
.env.local

# Private Keys
*.pem
*.key
id_rsa

# Python
__pycache__/
*.pyc
venv/

# Node
node_modules/

# Logs
*.log

# Build Files
dist/
build/

# Temporary Files
*.tmp
*.bak
```

### Important

If a secret has already been committed, adding it to `.gitignore` will not automatically remove it from Git history.

Immediately revoke or rotate exposed credentials.

**Official Guide:**

https://git-scm.com/docs/gitignore

# 43. Common GitHub Mistakes

Avoid these mistakes:

1. Publishing a project without a README.
2. Selecting a license without understanding it.
3. Uploading API keys.
4. Hardcoding passwords.
5. Ignoring copyright.
6. Copying unauthorized code.
7. Creating duplicate repositories.
8. Purchasing fake stars.
9. Making unnecessary bulk commits.
10. Uploading large files through normal Git.
11. Failing to update dependencies.
12. Ignoring security vulnerabilities.
13. Writing misleading project descriptions.
14. Creating unnecessary numbers of empty repositories.
15. Behaving abusively toward community members.

# 44. Developer Best Practices

A professional GitHub developer should:

- Develop original projects.
- Keep README files complete.
- Select an appropriate license.
- Write meaningful commit messages.
- Keep project structures clean.
- Document dependencies.
- Perform security checks.
- Maintain release notes.
- Fix bugs responsibly.
- Contribute to open-source communities.
- Respect the rights of other developers.
- Read GitHub policies regularly.

**Remember:** Quality, originality, and documentation are more important than quantity.

# 45. Official GitHub Links

The following are important official resources.

### GitHub Main

- GitHub: https://github.com/
- GitHub Docs: https://docs.github.com/
- GitHub Blog: https://github.blog/
- GitHub Changelog: https://github.blog/changelog/
- GitHub Status: https://www.githubstatus.com/

### Account and Profile

- Account Guide: https://docs.github.com/en/account-and-profile
- Profile Guide: https://docs.github.com/en/account-and-profile/concepts/personal-profile
- Achievements: https://docs.github.com/en/account-and-profile/reference/profile-reference
- Contributions: https://docs.github.com/en/account-and-profile/concepts/contributions-on-your-profile
- Authentication: https://docs.github.com/en/authentication

### Repository Management

- Creating a Repository: https://docs.github.com/en/repositories/creating-and-managing-repositories/creating-a-new-repository
- README: https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-readmes
- Repository Limits: https://docs.github.com/en/repositories/creating-and-managing-repositories/repository-limits
- Git LFS: https://docs.github.com/en/repositories/working-with-files/managing-large-files
- Releases: https://docs.github.com/en/repositories/releasing-projects-on-github

### Licensing

- License Guide: https://choosealicense.com/
- MIT: https://opensource.org/license/mit
- Apache 2.0: https://www.apache.org/licenses/LICENSE-2.0
- GPL v3: https://www.gnu.org/licenses/gpl-3.0.en.html
- GPL v2: https://www.gnu.org/licenses/old-licenses/gpl-2.0.html
- LGPL: https://www.gnu.org/licenses/lgpl-3.0.en.html
- AGPL: https://www.gnu.org/licenses/agpl-3.0.en.html
- BSD: https://opensource.org/licenses/
- Creative Commons: https://creativecommons.org/

### Account Restrictions and Recovery

- Terms of Service: https://docs.github.com/en/site-policy/github-terms/github-terms-of-service
- Acceptable Use: https://docs.github.com/en/site-policy/acceptable-use-policies/github-acceptable-use-policies
- Community Guidelines: https://docs.github.com/en/site-policy/github-terms/github-community-guidelines
- Appeal & Reinstatement: https://docs.github.com/en/site-policy/acceptable-use-policies/github-appeal-and-reinstatement
- GitHub Support: https://support.github.com/contact

### Development Tools

- Git: https://git-scm.com/
- Git LFS: https://git-lfs.com/
- GitHub Actions: https://docs.github.com/en/actions
- GitHub Pages: https://docs.github.com/en/pages
- GitHub Issues: https://docs.github.com/en/issues
- GitHub Pull Requests: https://docs.github.com/en/pull-requests
- GitHub Discussions: https://docs.github.com/en/discussions

### Security

- GitHub Security: https://docs.github.com/en/code-security
- Dependabot: https://docs.github.com/en/code-security/dependabot
- Secret Scanning: https://docs.github.com/en/code-security/secret-scanning
- Code Scanning: https://docs.github.com/en/code-security/code-scanning
- Security Advisories: https://docs.github.com/en/code-security/security-advisories

---

# 46. Final Guidelines

GitHub is more than a platform. It gives developers an opportunity to share their knowledge, skills, and original projects with the world.

A responsible developer should always:

- Publish original code.
- Respect copyright and licensing conditions.
- Maintain account security.
- Document repositories properly.
- Follow GitHub policies.
- Behave professionally toward community members.
- Avoid unauthorized activities.
- Maintain projects regularly.

**LEARN • BUILD • SECURE • SHARE**

**Stay Ethical. Stay Secure. Keep Building.**

---

<p align="center">
  <b>GitHub Complete Handbook</b>
  <br>
  <i>An English Guide for Developers, Open-Source Contributors, and Cybersecurity Learners.</i>
</p>

<p align="center">
  Made for learning and responsible development.
</p>

<p align="center">
  <a href="https://github.com/">GitHub</a> ·
  <a href="https://docs.github.com/">Documentation</a> ·
  <a href="https://support.github.com/">Support</a>
</p>
