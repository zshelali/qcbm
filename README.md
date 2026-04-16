# Setting up the project for development

1. Install Python 3.12.10 (Make sure to check "Add Python to PATH" during installation if you are on Windows)

2. Clone the project on your machine and navigate into it:

```bash
git clone https://github.com/zshelali/qcbm.git
cd qcbm
```

3. Create a python virtual environment. Using Python's built-in venv is the easiest way across all operating systems:

```bash
python -m venv .venv
```

> [!IMPORTANT]
> If your system uses python3 instead of python, just run python3 -m venv .venv)

4. Activate the virtual environment:

Mac / Linux:

```bash
source .venv/bin/activate
```

Windows (Command Prompt or PowerShell):

```PowerShell
.venv\Scripts\activate
```

5. Update pip before installing anything:

```bash
python -m pip install --upgrade pip
```

6. Install uv (an extremely fast package manager):

```bash
pip install uv
```

7. After making sure you are still at the root of the project, run:

```bash
uv pip install -r pyqcbm-requirements.txt
```

## You are now set up!
