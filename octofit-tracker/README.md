OctoFit Tracker (scaffold)

This folder contains the backend/frontend scaffolding for the OctoFit Tracker project.

Backend quick start (from repo root, do NOT change directories in agent commands — use absolute paths):

1) Create python virtual environment

```bash
python3 -m venv /workspaces/skills-build-applications-w-copilot-agent-mode/octofit-tracker/backend/venv
```

2) Activate and install requirements

```bash
source /workspaces/skills-build-applications-w-copilot-agent-mode/octofit-tracker/backend/venv/bin/activate
pip install -r /workspaces/skills-build-applications-w-copilot-agent-mode/octofit-tracker/backend/requirements.txt
```

3) (Optional) Create Django project skeleton after installing packages:

```bash
django-admin startproject octofit_tracker /workspaces/skills-build-applications-w-copilot-agent-mode/octofit-tracker/backend/octofit_tracker
```

Ports to forward later: 8000 (public), 3000 (public), 27017 (private)

Notes:
- Use Django ORM for data migration and seeding; do not run raw MongoDB scripts.
- See repository README and the `.github/instructions` files for additional setup guidance.
