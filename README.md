DevReview – Code Review Automation for Developers
# Code-Review-System
a python project with flask and devops for code review

File Structure 

code-review-automator/
├── app.py                 # Flask web app
├── analyzer.py            # Clone & analyze repos
├── templates/
│   └── index.html         # Frontend
├── static/
│   └── style.css          # Optional styling
├── test_app.py            # Simple test for Flask route
├── requirements.txt       # Flask, coverage, etc
├── Dockerfile             # Container build
├── .flake8                # Linting rules
├── .github/
│   └── workflows/
│       └── ci.yml         # GitHub Actions pipeline
├── fly.toml               # config file
└── README.md              # Docs
