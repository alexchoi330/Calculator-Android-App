# Calculator-Android-App
kivy, kivymd, pillow, python 3 ubuntu (linux)

- virtual machine (need at least 4gb of free RAM space for VM system) needs to be set up OR WSL Windows Subsystem Linux which I used for this project on Ubuntu linux system (but still need around 3-4gb of free RAM to run ubuntu VM)
- to convert python file main.py to APk (android app installation file), i used Buildozer to build the apk file.
- installed all the dependencies, initializing buildozer then edit specs file.

# run these: (ONLY FOR WINDOWS)
-   pip3 install --user --upgrade buildozer
-   sudo apt update
-   sudo apt install -y git zip unzip openjdk-17-jdk python3-pip autoconf libtool pkg-config zlib1g-dev libncurses5-dev libncursesw5-dev libtinfo5 cmake libffi-dev libssl-dev
-   pip3 install --user --upgrade Cython==0.29.33 virtualenv  # the --user should be removed if you do this in a venv

- add the following line at the end of your ~/.bashrc file
-   export PATH=$PATH:~/.local/bin/

# initialize and run buildozer
- !buildozer init
- in buildozer.spec file, make sure to add the requirements = python3, kivy==2.0.0, kivymd, pillow (kivymd depends on pillow/PIL package
- !buildozer -v android debug

# Todo:
-   need to deploy the apk on to a cloud platform, android app store.


# Future
- consider using google colab, as it is faster to convert to apk file
- https://colab.research.google.com/gist/kaustubhgupta/0d06ea84760f65888a2488bac9922c25/kivyapp-to-apk.ipynb

source: https://buildozer.readthedocs.io/en/latest/installation.html
