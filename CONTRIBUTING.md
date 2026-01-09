# Contributing to Coast FIRE Calculator

First off, thank you for considering contributing to Coast FIRE Calculator! It's people like you that make this tool better for the entire FIRE community.

## 🌟 How Can I Contribute?

### Reporting Bugs

Before creating bug reports, please check the [issue list](https://github.com/YOUR_ACTUAL_USERNAME/coast-fire-calculator/issues) to see if the problem has already been reported.

When you create a bug report, please include:
- **Clear descriptive title**
- **Steps to reproduce** the behavior
- **Expected behavior** and what actually happened
- **Screenshots** if applicable
- **Browser and OS** information

**Example Bug Report:**
```markdown
**Bug**: Negative portfolio values showing after retirement

**Steps to Reproduce:**
1. Set current age to 35
2. Set retirement age to 65
3. Set safe withdrawal rate to 5%
4. Set expected return to 6%

**Expected**: Portfolio should remain positive
**Actual**: Portfolio shows negative values at age 75

**Browser**: Chrome 120.0 on macOS 14.0
```

### Suggesting Enhancements

Enhancement suggestions are tracked as GitHub issues. When creating an enhancement suggestion, please include:
- **Clear descriptive title**
- **Detailed description** of the proposed functionality
- **Why this enhancement would be useful** to most users
- **Possible implementation** approach (optional)

**Ideas for Enhancements:**
- Add Monte Carlo simulation
- Multi-currency support
- Export to PDF functionality
- Mobile app version
- Scenario comparison side-by-side
- Tax calculation features
- Social Security integration

### Pull Requests

1. **Fork the repo** and create your branch from `main`
2. **Make your changes** with clear, commented code
3. **Test thoroughly** across different browsers
4. **Update documentation** if you change functionality
5. **Write clear commit messages**
6. **Submit the pull request** with a comprehensive description

## 💻 Development Guidelines

### Code Style

- **HTML**: Use semantic HTML5 elements
- **CSS**: Keep styles organized, use BEM naming if adding classes
- **JavaScript**: 
  - Use clear, descriptive variable names
  - Add comments for complex logic
  - Follow existing code patterns
  - Avoid external dependencies if possible

**JavaScript Style Example:**
```javascript
// Good
function calculateCoastFIRETarget(requiredPortfolio, realReturn, yearsToRetirement) {
    return requiredPortfolio / Math.pow(1 + realReturn / 100, yearsToRetirement);
}

// Avoid
function calc(rp, rr, ytr) {
    return rp / Math.pow(1 + rr / 100, ytr);
}
```

### Testing Checklist

Before submitting, please test:
- [ ] Calculator produces correct results
- [ ] Chart renders properly
- [ ] Table displays all data correctly
- [ ] All input fields validate properly
- [ ] Works in Chrome, Firefox, Safari, Edge
- [ ] Works on mobile devices
- [ ] No console errors
- [ ] No broken links in documentation

### Documentation

If you change functionality:
- Update relevant markdown files in `/docs`
- Update README.md if needed
- Add inline code comments for complex logic
- Update examples if behavior changes

## 📝 Documentation Style Guide

When editing documentation:
- Use clear, simple language
- Include practical examples
- Use headers to organize content
- Add links to related sections
- Keep paragraphs short and scannable
- Use bullet points and lists appropriately

## 🔍 Financial Calculation Accuracy

**This is critical**: All financial calculations must be:
- Mathematically correct
- Based on established financial principles
- Thoroughly tested with edge cases
- Conservative in assumptions

If you're adding/modifying calculations:
1. Cite your sources (research papers, textbooks, etc.)
2. Explain the methodology in comments
3. Provide test cases in your PR
4. Consider edge cases (negative returns, extreme values, etc.)

## 🌍 Internationalization

If adding features for international users:
- Keep currency formatting flexible
- Consider date format differences
- Use locale-aware number formatting
- Document any country-specific assumptions

## 🎨 Design Principles

Maintain these principles:
- **Simplicity**: Don't add complexity without clear benefit
- **Privacy**: Never add tracking or data collection
- **Accessibility**: Keep the tool usable by everyone
- **Performance**: Keep the calculator fast and lightweight
- **Education**: Help users understand, don't just calculate

## 📮 Submitting Changes

### Commit Messages

Use clear, descriptive commit messages:
- **Good**: `Add Monte Carlo simulation feature with 10,000 iterations`
- **Good**: `Fix portfolio value calculation for negative returns`
- **Avoid**: `Update code`
- **Avoid**: `Fixed stuff`

### Pull Request Process

1. **Update the README.md** with details of changes if applicable
2. **Update documentation** in `/docs` if you change functionality
3. **Add your name** to contributors if it's your first contribution
4. **Request review** from maintainers
5. **Be responsive** to feedback and questions

## ❓ Questions?

Feel free to:
- Open an issue with the "question" label
- Start a discussion in GitHub Discussions
- Reach out to maintainers

## 🏆 Recognition

Contributors are recognized in:
- README.md acknowledgments section
- GitHub contributors page
- Release notes for significant contributions

## 📜 Code of Conduct

### Our Pledge

We pledge to make participation in our project a harassment-free experience for everyone, regardless of age, body size, disability, ethnicity, gender identity and expression, level of experience, nationality, personal appearance, race, religion, or sexual identity and orientation.

### Our Standards

**Positive behavior includes:**
- Using welcoming and inclusive language
- Being respectful of differing viewpoints
- Gracefully accepting constructive criticism
- Focusing on what is best for the community
- Showing empathy towards others

**Unacceptable behavior includes:**
- Trolling, insulting/derogatory comments, personal attacks
- Public or private harassment
- Publishing others' private information without permission
- Other conduct which could reasonably be considered inappropriate

### Enforcement

Instances of abusive, harassing, or otherwise unacceptable behavior may be reported by opening an issue or contacting maintainers directly. All complaints will be reviewed and investigated promptly and fairly.

## 🙏 Thank You!

Your contributions to improve financial education and help people achieve financial independence are greatly appreciated!

---

**Questions about contributing?** Feel free to ask in [GitHub Discussions](https://github.com/YOUR_ACTUAL_USERNAME/coast-fire-calculator/discussions)!