# Statistical Machine Learning

## Ubuntu Setup

Download, clone or fork (your choice) this repository in a directory `PATH_TO_DIR/`.

Create a virtual environment using `python3`
```
cd PATH_TO_DIR/statistical-machine-learning/
sudo apt-get install python3-pip
pip3 install virtualenv
virtualenv venv
```

Now you should see `PATH_TO_DIR/statistical-machine-learning/venv/` folder.
Activate the enviroment and install the requirements:
```
source venv/bin/activate
ipython kernel install --name=python3 --user
pip install -r requirements.txt 
```

Open your notebooks using jupyter-notebook (or jupyter-lab):
```
cd notebooks/
jupyter-notebook
```

To deactivate the environment use `deactivate` command.
