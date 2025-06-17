# Contributing to DataLineagePy

Thank you for your interest in contributing to DataLineagePy! This project aims to make data lineage tracking accessible to everyone.

## 🚀 Quick Start

### Development Setup

1. **Fork the repository**

   ```bash
   # Fork on GitHub, then clone your fork
   git clone https://github.com/yourusername/DataLineagePy.git
   cd DataLineagePy
   ```

2. **Set up development environment**

   ```bash
   # Create virtual environment
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate

   # Install in development mode
   pip install -e ".[dev]"
   ```

3. **Run tests to verify setup**
   ```bash
   pytest tests/ -v
   ```

## 🛠️ Making Changes

### Before You Start

- Check existing [issues](https://github.com/Arbaznazir/DataLineagePy/issues) and [pull requests](https://github.com/Arbaznazir/DataLineagePy/pulls)
- For new features, please open an issue first to discuss the approach

### Development Workflow

1. **Create a feature branch**

   ```bash
   git checkout -b feature/your-feature-name
   ```

2. **Make your changes**

   - Write clean, readable code
   - Follow existing code style and patterns
   - Add tests for new functionality
   - Update documentation as needed

3. **Test your changes**

   ```bash
   # Run tests
   pytest tests/

   # Check code formatting (if black is installed)
   black --check .

   # Run specific test categories
   pytest tests/test_basic_functionality.py -v
   ```

4. **Commit your changes**

   ```bash
   git add .
   git commit -m "feat: add your feature description"
   ```

5. **Push and create pull request**
   ```bash
   git push origin feature/your-feature-name
   # Then create PR on GitHub
   ```

## 📝 Code Guidelines

### Code Style

- Follow [PEP 8](https://pep8.org/) Python style guide
- Use descriptive variable and function names
- Add type hints where appropriate
- Write docstrings for public functions and classes

### Testing

- Add tests for all new functionality
- Ensure existing tests continue to pass
- Aim for good test coverage of new code
- Use descriptive test names that explain what is being tested

### Documentation

- Update relevant documentation for new features
- Add examples to demonstrate usage
- Keep README.md and other docs up to date

## 🔧 Development Tips

### Running Specific Tests

```bash
# Run all tests
pytest

# Run specific test file
pytest tests/test_basic_functionality.py

# Run tests with verbose output
pytest -v

# Run tests matching a pattern
pytest -k "test_dataframe"
```

### Building Documentation Locally

```bash
# If using sphinx or similar (future enhancement)
cd docs/
make html
```

### Performance Testing

```bash
# Run performance benchmarks
python tests/test_benchmark_suite.py
```

## 🎯 Areas for Contribution

### High Priority

- **New Connectors**: Database connectors (MongoDB, Snowflake, etc.)
- **Performance Optimizations**: Memory usage, speed improvements
- **Documentation**: More examples and tutorials
- **Testing**: Additional test coverage and edge cases

### Medium Priority

- **Visualization Enhancements**: New chart types, better layouts
- **Integration Examples**: Jupyter notebooks, real-world scenarios
- **Error Handling**: Better error messages and recovery
- **Configuration Options**: More customization capabilities

### Future Enhancements

- **Apache Spark Integration**: Native Spark DataFrame support
- **Real-time Streaming**: Enhanced Kafka and streaming support
- **Cloud Integrations**: Better cloud storage connectors
- **ML Pipeline Support**: Integration with ML frameworks

## 🐛 Reporting Issues

### Bug Reports

When reporting bugs, please include:

- Python version and operating system
- DataLineagePy version
- Minimal code example that reproduces the issue
- Full error message and stack trace
- Expected vs actual behavior

### Feature Requests

For new features, please provide:

- Clear description of the feature
- Use case and motivation
- Proposed API or interface (if applicable)
- Any implementation ideas

## 📋 Pull Request Process

1. **Ensure tests pass**: All existing tests must continue to pass
2. **Add tests**: New functionality should include appropriate tests
3. **Update documentation**: Add or update docs for new features
4. **Describe changes**: Write clear PR description explaining what and why
5. **Link issues**: Reference any related GitHub issues

### PR Review Process

- Maintainer will review PRs within a few days
- Address any feedback or requested changes
- Once approved, maintainer will merge the PR

## 🌟 Recognition

Contributors will be:

- Listed in the project's contributors section
- Credited in release notes for significant contributions
- Invited to join the project as a maintainer (for ongoing contributors)

## 💬 Getting Help

- **GitHub Issues**: For bugs and feature requests
- **Discussions**: For questions and general discussion
- **Email**: Contact arbaznazir4@gmail.com for complex topics

## 📃 License

By contributing to DataLineagePy, you agree that your contributions will be licensed under the same MIT License that covers the project.

---

## 🙏 Thank You

Every contribution, no matter how small, helps make DataLineagePy better for the entire data engineering community. Thank you for being part of this project!

**Happy coding!** 🚀
