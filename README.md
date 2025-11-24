# Setup Instructions
## getting project
1. Open Terminal
2. run: `git clone <url_of_repo>`
3. go into the folder by running `cd cloud-class-project` in terminal

## installing tools
1. check if you have homebrew installed
   2. `brew --version` in terminal
   3. if not installed copy and paste the line below exactly
      1. `/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`
   4. install pyenv 
      1. `brew install pyenv pyenv-virtualenv`
## creating environment
1. install python 3.13.0
   1. `pyenv install 3.13.0`
2. create the virtual env
   1. `pyenv virtualenv 3.13.0 cloud-class-env`
3. activating venv
   1. `pyenv activate cloud-class-env` or
   2. `pyenv local cloud-class-env`
   3. the difference is that the local will automatically turn on the venv the next time you enter the folder
## install dependencies
1. run 
   1. `pip install -r requirements.txt`

congrats, its all setup, but now you need to import the dataset

for that you will need to make a new file inside the project call it dataset 
then make another file inside the dataset file call it train 
inside the train file copy and paste the unzipped CCSN file 
