# home_food
beta website for in-house home food

website development- windows requirements

1. Download and install VS code
    1.1 Install  extensions - python,prettier, etc.
    1.2 Enable autosave

2. Download and install Github desktop

3.Download and install git - https://git-scm.com/downloads/win 

4. Install latest python, check the version in cmd and vscode
    4.1 Install extensions(python)
    4.2 Create a virtual environment using (python -m venv .venv)
    4.3 If you want to activate the environment only in the current terminal when the Python extension loads, use:

        The python.terminal.activateEnvInCurrentTerminal setting activates the environment in the current terminal.
        If getting below error - 

        PS D:\VSCode> & D:/VSCode/.venv/Scripts/Activate.ps1
        & : File D:\VSCode.venv\Scripts\Activate.ps1 cannot be loaded because running scripts is
        disabled on this system. For more information, see about_Execution_Policies at

        This error occurs because PowerShell's execution policy prevents running scripts by default. To resolve this:
        Open PowerShell as Administrator.
        Run the following command to allow script execution for the current user: Set-ExecutionPolicy -Scope CurrentUser -ExecutionPolicy RemoteSigned
        Confirm the change when prompted.
        Try activating your .venv again.
        No Visual Studio Code setting or command directly controls PowerShell execution policies. This is a Windows security feature.

5. install flask - https://pypi.org/project/Flask/ 
    5.1 Flask guide -  https://flask.palletsprojects.com/en/stable/quickstart/ 
    5.2 $env:FLASK_APP = "hello:app"
        flask run
    5.3 $env:FLASK_DEBUG = "1"
        flask run









