# virtual env
pip install virtualenv
# cd into the root directory
  cd ~/
# create a hidden folder called .envs for virtual environments
  mkdir .envs
# cd into the virtual environments directory
  cd .envs
# create a virtual environment folder: my_library
  virtualenv my_library
# activate the virtual environment from anywhere using
  source ~/.envs/my_library/bin/activate

# versions  
django 1.11.6
ember-cli: 3.14.0
node: 12.13.1


# django rest
python manage.py makemigrations
python manage.py migrate
python manage.py run server


# ember
ember s
