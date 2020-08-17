# Goose Attack
Goose Attack installs Goose Desktop on the PC and then activates on the next restart. On the following reboot it deletes itself, like nothing ever happened.

# Installation
If using the python version:

    pip install -r requirements.txt

If using the executable just download it

# Build
If you want to build the executable for yourself: 
1. Install pyinstaller

        pip install pyinstaller
2. Goto the directory where the python script is and run:

        pyinstaller -w -F GooseAttack.py