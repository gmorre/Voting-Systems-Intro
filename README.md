# Voting Systems Intro

This repository contains the `Voting_Systems_Intro.ipynb` notebook and the
local Python module, data files, and images it uses. Keep the notebook and the
`voting_functions.py`, `CVR files/`, and `SP images/` paths together as shown;
the notebook reads these files using relative paths.

## To run the notebook in the cloud with JupyterHub.

1. Open this [Binder link](https://mybinder.org/v2/gh/gmorre/Voting-Systems-Intro/HEAD?urlpath=%2Fdoc%2Ftree%2FVoting_Systems_Intro.ipynb)
2. Wait, it will take a few minutes for the file to open the Jupyter notebook in your browser.
3. Follow the instructions provided in the notebook.

When running the notebook this way your session will timeout after 10 minutes of inactivity. If you are not ready to move on to the next cell, you can re-run an old cell to keep the session active. If you want to save your progress and work on the notebook in multiple sessions you will need to run the notebook locally.

## To run the notebook locally

### 1. Install Python

Install Python 3.11, 3.12, or 3.13 from [python.org](https://www.python.org/downloads/). On Windows, select **Add python.exe to PATH** during installation if that option appears.

To check that Python is installed, open a terminal (or Command Prompt) and run:

```bash
python --version
```

It should print a version between 3.11 and 3.13. On macOS or Linux, you may need to use `python3` instead of `python`.

### 2. Download the repository

Get the **entire repository**, not just the notebook, because the notebook uses files stored alongside it.

- On GitHub, select **Code** → **Download ZIP**, then extract the ZIP file; or
- If you have Git installed, clone the repository:

  ```bash
  git clone https://github.com/gmorre/Voting-Systems-Intro.git
  ```

The folder you use should contain `Voting_Systems_Intro.ipynb`, `requirements.txt`, `voting_functions.py`, `CVR files/`, and `SP images/`.

### 3. Open a terminal in the repository folder

Change to the folder that contains `Voting_Systems_Intro.ipynb`. For example:

```bash
cd path/to/Voting-Systems-Intro
```

Keep the terminal open while you work.

### 4. Create and activate a virtual environment

A virtual environment keeps this notebook’s Python packages separate from other projects on your computer. Create it from the repository folder:

```bash
python -m venv .venv
```

Activate it using the command for your operating system:

- **Windows Command Prompt:**

  ```bat
  .venv\Scripts\activate.bat
  ```

- **Windows PowerShell:**

  ```powershell
  .\.venv\Scripts\Activate.ps1
  ```

- **macOS or Linux:**

  ```bash
  source .venv/bin/activate
  ```

After activation, you may see `(.venv)` at the start of your terminal prompt.

### 5. Install the required packages

With the virtual environment activated, run:

```bash
python -m pip install --upgrade pip
python -m pip install -r requirements.txt
```

This may take a few minutes. You only need to install these packages again if you create a new virtual environment.

### 6. Start JupyterLab

From the same terminal, with the virtual environment activated, run:

```bash
python -m jupyter lab
```

JupyterLab should open in your browser. If it does not, look in the terminal for a link beginning with `http://localhost` and open that link in your browser.

In JupyterLab, open `Voting_Systems_Intro.ipynb` and follow the instructions in the notebook. Keep the terminal open while using JupyterLab; closing it stops the local server. To stop the server when you are finished, return to the terminal and press **Ctrl+C**.

**Important:** Run JupyterLab from the repository folder and keep the notebook, `voting_functions.py`, `CVR files/`, and `SP images/` together in their original locations. The notebook uses relative paths to find those files.

The notebook hides and locks code cells in compatible Jupyter interfaces.
This is only a display/editing convenience; the notebook source is still
available to anyone who downloads the file.
