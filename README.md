# Python-Virtual-Environment-VSC

This Tutorial explains how to setup a Virtual Environment in Visual Studio Code for Python.

# Windows
1. Virtual Environment Module installation
```console
pip install virtualenv
```

> Open the directory where you want to create the Virtual Environment.
> Navigate to that Path in the VSC Powershell.
> Then enter there the following command:

2. Virtual Environment Creation
```console
virtualenv -p python3.7 venv
```

> This creates a Python 3.7 Virtual Environment. For other Versions simply change the Version number.

3. Choose your Interpreter
> Select the Python Interpreter (**venv**) in the bottom left hand corner in VSC.

4. Activate your Virtual Environment
> Click run on your .py file to automatically activate your Virtual Environment.
>
> Alternatively execute the *Activate.ps1* file found at *venv/Scripts/Activate.ps1*.

> Your Virtual Environment should be activated. You can see this by checking whether **(venv)** stands before every line in your Terminal.

> Now you can install modules and libraries only for your Virtual Environment.

5. Pip handling

### Single Module installation
```console
pip install flask
```

### Predefined requirements.txt
```console
pip install -r requirements.txt
```

> Check Versions for all installed modules / libraries.

```console
pip freeze
```

# Mac
