# learn-genai

A repository for learning and experimenting with Generative AI concepts and applications.

## Prerequisites

- Python 3.8 or higher
- Git
- A compatible operating system (Windows/Linux/macOS)

## Getting Started

1. Clone the repository:
```bash
git clone https://github.com/nipaul/learn-genai.git
cd learn-genai
```

2. Set up the virtual environment:

**Windows (PowerShell)**:
```powershell
python -m venv venv
.\venv\Scripts\Activate.ps1
```

**Linux/macOS**:
```bash
python3 -m venv venv
source venv/bin/activate
```

3. Install dependencies (when added):
```bash
pip install -r requirements.txt
```

## Project Structure

```
learn-genai/
├── venv/           # Virtual environment (not in git)
└── lessons      # lessons notebooks folder
    └── lesson_n      # lesson notebook
├── .gitignore     # Git ignore rules
└── README.md      # Project documentation
```

## Contributing

We welcome contributions! Here's how you can help:

1. **Fork the Repository**
   - Click the 'Fork' button at the top right of this page
   - Clone your fork locally

2. **Create a Branch**
   ```bash
   git checkout -b feature/your-feature-name
   # or
   git checkout -b fix/your-fix-name
   ```

3. **Make Your Changes**
   - Write clean, documented code
   - Follow PEP 8 style guidelines for Python code
   - Add tests if applicable
   - Update documentation as needed

4. **Test Your Changes**
   - Ensure all tests pass
   - Verify your changes work as expected

5. **Commit Your Changes**
   ```bash
   git add .
   git commit -m "Brief description of your changes"
   ```

6. **Push to Your Fork**
   ```bash
   git push origin feature/your-feature-name
   ```

7. **Submit a Pull Request**
   - Go to the [Pull requests](https://github.com/nipaul/learn-genai/pulls) page
   - Click 'New Pull Request'
   - Select your fork and branch
   - Add a clear title and description
   - Submit the pull request

## Reporting Issues

If you find a bug or have a suggestion for improvement:

1. First, check if the issue already exists in the [Issues](https://github.com/nipaul/learn-genai/issues) section

2. If not, create a new issue:
   - Click 'New Issue'
   - Use a clear, descriptive title
   - Provide detailed information:
     - Steps to reproduce (for bugs)
     - Expected behavior
     - Actual behavior
     - Screenshots (if applicable)
     - System information (OS, Python version, etc.)
     - Any relevant code snippets

3. Add appropriate labels to your issue

4. Be responsive to any follow-up questions

## Development Environment Setup

1. Ensure you have activated the virtual environment (see Getting Started)

2. Install development dependencies (when added):
   ```bash
   pip install -r requirements-dev.txt
   ```

3. Set up pre-commit hooks (if implemented):
   ```bash
   pre-commit install
   ```

## Code Style Guidelines

- Follow [PEP 8](https://peps.python.org/pep-0008/) for Python code
- Use meaningful variable and function names
- Add docstrings to functions and classes
- Comment complex logic
- Keep functions focused and concise

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For additional questions or concerns, please open an issue in the repository.

---
Project maintained by [@nipaul](https://github.com/nipaul)