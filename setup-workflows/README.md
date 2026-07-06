# Workflow setup (one-time)

These workflow files couldn't be pushed automatically because the CLI token doesn't have `workflow` scope. To activate the interactive grader:

## Option A: run this locally
```bash
gh auth refresh -s workflow
mkdir -p .github/workflows
mv setup-workflows/*.yml .github/workflows/
git rm -r setup-workflows
git add .github/workflows
git commit -m "Enable step-progression workflow"
git push
```

## Option B: create via GitHub UI
Copy each `.yml` file into a new file at `.github/workflows/<name>.yml` through the GitHub web editor. That path enables workflow scope automatically.

Once workflows are in `.github/workflows/`, learners will get auto-graded advancement.
