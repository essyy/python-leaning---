# python-leaning---

- A virtual environment is a sandbox where you can install only the Python packages you need for a particular project, without the risk of those packages clashing with those for another project (or your system). You create different little sandboxes for each project and install only the packages you want in it.
- theoce is python3 -m ❶ venv ❷ venv
- The first venv ❶ is a command that creates a virtual environment, and the second venv ❷ is the desired path to the virtual environment. In this case, venv is just a relative path, creating a venv/ directory in the current working directory. However, you could also use an absolute path, and you could call it whatever you want. For example, you could create a virtual environment called myvirtualenv in the /opt directory of a UNIX system, like this
- python3 -m venv /opt/myvirtualenv
- to activate it  venv\Scripts\activate.bat
- Pip is used in installation of files using the command: pip install
- You can use == to signify a specific version or even >= 
- You can also write a requirements.txt filr that contains commands of packages yu would like to install
- Then run pip install -r requirements.txt
##### Update files using pip install --upgrade---------------
###### pip search command to find the packages
