# new-project

Jira Ticket: PROM-42164

## Git Workflow Instructions

### 1. Clone the repository

```bash
git clone https://github.com/svc32GH/new-project.git
cd new-project
```

### 2. Create a development branch

```bash
git switch main
git switch -c development
```

### 3. Make changes

Create or modify project files.

### 4. Stage and commit changes

```bash
git add .
git commit -m "Add project documentation"
```

### 5. Merge development into main

```bash
git switch main
git merge development
```

### 6. Push changes to GitHub

```bash
git push origin main
```
