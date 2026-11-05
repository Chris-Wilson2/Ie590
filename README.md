# Ie590
# IE590 – GitHub Guide

## 1. Clone the Repository (First Time Only)

Download the repository to your computer:

```bash
git clone https://github.com/YOUR_USERNAME/ie590.git
cd ie590
```

Replace `YOUR_USERNAME` with the repository owner's GitHub username.

## 2. Pull the Latest Code

Before making changes, get the latest version:

```bash
git pull origin main
```

## 3. Save and Push Your Changes

After editing and saving your files, run:

```bash
git add .
git commit -m "Description of changes"
git push origin main
```

- `git add .` — Selects your changed files.
- `git commit -m "message"` — Saves your changes locally.
- `git push origin main` — Uploads your changes to GitHub.

## 4. Basic Workflow

**Every time you work on the project:**

1. Pull the latest code.
2. Make and save your changes.
3. Add, commit, and push your changes.

```bash
git pull origin main
git add .
git commit -m "Updated code"
git push origin main
```

## 5. Team Reminders

- Always pull before making changes.
- Use clear commit messages.
  
- Coordinate with teammates when editing the same files.
- If Git reports a conflict, resolve it before pushing.
