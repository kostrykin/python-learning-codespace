<<<<<<< HEAD
Test
=======
# [python-learning-codespace](https://github.com/kostrykin/python-learning-codespace)

This repository provides a template for GitHub Codespaces to be used in [*Lessons on Image Analysis using Python and Jupyter Notebooks* in Molecular Biotechnology](https://github.com/users/kostrykin/projects/4).

**The codespace is configured as follows:**
- VS Code with `ms-toolsai.jupyter` extension
- Python 3.12 (should be selected as default Jupyter kernel, doesn't work reliably)
- Common Python packages for image analysis (numpy, scipy, scikit-image, tifffile, pillow)

Update `.devcontainer/Dockerfile` to add Python packages to be installed.

Dotfiles `**/.*`, Markdown files `**/*.md` are some other auxiliary files (e.g., LICENSE) are hidden in the VS Code file manager. Pylance is disabled.

**To update your existing repository with this template:**

Install the auto-updater workflow:
```bash
mkdir -p .github/workflows && wget https://github.com/kostrykin/python-learning-codespace/raw/master/.github/workflows/pull_upstream.yml -O .github/workflows/pull_upstream.yml
```

Run the workflow from the web interface and merge the created pull request.
>>>>>>> upstream/master
