# UM SIADS 521 Assignment 3/4

How to run the notebook

## Setup Instructions

Clone the repository and install the dependencies in a virtual environment:

```bash
# 1. Clone the repository
git clone https://github.com/MSnowman/UM_SIADS.git
cd your-repo-name

# 2. Open the project in VS Code
(Ensure you have VS Code and the Python/Jupyter extensions installed)

# 3. Create and activate a virtual environment
# Open the integrated terminal in VS Code and run:
python3.13 -m venv venv
source venv/bin/activate  # On Windows, use: venv\Scripts\activate

# 4. Install requirements
pip install -r requirements.txt

# 5. Launch and set the kernel environment
- Open the `.ipynb` notebook file inside VS Code.
- In the top right corner of the notebook interface, click "Select Kernel" (or the currently selected Python version).
- Choose **"Python Environments"** and select the **venv** you just created.

# 6. Run the Notebook
Run all cells in the notebook. The charts and Dashboard will render correctly directly inside the VS Code window.