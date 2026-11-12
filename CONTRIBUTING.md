# Contributing to Jiajiri

Thank you for your interest in contributing to the **Jiajiri** open-access technology ecosystem! We build open-source tools to democratize access to global remote careers and scientific research for Africa's high-caliber workforce.

---

## Code of Conduct

All contributors and participants are expected to adhere to our [Code of Conduct](CODE_OF_CONDUCT.md). Please read it before participating in discussions or opening pull requests.

---

## How Can You Contribute?

You can contribute to Jiajiri in several ways:
- **Reporting Bugs**: Open an issue describing the bug, including steps to reproduce, expected behavior, and screenshots if applicable.
- **Suggesting Enhancements**: Propose new features or UX improvements through GitHub Discussions or an issue.
- **Submitting Code**: Submit bug fixes, optimizations, or new features via Pull Requests.
- **Improving Documentation**: Fix typos, add explanations, or clarify instructions in README files and developer guides.

---

## Getting Started

1. **Fork and Clone**:
   Fork the repository you want to work on (e.g. `frontend-jiajiri`) and clone it locally:
   ```bash
   git clone git@github.com:<your-username>/frontend-jiajiri.git
   cd frontend-jiajiri
   ```

2. **Branch Naming**:
   Create a dedicated feature or fix branch from `main`:
   ```bash
   git checkout -b feat/your-feature-name
   # or
   git checkout -b fix/your-bugfix-name
   ```

3. **Install Dependencies & Verify**:
   ```bash
   npm install
   npx tsc --noEmit
   npm run dev
   ```

---

## Development & Code Standards

- **TypeScript Strictness**: All code must pass `npx tsc --noEmit` with zero errors.
- **Zero Hardcoded Secrets**: Never commit API keys, tokens, internal URLs, or credentials. Use `.env.example` and dynamic environment variables.
- **Accessible UI/UX**: Adhere to responsive design standards, high contrast ratios, and clear semantic HTML.
- **Commit Messages**: Follow the Conventional Commits specification:
  - `feat: add filter for remote timezones`
  - `fix: prevent text overflow on mobile job cards`
  - `docs: update deployment guidelines in README`

---

## Pull Request Process

1. Ensure all TypeScript and linting checks pass cleanly locally.
2. Verify the production build finishes without errors (`npm run build`).
3. Submit your Pull Request against the `main` branch.
4. Fill out the PR description with:
   - Summary of changes
   - Motivation / context
   - Verification steps or test output
5. Address any review comments promptly. Once approved and checks pass, maintainers will squash and merge your PR.

Thank you for making Jiajiri better for everyone!
