# jupyter
Jupyter notebook for repl.it

1. create a new github repository ex. jupyter_notebook
2. create a empty python file ex. jupyter.py
3. clone the github repository to repl.it ("import repo")
4. @.replit file, replace ' run = "" ' with ' run = "/home/runner/.local/bin/jupyter notebook --ip=0.0.0.0 --port=3000" '
5. type these in terminal(in order):
a. pip3 install --upgrade pip
b. pip3 install notebook
c. (jupyter --version ← if you want to check)
d. jupyter notebook --generate-config
e. jupyter notebook password
6. Enter and confirm the password
7. click the "Run" button and here you go
