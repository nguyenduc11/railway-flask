# Procfile
web: gunicorn app:app

# railway.toml
[build]
builder = "NIXPACKS"

[deploy]
startCommand = "gunicorn app:app"
healthcheckPath = "/"
restartPolicyType = "ON_FAILURE"

# .gitignore
venv/
*.pyc
__pycache__/
instance/
.pytest_cache/
.coverage
htmlcov/
dist/
build/
*.egg-info/
.idea/
*.swp
*~