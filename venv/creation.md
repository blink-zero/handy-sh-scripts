Virtual Environment Setup
It is preferred to create a virtual environment per project, rather then installing all dependencies of each of your projects system wide. Once you install virtual env, and move to your projects directory through your terminal, you can set up a virtual env with:

python3 -m venv .venv
Dependency installations
To install the necessary packages:

source venv/bin/activate
pip3 install -r requirements.txt
This will install the required packages within your venv.
