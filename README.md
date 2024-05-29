# medical-disease-analysis-using-gpt4vision


### How to run:

1. Create a new environment


    conda create -n mdagpt4 python=3,10 -y


2. Activate the environment


    conda activate mdagpt4


3. Insatll required packages


     pip install -r requirements.txt


4. Run the app.py

   
   streamlit run app.py


### How to Deploy Streamlit app on EC2 instance

1. Login with your AWS console and launch an EC2 instance

2. Run the following commands


Note: Do the port mapping to this port:- 8501

sudo apt update

sudo apt-get update

sudo apt upgrade -y

sudo apt install git curl unzip tar make sudo vim wget -y

git clone "Your-repository"

sudo apt install python3-pip

pip3 install -r requirements.txt

#Temporary running
python3 -m streamlit run app.py

#Permanent running
nohup python3 -m streamlit run app.py
