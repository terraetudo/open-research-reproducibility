````markdown
# Open Research and Reproducibility Workshop

This repository contains the Quarto materials for the Open Research and Reproducibility workshop.

## Current version

**Version:** 1.0  
**Last updated:** 28 May 2026

Update the version number when there are substantial changes to the workshop structure, content, exercises or resources.

Suggested versioning:

- Small text edits or typo corrections: keep the same version.
- New resource, small section revision or minor exercise change: increase to 1.1, 1.2, etc.
- Major restructuring or new workshop version: increase to 2.0.

## Editing the materials

Edit the `.qmd` files in RStudio.

Before committing changes, render the website locally to check that everything works:

```bash
quarto render
````

Check the rendered website before pushing changes.

## Saving changes to GitHub

After finishing edits and checking the rendered materials, run the following in the Terminal in RStudio:

```bash
git status
git add .
git commit -m "Update workshop materials"
git push
```

Use a more specific commit message where possible, for example:

```bash
git commit -m "Add onboarding and offboarding checklists"
```

## Suggested workflow

1. Edit the Quarto files.
2. Run `quarto render`.
3. Check the rendered website.
4. Run `git status`.
5. Add, commit and push the changes.
6. Update the version number if the changes are substantial.

## Files to check before publishing

* Homepage or introduction page
* Workshop schedule
* Resource boxes
* Links and references
* Exercises or activities
* Any figures, captions and credits
* README
* Version number and last updated date

## Notes to self

After finishing edits in Quarto, always run:

```bash
quarto render
git status
git add .
git commit -m "Update workshop materials"
git push
```

```
```
