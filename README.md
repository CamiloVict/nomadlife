# Project Readme

Welcome to the Nomad-Life project! In this repository, we have a pre-commit hook set up to ensure that all code being committed meets our quality standards.

Before committing, the pre-commit hook automatically runs a linting and formatting process to ensure that the code is clean and well-structured.

In addition, to ensure that the commit history is easy to read and follow, we have established a standard format for commit messages. If a commit does not follow this format, it will be rejected and not included in the commit history.

## The commit format we use is as follows:

```bash
## Type:
feat - A new feature.
fix - A bug fix.
docs - Documentation only changes.
style - Changes that do not affect the meaning of the code (white-space, formatting, missing semi-colons, etc).
refactor - A code change that neither fixes a bug nor adds a feature.
test - Adding missing tests or correcting existing ones.
chore - Changes to the build process or auxiliary tools and libraries such as documentation generation.
perf - A code change that improves performance.
ci - Changes to your CI configuration files and scripts.
build - Changes that affect the build system or external dependencies (example scopes: gulp, broccoli, npm).
temp - Temporary commit that won't be included in your CHANGELOG.

## Scope:
Optional, can be anything specifying the scope of the commit change. For example $location, $browser, $compile, $rootScope, ngHref, ngClick, ngView, etc. In App Development, scope can be a page, a module, or a component.

## Subject:
Brief summary of the change in present tense. Not capitalized. No period at the end.
With this commit format, we ensure that the commit history is easy to read and follow, which helps developers understand the project's progress and identify changes that have affected a specific part of the code.
```

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

[API routes](https://nextjs.org/docs/api-routes/introduction) can be accessed on [http://localhost:3000/api/](http://localhost:3000/api/). This endpoint can be edited in `pages/api/`.

The `pages/api` directory is mapped to `/api/*`. Files in this directory are treated as [API routes](https://nextjs.org/docs/api-routes/introduction) instead of React pages.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

# Thank you for being part of this project and contributing to clean and well-organized code!
