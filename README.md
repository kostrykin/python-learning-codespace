# [python-learning-codespace](https://github.com/kostrykin/python-learning-codespace)

This repository serves as a template for *Lessons on Image Analysis using Python and Jupyter Notebooks* inside GitHub Codespaces.

**The codespace is configured as follows:**
- VS Code with `ms-toolsai.jupyter` extension
- Python 3.12 (should be selected as default Jupyter kernel, doesn't work all the time)
- Common Python packages for image analysis (numpy, scipy, scikit-image, tifffile, pillow)

Update `.devcontainer/Dockerfile` to add Python packages to be installed.

Dotfiles `**/.*`, Markdown files `**/*.md` are some other auxiliary files (e.g., LICENSE) are hidden in the VS Code file manager. Pylance is disabled.
