# Homework Instructions (HW1 + HW2)

This guide explains how to set up your environment on macOS and how to complete the two homework assignments.

## 0) Clone the project
If you do not have the project folder yet, clone it first:

```bash
git clone https://github.com/cepessh/NLPPython102.git
cd NLPPython102
```

If you already have the folder, skip this step.

## 1) Project folder
Open Terminal and go to the course folder:

```bash
cd NLPPython102/notebooks
```

If you are not sure, ask me and I will confirm the exact path.

## 2) Create a virtual environment (macOS)
We will use a local virtual environment so your packages are isolated.

```bash
python3 -m venv .venv
source .venv/bin/activate
python -m pip install --upgrade pip
pip install datasets transformers matplotlib numpy
```

Notes:
- Keep the environment active while working (`source .venv/bin/activate`).
- `datasets` downloads data from the Hugging Face Hub, so you need internet access.
- You may need to install other packages. If something fails at this stage, you may use AI to troubleshoot installation.

Open the copied notebook files and work **inside those notebooks**.

**You should use AI assistants only as the last resort after you've spent significant effort and time yourself.**
