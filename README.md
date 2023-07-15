# ModChecker<br />![GitHub all releases](https://img.shields.io/github/downloads/chuff-io/ModChecker/total?style=for-the-badge) ![GitHub repo size](https://img.shields.io/github/repo-size/chuff-io/ModChecker?style=for-the-badge) ![GitHub last commit](https://img.shields.io/github/last-commit/chuff-io/ModChecker?style=for-the-badge) ![GitHub stars commit](https://img.shields.io/github/stars/chuff-io/ModChecker?style=for-the-badge)

Discord bot to monitor collection of mods on the Steam Workshop and notify on update to selected Discord channel via Nextcordbot API.
# Requirements

- Python 3.10 or later
- Python pip -> requirements.txt
- Discord bot token
# Setup
**Linux**
```py
git clone https://https://github.com/chuff-io/ModChecker/
cd Steam-Workshop-Monitor/
pip3 install -r requirements.txt
#Edit info in .env
python3 WorkshopMonitor.py
#Wait till config fills then ctrl+c
#Comment out l5 in .env
python3 WorkshopMonitor.py
```
**Windows**
```py
Downloadn the repo and extract to an empty folder
Open a CLI ex. CMD,PS,GitBash in the directory
pip3 install -r requirements.txt
#Edit info in .env
python3 WorkshopMonitor.py
#Wait till config fills then ctrl+c
#Comment out l5 in .env
python3 WorkshopMonitor.py
```
