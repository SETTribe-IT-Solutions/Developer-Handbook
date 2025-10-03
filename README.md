# Developer Handbook

Welcome to the **Developer Handbook** 👩‍💻👨‍💻

This repository defines the coding standards, best practices, and project workflows to be followed across all teams. It acts as a **single source of truth** for maintaining consistency, readability, and maintainability across all projects.

---

## 📚 Index

- [Standard Folder Structure](#-standard-folder-structure-html-css-js-php-sql-projects)
- [File Naming Conventions](#-file-naming-conventions)
- [Variable Naming Conventions](#-variable-naming-conventions)
- [Git Commit Guidelines](#-git-commit-guidelines)
- [Pull Request Guidelines](#-pull-request-guidelines)
- [Coding Standards](#-coding-standards)
- [Environment Setup](#️-environment-setup)
- [DBeaver — Remote MySQL Database Handbook (step-by-step) Setup](./database-remote-access.md)
- [WABA Account Verification Process](./waba-verification.md)
- [Project & Task Management](./project-management.md)
- [Onboarding Guide](#-onboarding-guide)
- [Contribution Guidelines](#-contribution-guidelines)
- [Versioning](#-versioning)
- [Getting Started](#-getting-started)

---

## 📂 Standard Folder Structure (HTML, CSS, JS, PHP, SQL Projects)

```
index.html
css/
    style.css
script/
    script.js
include/
    header.php
    footer.php
    functions.php
ajax/
    fetch_page.php
```

🔹 **Guidelines:**

- All file and folder names must begin in **lowercase only**.
- Spaces are not allowed – use **underscore** (`_`) instead.
- Example: `fetch_page.php` ✅ instead of `Fetch Page.php` ❌

---

## 📄 File Naming Conventions

- Use descriptive names relevant to the file’s functionality.
- Example: `user_profile.php`, `batch_report.sql`

---

## 📝 Variable Naming Conventions

- Use **camelCase** for variables.
- Examples:
  - `srNo`
  - `batchNo`
  - `userEmail`

---

## 🔀 Git Commit Guidelines

**Commit Message Format:**

```
YourName_FeatureName
YourName_FixDetails
```

Examples:

- `Sarang_LoginPage`
- `Sarang_FixLoginIssue`

---

## 📌 Pull Request Guidelines

**PR Naming Convention:**

```
[YourName] FeatureName / BugName
```

Examples:

- `[Sarang] Adding Login & Sign Up Page`
- `[Meher] Fixing API Timeout Issue`

---

## 💻 Coding Standards

- Follow proper indentation and code formatting.
- Keep functions small, reusable, and well-documented.
- Avoid hardcoding values – use constants or config files.
- SQL queries should be formatted for readability.
- Always sanitize inputs before database operations.

---

## ⚙️ Environment Setup

- Recommended IDE: **VS Code** with extensions for PHP, JS, and linting.
- Configure Git in your system with your official email and username.
- Use Prettier/ESLint for JS and PHPCS for PHP to maintain formatting.
- Install and configure **DBeaver Community Tool** for managing and accessing remote databases.
  - Refer to [Database Remote Access Guide](./database-remote-access.md) for step-by-step instructions.

---

## 🆕 Onboarding Guide

- Install required tools (VS Code, Git, MySQL, PHP, Apache/XAMPP).
- Clone the repository and follow the [Folder Structure](#-standard-folder-structure-html-css-js-php-sql-projects).
- Review Git commit & PR guidelines before your first contribution.
- Pair up with a mentor/lead for your first code review.

---

## ✅ Contribution Guidelines

- All updates to this handbook or codebase must be done via **Pull Requests (PRs)**.
- Each PR should follow the defined [PR Naming Convention](#-pull-request-guidelines).
- At least **one approval** from a team lead is required before merging.

---

## 🕒 Versioning

Use **CHANGELOG.md** for version history of this handbook.

Example:

```
## [1.0.0] - 2025-08-25
- Added initial folder structure and naming conventions
- Defined Git commit & PR standards
```

---

## 🚀 Getting Started

- New joiners should start with the [Onboarding Guide](#-onboarding-guide).
- All developers must strictly follow the standards in this handbook.

---

Happy Coding! ✨
