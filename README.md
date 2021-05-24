# SIIM-COVID

*This repo will include only the basics / starter-code for the siim-covid19-detection Kaggle competition. Algorithms and findings will remain private.*

## System Requirements

1. Python - Version 3

`
apt install python3
`

2. Pip (python package manager)

`
apt install pip
`

3. Additional dependencies, which you will need to install locally.

`sh
sudo apt-get install python3-matplotlib
python3 -m pip install seaborn
`

4. pipreqs (depedency management utility)

`
pip install pipreqs
pipreqs .
`

This will create a "requirements.txt" file which you can use to maintain your dependency versions. Use:

`
pipreqs . --force
pip install -r requirements.txt
`

... to refresh your requirements.txt file and then reinstall your dependencies.

## To Execute

`
python3 main.py
`
