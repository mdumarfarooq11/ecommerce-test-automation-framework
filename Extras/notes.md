#open virtual env (here : project_env) 
    For powershell - after 
    Open PowerShell as Administrator
    Run: Set-ExecutionPolicy RemoteSigned -Scope CurrentUser
    Type Y or A

    For CMD - 
    project_env\Scripts\activate

#pip freeze > requirements.txt
    pip freeze → lists installed packages
    > → writes output to file
    requirements.txt → file name

    use - 
        Anyone can then do:
        pip install -r requirements.txt
        And their environment becomes exactly like yours.