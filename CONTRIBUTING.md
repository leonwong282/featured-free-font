# 🤝 Contributing to Featured Free Fonts

First off, thank you for considering contributing to Featured Free Fonts! It's people like you that make high-quality typography accessible to everyone and help expand our curated collection of free commercial fonts.

## 📋 Table of Contents

- [Code of Conduct](#code-of-conduct)
- [Getting Started](#getting-started)
- [How Can I Contribute?](#how-can-i-contribute)
- [Font Submission Guidelines](#font-submission-guidelines)
- [Pull Request Process](#pull-request-process)
- [Documentation Standards](#documentation-standards)
- [License Verification](#license-verification)

## 📜 Code of Conduct

This project and everyone participating in it is governed by our [Code of Conduct](CODE_OF_CONDUCT.md). By participating, you are expected to uphold this code.

## 🚀 Getting Started

### Types of Contributions

We welcome many different types of contributions including:

- 🎨 **Font submissions** - Adding new free commercial fonts to our collection
- 🔍 **License verification** - Helping verify and update licensing information
- 📚 **Documentation improvements** - Enhancing font descriptions and usage examples
- 🐛 **Bug reports** - Reporting broken links or outdated information
- 🌍 **Translations** - Translating font descriptions and documentation
- 💡 **Feature suggestions** - Ideas for improving the collection and database

### Before Contributing

1. Check if the font is already in our [collection](https://leonwong282.notion.site/font?v=3113cedbea13433ab58465f2f47dff0a&pvs=74)
2. Verify that the font is indeed free for commercial use
3. For major changes, please open an [issue](https://github.com/leonwong282/featured-free-font/issues) first to discuss
4. Make sure your contribution aligns with our quality standards

1. **Fork the repository**
   ```bash
   # Click the "Fork" button on GitHub
   ```

2. **Clone your fork**
   ```bash
   git clone https://github.com/leonwong282/simple-beatiful-open-project-templete.git
   cd simple-beatiful-open-project-templete
   ```

3. **Add upstream remote**
   ```bash
   git remote add upstream https://github.com/leonwong282/simple-beatiful-open-project-templete.git
   ```

4. **Install dependencies**
   ```bash
   npm install
   ```

5. **Create a new branch**
   ```bash
   git checkout -b feature/your-feature-name
   # or
   git checkout -b fix/your-bug-fix
   ```

6. **Start development server**
   ```bash
   npm run dev
   ```

### Development Workflow

```bash
# Keep your fork up to date
git fetch upstream
git checkout main
git merge upstream/main

# Create a new branch for your changes
git checkout -b feature/amazing-feature

# Make your changes and commit them
git add .
git commit -m "feat: add amazing feature"

# Push to your fork
git push origin feature/amazing-feature

# Create a Pull Request on GitHub
```

## 🔄 Pull Request Process

### Before Submitting

- [ ] Code follows the project's coding standards
- [ ] Tests have been added or updated
- [ ] Documentation has been updated if necessary
- [ ] All tests pass locally
- [ ] Code has been linted and formatted
- [ ] Commit messages follow our guidelines

### PR Requirements

1. **Clear Description**: Provide a clear description of what your PR does
2. **Issue Reference**: Reference any related issues
3. **Breaking Changes**: Clearly mark any breaking changes
4. **Screenshots**: Include screenshots for UI changes
5. **Testing**: Describe how you tested your changes

### PR Template

```markdown
## Description
Brief description of changes

## Type of Change
- [ ] Bug fix (non-breaking change which fixes an issue)
- [ ] New feature (non-breaking change which adds functionality)
- [ ] Breaking change (fix or feature that would cause existing functionality to not work as expected)
- [ ] Documentation update

## Related Issue
Fixes #(issue number)

## How Has This Been Tested?
Describe the tests that you ran and how to reproduce them

## Screenshots (if applicable)
Add screenshots here

## Checklist
- [ ] My code follows the style guidelines of this project
- [ ] I have performed a self-review of my own code
- [ ] I have commented my code, particularly in hard-to-understand areas
- [ ] I have made corresponding changes to the documentation
- [ ] My changes generate no new warnings
- [ ] I have added tests that prove my fix is effective or that my feature works
- [ ] New and existing unit tests pass locally with my changes
```

## 📝 Commit Guidelines

We follow the [Conventional Commits](https://www.conventionalcommits.org/) specification.

## 🏷️ Issue and PR Labels

We use labels to categorize issues and PRs:

- `bug` - Something isn't working
- `enhancement` - New feature or request
- `documentation` - Improvements or additions to documentation
- `good first issue` - Good for newcomers
- `help wanted` - Extra attention is needed
- `priority: high` - High priority
- `priority: low` - Low priority
- `status: needs review` - Needs review
- `status: work in progress` - Work in progress

## 🎉 Recognition

Contributors will be recognized in:

- README.md contributors section
- Release notes
- GitHub contributors page
- Annual contributor highlights

## 📋 Contributor Checklist

Before your first contribution:

- [ ] Read and understand the Code of Conduct
- [ ] Set up your development environment
- [ ] Read this contributing guide thoroughly
- [ ] Join our community channels
- [ ] Look for `good first issue` labels

For each contribution:

- [ ] Create an issue or find an existing one
- [ ] Discuss your approach (for larger changes)
- [ ] Fork the repository
- [ ] Create a feature branch
- [ ] Make your changes
- [ ] Add/update tests
- [ ] Update documentation
- [ ] Run tests locally
- [ ] Create a pull request
- [ ] Respond to code review feedback

---

Thank you for contributing to Project Name! 🎉

Your contributions make this project better for everyone in the community.
