# Calculator-Android-App
kivy, kivymd, pillow, python 3 

- ubuntu (linux)virtual machine (need at least 4gb of free RAM space for VM system) used, vscode used
- to convert python file main.py to APk (android app installation file), i used Buildozer to build the apk file.
- installed all the dependencies, initializing buildozer then edit specs file.

- run these: (ONLY FOR WINDOWS)
-   pip3 install --user --upgrade buildozer
-   sudo apt update
-   sudo apt install -y git zip unzip openjdk-17-jdk python3-pip autoconf libtool pkg-config zlib1g-dev libncurses5-dev libncursesw5-dev libtinfo5 cmake libffi-dev libssl-dev
-   pip3 install --user --upgrade Cython==0.29.33 virtualenv  # the --user should be removed if you do this in a venv

- add the following line at the end of your ~/.bashrc file
-   export PATH=$PATH:~/.local/bin/


- Todo:
-   need to deploy the apk on to a cloud platform, android app store.
