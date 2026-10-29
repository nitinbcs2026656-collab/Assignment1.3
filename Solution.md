# Assignment 1.3 — Terminal & Developer Workflow

### 1. Terminal Commands

Run these commands in the **VS Code terminal (Windows PowerShell)**:

```powershell
mkdir web-development-practice
cd web-development-practice

mkdir week-1, week-2, week-3

New-Item week-1/index.html -ItemType File
New-Item week-2/index.html -ItemType File
New-Item week-3/index.html -ItemType File

code .
```

### 2. Navigation, Renaming, and Deleting

```powershell
cd week-1
cd ..
Rename-Item week-3 week-4
Remove-Item week-4 -Recurse -Force
```

**Note:** The last two commands rename and then delete `week-3`. Run them only to practice; recreate `week-3` afterward if needed.

### 3. Final Folder Structure

```text
web-development-practice/
├── week-1/
│   └── index.html
├── week-2/
│   └── index.html
└── week-3/
    └── index.html
```

### Submission
Submit the terminal commands and a screenshot of the final folder structure in VS Code.