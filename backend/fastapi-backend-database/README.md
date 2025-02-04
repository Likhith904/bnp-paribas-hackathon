# This is BACKEND-DATABASE part in this project 

## To run this api follow the below steps

## Clone this project
```sh
git clone https://github.com/Likhith904/bnp-paribas-hackathon.git
```
## Change to this directory
```sh
cd backend/fastapi-backend-database/
```
- change env.sample to .env and add your mongodb connection string
### Requriements 
- Python >= 3.9

## Run the following commands
```sh
pip install uv
uv init .
uv venv # to create virtual environment
```
## Activate virtual environment
#### Windows 
```sh
.venv/Scripts/activate
```
#### Mac or Linux
```sh
source ./venv/bin/activate
```
### deactivate virtual environment
```sh
deactivate
```
## Install all the requirements
```sh
uv pip install -r requirements.txt
```
## Running the app
```sh
python main.py
```
- this usually run on localhost:8000
