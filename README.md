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

### AWS
1. Login with your AWS console and launch an EC2 instance
2. Run the following commands
Note: Do the port mapping to this port:- 8501
sudo apt update
sudo apt-get update
sudo apt upgrade -y
sudo apt install git curl unzip tar make sudo vim wget -y
git clone https://github.com/Arya1790/MultilingualAI.git
sudo apt install python3-pip

## python 3.10
sudo apt update
sudo apt install software-properties-common -y

sudo add-apt-repository ppa:deadsnakes/ppa
sudo apt update

sudo apt install python3.10 python3.10-venv python3.10-dev
python3 --version

ls -la /usr/bin/python3
sudo rm /usr/bin/python3
sudo ln -s python3.10 /usr/bin/python3
python3 --version

## pyaudio
sudo apt install portaudio19-dev
python3 -m  pip install PyAudio

pip install -r requirements.txt   #( pip3 not working )
#Temporary running
python3 -m streamlit run app.py
#Permanent running
nohup python3 -m streamlit run app.py
Note: Streamlit runs on this port: 8501