# Contributing to Charulekh Prakashan

First off, thank you for considering contributing to Charulekh Prakashan! It's people like you that make this project better for everyone.

## Code of Conduct

This project and everyone participating in it is governed by our [Code of Conduct](CODE_OF_CONDUCT.md). By participating, you are expected to uphold this code.

## How Can I Contribute?

### Reporting Bugs

Before creating bug reports, please check existing issues to avoid duplicates. When you create a bug report, include as many details as possible:

- **Use a clear and descriptive title**
- **Describe the exact steps to reproduce the problem**
- **Provide specific examples** to demonstrate the steps
- **Describe the behavior you observed** and what you expected
- **Include screenshots** if applicable
- **Include browser and OS information**

### Suggesting Enhancements

Enhancement suggestions are tracked as GitHub issues. When creating an enhancement suggestion:

- **Use a clear and descriptive title**
- **Provide a detailed description** of the suggested enhancement
- **Explain why this enhancement would be useful**
- **List examples** of how it would be used

### Pull Requests

1. **Fork the repository** and create your branch from `main`
2. **Make your changes** following our coding standards
3. **Test your changes** thoroughly
4. **Update documentation** if needed
5. **Commit your changes** with clear, descriptive messages
6. **Push to your fork** and submit a pull request

## Development Guidelines

### Coding Standards

#### HTML
- Use semantic HTML5 elements
- Maintain proper indentation (2 or 4 spaces consistently)
- Include alt text for all images
- Use meaningful class and ID names
- Ensure accessibility (ARIA labels where needed)

#### CSS
- Follow BEM naming convention where applicable
- Keep selectors simple and maintainable
- Use CSS variables for colors and common values
- Comment complex CSS rules
- Ensure responsive design (mobile-first approach)

#### JavaScript
- Use ES6+ features where appropriate
- Write clean, readable code with meaningful variable names
- Add comments for complex logic
- Avoid global variables
- Handle errors gracefully

### Commit Messages

- Use present tense ("Add feature" not "Added feature")
- Use imperative mood ("Move cursor to..." not "Moves cursor to...")
- Limit first line to 72 characters
- Reference issues and pull requests when relevant

Examples:
```
Add user authentication feature
Fix navigation menu on mobile devices
Update README with installation instructions
```

### Branch Naming

- `feature/description` - for new features
- `fix/description` - for bug fixes
- `docs/description` - for documentation updates
- `refactor/description` - for code refactoring

Examples:
```
feature/add-shopping-cart
fix/mobile-menu-overflow
docs/update-readme
refactor/optimize-images
```

## Project Structure

Please maintain the existing project structure:

```
charulekh-prakashan/
├── assets/
│   ├── css/        # Stylesheets
│   ├── img/        # Images
│   ├── js/         # JavaScript files
│   └── documents/  # Documentation
├── *.html          # HTML pages
└── ...
```

## Testing

Before submitting a pull request:

1. Test on multiple browsers (Chrome, Firefox, Safari, Edge)
2. Test on different screen sizes (mobile, tablet, desktop)
3. Validate HTML using [W3C Validator](https://validator.w3.org/)
4. Check CSS using [CSS Validator](https://jigsaw.w3.org/css-validator/)
5. Ensure no console errors in browser DevTools

## Questions?

Feel free to open an issue with the `question` label if you have any questions about contributing.

## Recognition

Contributors will be recognized in our README.md file and release notes.

Thank you for contributing! 🙏
