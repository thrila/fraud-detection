### Fraudulent Transaction Detector
This is a model that tries to predict fraudulent eth transactions
It was originally supposed to be for local bank transactions however i do not have access to transactions details lol

*Dataset:* provided by kaggle

**SETUP NOTEBOOK**
# 1. Clone the project
git clone <project_url>
cd <project_name>

# 2. Install dependencies from uv.lock
uv sync

# 3. Activate the virtual environment (optional, for manual control)
source .venv/bin/activate        # Unix/macOS
# OR
.venv\Scripts\activate           # Windows

# 4. Run Jupyter Lab
uv run jupyter lab               # Preferred — runs inside the uv-managed env
# OR if manually activated above:
jupyter lab

--- 
- [X] make prepare data, normalise and use relavant features to train
- [X] test various classification models
- [X] fine tune best performing model
- [ ] reimplement in a lowlevel language and expose via API

