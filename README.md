How to run?
STEPS:
Clone the repository

Project repo: https://github.com/
STEP 01- Create a conda environment after opening the repository
conda create -n llmapp python=3.8 -y
conda activate llmapp
STEP 02- install the requirements
pip install -r requirements.txt
Create a .env file in the root directory and add your GOOGLE_API_KEY credentials as follows:
GOOGLE_API_KEY = "xxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
# Finally run the following command
streamlit run app.py
Now,

open up localhost:
Techstack Used:
Python
Google API
Streamlit
PaLM2
s2t
t2s