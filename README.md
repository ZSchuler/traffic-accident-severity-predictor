# traffic-accident-severity-predictor
Course project for the CMPT455 - Data Mining class at SFU.

## Python Environment

Create the venv (first time only):

```bash
python3 -m venv .venv
```

Activate it (each new shell):

```bash
source .venv/bin/activate
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Add a package:

```bash
pip install <package>
pip freeze > requirements.txt
```

Deactivate:

```bash
deactivate
```

## Jupyter Notebooks in VS Code

1. Install the Python and Jupyter extensions.
2. Open the `.ipynb` file and click **Select Kernel** (top right).
3. Choose **Python Environments**, then `.venv`.

If `.venv` isn't listed, run **Python: Select Interpreter** from the Command Palette (`Ctrl+Shift+P`), pick `./.venv/bin/python`, then reselect the kernel.