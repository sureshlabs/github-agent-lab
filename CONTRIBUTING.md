# Contributing Guidelines

Thank you for considering contributing to **github-agent-lab**! We welcome contributions of all kinds, whether it's fixing bugs, adding features, improving documentation, or suggesting ideas.

## Getting Started

1. **Fork the repository**
   Click the **Fork** button at the top right of the repository page to create your own copy.

2. **Clone your fork**
   ```bash
   git clone https://github.com/<your-username>/github-agent-lab.git
   cd github-agent-lab
   ```

3. **Create a new branch**
   ```bash
   git checkout -b <branch-name>
   ```
   Use a descriptive name, e.g., `fix/typo-in-readme` or `feature/add-cli`.

4. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

5. **Make your changes**
   - Follow the existing code style (PEP8 for Python).
   - Write clear, concise commit messages.
   - If you add new functionality, include tests where applicable.

6. **Run the test suite** (if any)
   ```bash
   # No tests are currently defined, but run any existing checks.
   ```

7. **Commit and push**
   ```bash
   git add .
   git commit -m "Brief description of your changes"
   git push origin <branch-name>
   ```

## Submitting a Pull Request

- Navigate to the original repository and click **Pull requests** → **New pull request**.
- Select your fork and the branch you just pushed.
- Provide a descriptive title and a detailed description of what the PR does.
- Reference any related issues using `closes #<issue-number>`.
- Ensure that your PR passes any automated checks (e.g., CI) before requesting a review.

## Code Style & Guidelines

- **Python**: Follow PEP 8 guidelines. Use `black` or `flake8` if you have them configured.
- **Documentation**: Update `README.md` or other docs if your change affects usage.
- **Commit Messages**: Use the imperative mood (e.g., "Add feature X", "Fix bug Y").

## Reporting Issues

If you encounter a bug or have a suggestion, please open an issue with:
- A clear title.
- A description of the problem or feature request.
- Steps to reproduce (for bugs).
- Any relevant logs or screenshots.

## License

By contributing, you agree that your contributions will be licensed under the same MIT License as the project.

---

Thank you for your contributions!
