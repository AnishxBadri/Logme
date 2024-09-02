# Contributing to LogMe 

## Getting Started

- Make sure you have a [GitHub account](https://github.com/signup/free)
- Submit a ticket for your issue, assuming one does not already exist.
  - Clearly describe the issue including steps to reproduce when it is a bug.
  - Make sure you fill in the earliest version that you know has the issue.

## Making Changes

1. Fork the repository on GitHub.
2. Clone the forked repository to your machine.
3. Create a new branch from `main` for your changes:
   ```
   git checkout -b feature/your-feature-name main
   ```
   Use a clear and descriptive branch name.

4. Make your changes and commit them using conventional commit messages:
   ```
   git commit -m "feat: add new login functionality"
   ```
   
   Our project uses the [Conventional Commits](https://www.conventionalcommits.org/) specification. Please follow these conventions for your commit messages:

   - `feat:` for new features
   - `fix:` for bug fixes
   - `docs:` for documentation changes
   - `style:` for changes that do not affect the meaning of the code
   - `refactor:` for refactoring existing code
   - `perf:` for performance improvements
   - `test:` for adding or modifying tests
   - `chore:` for changes to the build process or auxiliary tools

5. Push your changes to your fork on GitHub:
   ```
   git push origin feature/your-feature-name
   ```

6. Submit a pull request to the main repository.

## Pull Request Process

1. Ensure any install or build dependencies are removed before the end of the layer when doing a build.
2. Update the README.md with details of changes to the interface, this includes new environment variables, exposed ports, useful file locations and container parameters.
3. Increase the version numbers in any examples files and the README.md to the new version that this Pull Request would represent. The versioning scheme we use is [SemVer](http://semver.org/).

## Coding Conventions

Start reading our code and you'll get the hang of it. We optimize for readability:

- We use Rust's official style guide. Run `rustfmt` on your code before submitting.
- We use `clippy` to catch common mistakes and improve code quality. Run `cargo clippy` before submitting your changes.
- Write documentation for new code and update documentation for changed code.

## Testing

- Write unit tests for new code.
- Run all tests before submitting a pull request.
- Ensure your changes don't break existing tests.

Thank you for contributing to LogMe!
