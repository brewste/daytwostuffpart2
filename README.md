# Recipie for new project working enviornment 

### 1. Repo Management
- If working with an exsisting github repo, fork the repo to create your own copy that you can work with.
    - Or, simply create your own repo through github
- To set up a cloud-based IDE through github, open a new "codespace". This will allow you to access a development environment hosted on a virtual machine, which you can then access through platforms such as VS Code. 

### 2. Virtual Environment 
Create a virtual environment to be able to work with Python in your development environment. Creating a local virtual environment ensures your system is protected and you are only installing and working with packages needed for the project.
- Use terminal command "python -m venv .venv" to create a new virtual environment in your project
- Activate this environment using the command "source .venv/bin/activate" to activate this environment 
- You should create a .gitignore file and include all virtual environment files to ensure that this environment is not uploaded to the repo. 

### 3. Creating a Project
- To create executable python files add new ".py" files
- Add any useful extensions, such as Data Wrangler
- If a requirements file is available, read the text file to download the required packages. Otherwise, download any packages you may need with pip install

