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

3. Activation
  a. Command Prompt
    ```console
    call venv/Scripts/activate.bat
    ```
  b. Powershell
    ```console
    call venv/Scripts/activate.ps1
    ```
4. Deactivation
  a. Command Prompt
    ```console
    call venv/Scripts/deactivate.bat
    ```
  b. Powershell
    ```console
    call venv/Scripts/deactivate.ps1
    ```

> This creates a Python 3.7 Virtual Environment. For other Versions simply change the Version number.

## Visual Studio Code
1. Choose your Interpreter
> Select the Python Interpreter (**venv**) in the bottom left hand corner in VSC.

2. Activate your Virtual Environment
> Click run on your .py file to automatically activate your Virtual Environment.
>
> Alternatively execute the *Activate.ps1* file found at *venv/Scripts/Activate.ps1*.

> errors with PS: https://stackoverflow.com/a/67420296 (normal settings.json)

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

1. Virtual Environment Module installation
```console
pip install virtualenv
```

> Navigate to the directory where you want to create the Virtual Environment.

2. Virtual Environment Creation
```console
virtualenv -p python3.7 venv
```

activate
```console
source venv/bin/activate
```

deactivate
```console
deactivate
```
