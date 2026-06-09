# AISkillFest — Hello World Python App

A minimal Python console application used for demonstration during AISkillFest.

Prerequisites:
- Python 3.8+ installed (or use the included virtual environment if available).

Running locally:
```bash
python main.py
```
or, using the workspace virtual environment (Windows PowerShell):
```powershell
c:/Users/WorK/TesteDotNet/TesteDotNet/.venv/Scripts/python.exe main.py
```

Project structure:
- `main.py` — entrypoint printing "Hello World".
- `README.md` — this file.

Notes:
- This is a tiny starter repo. You can add a `.gitignore`, license, or expand the app.

How to use
-----------

Run the app:

```bash
python main.py
```

What to expect:
- The program prints `Hello World` to the console and then exits.

Modify the app:
- Open `main.py` and change the `print("Hello World")` line to your desired output or add new functions.

Using a virtual environment:
- To create a venv: `python -m venv .venv`
- Activate (PowerShell): `.\.venv\Scripts\Activate.ps1`
- Then run: `python main.py`

Next steps you might try:
- Add command-line arguments with `argparse`.
- Add logging or tests under a `tests/` directory.
- Add a `.gitignore` to exclude `.venv/` and `__pycache__/`.


