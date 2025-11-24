# Developing a Machine-Learning Algorithm to Predict Fractional Free Volume for a Polymer

**Overview**

This project presents a machine-learning tool to predict fractional free volume (FFV) from a given polymer structure. FFV is difficult to measure experimentally; thus, being able to predict this polymer property can be useful when designing new polymer systems, such as for drug delivery. 

**Repo Map**
Here’s where to find stuff:
- `plot/` → plots created in the model  
- `FFV prediction_group4_CHE1147_Final.ipynb` → notebook file containing code  
- `dataset.csv` → dataset used to train the model 
- `requirements.txt` → requirements file for dependencies

**Setup the Environment**

Python version 3.11.14

To run this project locally, you can create a Python virtual environment and install dependencies from `requirements.txt`:

```bash
# Clone the repository
git clone https://github.com/GjotoGjoto/1147_new.git
cd 1147_new

# macOS / Linux
python3 -m venv venv
source venv/bin/activate

# Windows (PowerShell)
python -m venv venv
.\venv\Scripts\Activate.ps1

# Install dependencies
pip install --upgrade pip
pip install -r requirements.txt

# Deactivate when done
deactivate
```

Or you can run in Colab😊

```bash
# !pip install -r requirements.txt
```

**Usage**

The FFV prediction_group4_CHE1147 script is designed to follow all modelling steps in order, moving from EDA to pre-processing, to training, and finally to evaluation.



**Dataset**

The dataset used to train the model was obtained by the NeurIPS - Open Polymer Prediction 2025 Kaggle competition, which can be found here:
NeurIPS - Open Polymer Prediction 2025. https://kaggle.com/neurips-open-polymer-prediction-2025 (accessed 2025-10-20).

**Authors**

Emma Lord

Ghazal Shafiee

Ana Matovic
