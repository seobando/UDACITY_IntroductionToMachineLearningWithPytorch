# Setup Instructions

## Virtual Environment Setup

### Windows (PowerShell)
```powershell
# Activate the virtual environment
.\venv\Scripts\Activate.ps1

# Install requirements
pip install -r requirements.txt
```

### Windows (Command Prompt)
```cmd
# Activate the virtual environment
venv\Scripts\activate.bat

# Install requirements
pip install -r requirements.txt
```

### Linux/Mac
```bash
# Activate the virtual environment
source venv/bin/activate

# Install requirements
pip install -r requirements.txt
```

## Deactivate Virtual Environment
When you're done working, deactivate the virtual environment:
```bash
deactivate
```

## Running Jupyter Notebooks
After activating the virtual environment and installing requirements:
```bash
jupyter notebook
```

Or if you prefer JupyterLab:
```bash
jupyter lab
```

## Project Structure
- `Project 1 - Finding Donors/` - Supervised learning project with scikit-learn
- `Project 2 - Create your own image classifier/` - Deep learning project with PyTorch
- `Project 3 - Identify Customer Segments/` - Unsupervised learning project with clustering

## Notes
- Make sure you have Python 3.8 or higher installed
- PyTorch installation may require additional steps depending on your system (CPU vs GPU)
- For GPU support with PyTorch, visit: https://pytorch.org/get-started/locally/

