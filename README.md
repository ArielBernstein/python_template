# Python ML Project Template

This repository is a basic template for starting a Python project using VS Code, virtual environments (venv), Jupyter notebooks (via VS Code), and Git.

---

## 🚀 Start a New Project

1. Create a new repository from this template on GitHub using **"Use this template"**.

2. Open VS Code and open the project folder.  
   Then open the terminal using `Ctrl + ~`.

3. Clone the repository and enter the project directory:

```bash
git clone <REPO_URL>
cd <REPO_NAME>
```

4. Create a virtual environment:

```bash
python -m venv .venv
```

5. Activate the environment (Windows PowerShell):

```bash
.\.venv\Scripts\Activate
```

6. Install dependencies:

```bash
python -m pip install --upgrade pip
python -m pip install -r requirements.txt
```

7. Select Python interpreter in VS Code:  
Ctrl + Shift + P → Python: Select Interpreter → choose .venv

If using notebooks (.ipynb), select the .venv kernel and run cells with Shift + Enter.


## ➕ Adding New Packages

Install a new package:

```bash
pip install <package_name>
```

Update dependencies:

```bash
pip freeze > requirements.txt
```


