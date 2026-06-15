# GitHub Publishing Checklist

Use this checklist to publish Qyvaria Softwares.

## 1. Create the Repository

Recommended repository name:

```text
qyvaria-softwares
```

Recommended description:

```text
Qyvaria Softwares — a daily-updated collection of Windows and Linux desktop apps, optimizers, editors, installers, and data tools under Apache License 2.0.
```

Suggested topics:

```text
qyvaria
desktop-app
python
windows
linux
optimizer
zip
installer
tkinter
software-suite
apache-2-0
```

## 2. Upload Files

Upload these files first:

- README.md
- LICENSE
- NOTICE
- CONTRIBUTING.md
- SECURITY.md
- CODE_OF_CONDUCT.md
- CHANGELOG.md
- .gitignore
- .github folder

Then upload each software folder.

## 3. Add Releases

Create a GitHub Release for each ZIP package.

Suggested first release title:

```text
Qyvaria Softwares Stable Setup v0.2.0
```

Suggested first release notes:

```text
First public Qyvaria Softwares suite release.

Includes:
- AI Inspector Editor
- QTask Optimizer
- Qyvaria Zip Resizer
- SafeSpeed Optimizer

Windows and Linux setup scripts included.
Licensed under Apache License 2.0.
```

## 4. Add Screenshots

Create a folder:

```text
docs/screenshots/
```

Add screenshots for:

- Main suite
- AI Inspector Editor
- QTask Optimizer
- Qyvaria Zip Resizer
- SafeSpeed Optimizer

## 5. Add Daily Update Log

Every day, update:

```text
CHANGELOG.md
```

Use this format:

```text
## YYYY-MM-DD
- Added:
- Fixed:
- Improved:
- Tested:
```

## 6. Before Every Commit

Run:

```bash
python -m compileall .
```

If tests exist:

```bash
python -m pytest
```

## 7. Commit Message Examples

```text
Add Qyvaria Zip Resizer stable setup
Improve Linux desktop installers
Add SafeSpeed Optimizer v0.4.0
Fix Windows shortcut creation
Update daily changelog
```
