# AI-Voice-Assistant

# How to run?

# STEPS:

 Clone the repository
Project repo: https://github.com/

# STEP 01- Create a conda environment after opening the repository

conda create -n Voice python=3.10 -y

conda activate Voice

# STEP 02- install the requirement

pip install -r requirements.txt

# Create a .env file in the root directory and add your GROQ_API_KEY credentials as follows:

GROQ_API_KEY = "xxxxxxxxxxxxxxxxxxxxxxxxxxxxx"

# Finally run the following command
streamlit run src/app.py