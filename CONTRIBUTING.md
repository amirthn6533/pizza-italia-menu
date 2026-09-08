# Contributing to pizza-italia-menu

Thank you for your interest in contributing! We welcome contributions from everyone.

## Code of Conduct
This project follows the [Contributor Covenant Code of Conduct](CODE_OF_CONDUCT.md). By participating, you are expected to uphold this code.

## How to Contribute

### 1. Reporting Bugs
- Check existing GitHub Issues to see if the bug has already been reported.
- If not, create a new issue using our **Bug Report** template with clear reproduction steps.

### 2. Suggesting Enhancements
- Open a feature request issue using our **Feature Request** template.
- Clearly describe the use case and proposed solution.

### 3. Pull Request Workflow
1. Fork the repository to your own GitHub account.
2. Clone your fork and create a descriptive feature branch:
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. Make your changes adhering to code style guidelines.
4. Add or update unit tests to verify your implementation.
5. Commit your changes using conventional commit messages:
   - `feat: add new feature`
   - `fix: resolve bug in parser`
   - `docs: update documentation`
   - `test: add unit tests`
6. Push to your branch and open a Pull Request against the default branch.

### Frontend / Web Development Setup
1. Clone the repository and navigate into the directory:
   ```bash
   git clone https://github.com/amirthn6533/pizza-italia-menu.git
   cd pizza-italia-menu
   ```
2. Run or test locally:
   ```bash
   # Using Python simple server:
   python -m http.server 8080
   # Or using Node if package.json is present:
   npm install && npm test
   ```


## Code Style & Standards
- Write clean, documented, and testable code.
- Add Google/Sphinx style docstrings to non-trivial functions and classes.
- Ensure all CI/CD checks pass before requesting review.
