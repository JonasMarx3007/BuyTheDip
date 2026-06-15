# Buy The Dip

This university project compares investing immediately in the S&P 500 with a
simple strategy that holds cash until the market has fallen by 30%.

The complete analysis, calculations, and plots are in `buythedip.ipynb`.

## Requirements

- Python 3.11 or newer
- Git
- Internet access (for Yahoo Finance data)

## Installation

Clone the repository:

```bash
git clone https://github.com/JonasMarx3007/BuyTheDip.git
cd BuyTheDip
```

### Windows PowerShell

```powershell
py -3 -m venv .venv
.\.venv\Scripts\Activate.ps1
python -m pip install --upgrade pip
python -m pip install -r requirements.txt
jupyter lab buythedip.ipynb
```

In JupyterLab, use **Kernel > Restart Kernel and Run All Cells** to reproduce
the analysis. Run JupyterLab from the repository root so the notebook can find
the CSV files in the `data` directory.

The notebook downloads S&P 500 prices from Yahoo Finance when it runs, so an
internet connection is required.

### macOS or Linux

```bash
python3 -m venv .venv
source .venv/bin/activate
python -m pip install --upgrade pip
python -m pip install -r requirements.txt
jupyter lab buythedip.ipynb
```
