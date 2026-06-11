## Installation

This project can be run using uv, conda, or Python venv.

### Option 1: uv

```bash
uv sync
uv run python main.py
```

### Option 2: conda

```bash
conda env create -f environment.yml
conda activate new-pdf
python main.py
```

### Option 3: venv

macOS/Linux:

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
python main.py
```

Windows PowerShell:

```powershell
python -m venv .venv
.venv\Scripts\Activate.ps1
pip install -r requirements.txt
python main.py
```