# Contributing to KEC × GUVI Website

Thank you for your interest in contributing to the KEC × GUVI collaboration website! We welcome contributions from the community.

## 🚀 Getting Started

### Prerequisites
- Git installed on your machine
- A modern web browser (Chrome, Firefox, Safari, or Edge)
- Basic knowledge of HTML, CSS, and JavaScript
- A text editor or IDE (VS Code recommended)

### Setting Up Your Development Environment

1. **Fork the repository**
   ```bash
   # Click the "Fork" button on GitHub
   ```

2. **Clone your fork**
   ```bash
   git clone https://github.com/YOUR_USERNAME/Devops_coaching.git
   cd Devops_coaching
   ```

3. **Create a new branch**
   ```bash
   git checkout -b feature/your-feature-name
   ```

4. **Start the development server**
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Or using Node.js
   npx http-server -p 8000
   ```

5. **Open in browser**
   ```
   http://localhost:8000
   ```

## 📝 How to Contribute

### Reporting Bugs

If you find a bug, please create an issue with:
- Clear title and description
- Steps to reproduce
- Expected vs actual behavior
- Screenshots (if applicable)
- Browser and OS information

### Suggesting Enhancements

We welcome feature suggestions! Please create an issue with:
- Clear description of the enhancement
- Use case and benefits
- Mockups or examples (if applicable)

### Code Contributions

#### Before You Start
- Check existing issues and pull requests
- Discuss major changes in an issue first
- Follow our coding standards

#### Making Changes

1. **Write clean, readable code**
   - Use meaningful variable and function names
   - Add comments for complex logic
   - Follow existing code style

2. **Test your changes**
   - Test in multiple browsers (Chrome, Firefox, Safari, Edge)
   - Test responsive design on different screen sizes
   - Verify all interactive features work

3. **Commit your changes**
   ```bash
   git add .
   git commit -m "feat: add new feature description"
   ```

   **Commit Message Format:**
   - `feat:` - New feature
   - `fix:` - Bug fix
   - `docs:` - Documentation changes
   - `style:` - Code style changes (formatting, etc.)
   - `refactor:` - Code refactoring
   - `test:` - Adding tests
   - `chore:` - Maintenance tasks

4. **Push to your fork**
   ```bash
   git push origin feature/your-feature-name
   ```

5. **Create a Pull Request**
   - Go to the original repository
   - Click "New Pull Request"
   - Select your branch
   - Fill in the PR template
   - Wait for review

## 🎨 Coding Standards

### HTML
- Use semantic HTML5 elements
- Maintain proper indentation (2 spaces)
- Include alt text for images
- Use meaningful IDs and classes
- Follow accessibility best practices

### CSS
- Use CSS variables for colors and common values
- Organize styles logically (layout, typography, components)
- Use mobile-first responsive design
- Avoid inline styles
- Use meaningful class names (BEM methodology preferred)

### JavaScript
- Use ES6+ features
- Avoid global variables
- Use `const` and `let` instead of `var`
- Add error handling
- Comment complex logic
- Use meaningful function and variable names

### File Organization
```
GUVI/
├── index.html          # Main HTML file
├── styles.css          # All styles
├── script.js           # All JavaScript
├── README.md           # Documentation
├── SECURITY.md         # Security policy
├── CONTRIBUTING.md     # This file
└── .github/
    └── workflows/      # GitHub Actions
```

## ✅ Pull Request Checklist

Before submitting your PR, ensure:
- [ ] Code follows the project's coding standards
- [ ] All tests pass (if applicable)
- [ ] Changes are tested in multiple browsers
- [ ] Responsive design works on mobile, tablet, and desktop
- [ ] No console errors or warnings
- [ ] Documentation is updated (if needed)
- [ ] Commit messages follow the format
- [ ] PR description clearly explains the changes

## 🔒 Security

- Never commit sensitive data (API keys, passwords, etc.)
- Review the [SECURITY.md](SECURITY.md) file
- Report security vulnerabilities privately
- Use HTTPS for external resources

## 🧪 Testing

### Manual Testing
1. Open the website in different browsers
2. Test all interactive features:
   - Navigation menu (desktop and mobile)
   - Smooth scrolling
   - Form validation
   - Hover effects
3. Test responsive design:
   - Mobile (< 768px)
   - Tablet (768px - 1199px)
   - Desktop (≥ 1200px)

### Automated Testing
- GitHub Actions will run automatically on PR
- Security checks will be performed
- HTML/CSS validation will be done

## 📚 Resources

- [HTML Best Practices](https://github.com/hail2u/html-best-practices)
- [CSS Guidelines](https://cssguidelin.es/)
- [JavaScript Style Guide](https://github.com/airbnb/javascript)
- [Web Accessibility](https://www.w3.org/WAI/fundamentals/accessibility-intro/)

## 💬 Communication

- **Issues**: For bug reports and feature requests
- **Pull Requests**: For code contributions
- **Discussions**: For general questions and ideas

## 📄 License

By contributing, you agree that your contributions will be part of the project under the same terms.

## 🙏 Thank You!

Your contributions make this project better! We appreciate your time and effort.

---

**Questions?** Feel free to open an issue or reach out to the maintainers.

**Happy Contributing! 🎉**
