# Contributions

Thank you for considering contributing to our project! Here you will find all the necessary information to start collaborating effectively.

## Prerequisites

Before making your first contribution, make sure you meet the following requirements:

**Required tools:**

- [Git](https://git-scm.com/) and [GitHub](https://github.com) account
- Code editor (we recommend [Visual Studio Code](https://code.visualstudio.com))

**Essential documentation:**

- [Readme](../README.md), [User Guide](USER_GUIDE.md) and [Development Guide](DEVELOPMENT_GUIDE.md)
- [Code of Conduct](CODE_OF_CONDUCT.md) and [Security](SECURITY.md)

**Basic knowledge:**

- Git, Markdown and project objectives ([Proposal](PROPOSAL.md))

## How Can You Contribute?

You can collaborate in the following areas:

- **Bug Fixes**: Help improve project stability by fixing existing bugs. You can find a list of known bugs in the [issues](https://github.com/sergio-ridaura/project-kickstart/issues) section tagged as `bug`.
- **New Features**: Do you have an idea for a new feature? Review the [issues](https://github.com/sergio-ridaura/project-kickstart/issues) tagged as `enhancement` to see if your idea is already under discussion. If not, feel free to open a new issue to propose it!
- **Documentation Improvements**: Good documentation is key to any project. If you find areas that can be improved or expanded in the [Readme](../README.md) or other documents in the `docs` folder, your contributions are welcome.
- **Code Review**: Collaborate by reviewing open [Pull Requests](https://github.com/sergio-ridaura/project-kickstart/pulls). Offering a second opinion and suggesting improvements is an excellent way to ensure code quality.

## Workflow

The [Development Guide](DEVELOPMENT_GUIDE.md) describes the project's general methodology. The specific flow for contributors is detailed below:

1. **Fork the repository**.
2. Before you start, **open an [issue](https://github.com/sergio-ridaura/project-kickstart/issues)** to describe your proposal. This allows the team to discuss the contribution and ensure it aligns with the project's goals before you invest time in development.
3. **Create a branch for your contribution**, from the `staging` branch, following the branch convention:

   ```bash
   # Switch to the staging branch
   git checkout staging

   # Create new branch from staging
   git checkout -b type/task-name
   ```

4. **This new task, which is not in the plan**, add it to the [Action Plan](ACTION_PLAN.md) and adapt the corresponding metrics (number of tasks, estimated hours, etc.).
5. **Make the necessary changes**.
6. **Before committing the changes**, make sure your code follows the project standards, update the status of the completed task document and action plan (mark as completed, update hours, acceptance criteria and plan metrics).
7. **Commit your changes** following the message convention:
   ```bash
   # Commit changes with task name
   git commit -m "type:task-name"
   ```
8. **Push the changes to your fork**:
   ```bash
   # Push branch to GitHub fork
   git push origin type/task-name
   ```
9. **Open a Pull Request** from your branch to the `staging` branch of the main repository.

### Branch Flow

To ensure code stability and facilitate parallel work, we follow an adapted Git Flow branch flow model:

```
main (stable production)
└── staging (preparation for production)
    ├── feat/authentication-system
    ├── fix/form-validation-error
    └── docs/installation-guide
```

- **`main`**: Contains the production version of the project. It should always be stable and ready to be deployed.
- **`staging`**: It is the pre-production branch. It continuously integrates all functionalities and fixes.
- **`type/task-name`**: These are development branches, created from `staging`. Each new feature, fix or change is developed in its own branch to isolate the work.

### Branch Names

Use the format `type/task-name`, where `type` can be:

- `feat`: New functionality.
- `fix`: Bug fix.
- `docs`: Documentation changes.
- `style`: Formatting adjustments (spaces, commas, etc.).
- `refactor`: Refactoring of existing code.
- `test`: Add or modify tests.
- `config`: Configuration file changes.
- `chore`: Maintenance tasks.

### Commit Messages

Commit messages should follow the format `type: task-name`, using the same types as branches. This facilitates reading the history and automating tasks.

**Examples**:

```bash
feat: authentication-system
fix: form-validation-error
docs: installation-guide
```

## Code Quality

To maintain code consistency and readability, it is essential to follow these guidelines:

- **Code Style**: This project uses [Prettier](https://prettier.io/) to format Markdown code. We recommend using the [Prettier - Code formatter](https://marketplace.visualstudio.com/items?itemName=esbenp.pretter-vscode) extension for Visual Studio Code to automatically format files.
- **Consistency**: When editing documentation, please follow the style and structure of existing files. This includes how headers, lists and other Markdown elements are used.

## Reviews and Approvals

- The developer must verify locally that the acceptance criteria are met and that no existing functionality has been broken.
- Maintainers will review your Pull Request as soon as possible.
- If adjustments are needed, you will be notified through comments on the Pull Request.

## Additional Resources

- [Conventional Commits](https://www.conventionalcommits.org/)
- [Markdown Guide](https://www.markdownguide.org/)
- [GitHub Flow](https://guides.github.com/introduction/flow/)
- [About pull requests](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests)

## Acknowledgements

Thank you for your interest in contributing to this project! Your participation is valuable and helps improve the quality and functionality of the project. If you have any questions or need help, feel free to contact the project maintainers.
