# Getting Started with GitHub Copilot

Welcome to the **Getting Started with GitHub Copilot** skills repository! This repository provides a hands-on learning experience with GitHub Copilot, an AI-powered coding assistant.

## About This Repository

This repository contains a sample FastAPI application for **Mergington High School Activities**, which allows students to view and sign up for extracurricular activities. The application serves as a practical project for learning how to use GitHub Copilot features.

## Sample Application

The repository includes a simple web application built with FastAPI that provides:

- A RESTful API for viewing extracurricular activities
- Student signup functionality for activities
- Static web interface for interacting with the API

### Technologies Used

- **FastAPI**: Modern web framework for building APIs with Python
- **Uvicorn**: ASGI server for running the application
- **Python**: Programming language

## Getting Started

### Prerequisites

- Python 3.7+
- pip (Python package installer)

### Installation

1. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

2. Navigate to the `src` directory:

   ```bash
   cd src
   ```

3. Run the application:

   ```bash
   python app.py
   ```

4. Open your browser and navigate to:
   - Application: http://localhost:8000
   - API Documentation: http://localhost:8000/docs
   - Alternative Documentation: http://localhost:8000/redoc

## Learning GitHub Copilot

This repository is part of the GitHub Skills learning path. Through this exercise, you'll learn to:

- Use **Inline Suggestions** for code completion
- Leverage **Copilot Chat** for asking coding questions
- Apply **Copilot Edit Mode** for making code changes
- Utilize **Copilot Agent Mode** for autonomous task completion

### Resources

- [GitHub Copilot Documentation](https://docs.github.com/en/copilot)
- [GitHub Copilot Features](https://docs.github.com/en/copilot/about-github-copilot/github-copilot-features)
- [GitHub Skills](https://skills.github.com)

## Project Structure

```
.
├── src/
│   ├── app.py          # Main FastAPI application
│   ├── static/         # Static web assets
│   └── README.md       # Application-specific documentation
├── requirements.txt    # Python dependencies
└── README.md          # This file
```

## Contributing

This is a learning repository. Feel free to experiment with the code and practice using GitHub Copilot!

## License

&copy; 2025 GitHub &bull; [MIT License](https://gh.io/mit)

