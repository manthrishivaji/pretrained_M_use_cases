# instructions to successfully run the repo
  clone copy the repo
  in .env file add your huggingface write api key without quotes
  go to terminal and select command prompt

# create a conda environment
conda create -n myenv python=3.9

# activate the conda environment
conda activate myenv/

# install dependencies
pip install -r requirements.txt

# run the application in terminal type
python app.py

# open a browser and type 
"http://localhost:8000/docs" that's it.
