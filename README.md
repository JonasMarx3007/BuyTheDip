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

Or:

```powershell
jupyter notebook buythedip.ipynb
```

### macOS or Linux

```bash
python3 -m venv .venv
source .venv/bin/activate
python -m pip install --upgrade pip
python -m pip install -r requirements.txt
jupyter lab buythedip.ipynb
```

Or:

```bash
jupyter notebook buythedip.ipynb
```
