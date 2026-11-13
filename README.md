# Personal Task Manager
![Static badge](https://img.shields.io/badge/Python-blue?logo=python&logoColor=white)

A simple task manager built with python for learning and github

## Features
- add multiple tasks
- save tasks
- load save tasks
- admin mode
- set task priority

## Task priority
Each task can have one of these priority levels:
- low
- medium 
- high

## Requirements
- Python 
- python-dotenv

## Project structure
```text
Spotplayer_task_mager/
│   .env.example
│   .gitignore
│   main.py
│   README.md
│   requirements.txt
│   tasks.py
│
├───images/
│       ezgif-speed.gif
│___       spotplayer_task_manager.png

```

## Installition
Install the requirement packages:

```bash
python -m pip install -r requirement
```
## Envoirment Setup
create a `.env` file in the project folder 

use `.enve.example` as a template

Add your admin passwort 

```env
admin_password = your_password_here
```
replace `your_password_here` with your own admin password

## Run the Program
run the main.py file:
```bash
python main.py
```
## Screenshot
![personal_task_manaher_screenshote](images/spotplayer_task_manager_update.png)

## Demo 
![personal_task_manaher_demo](images/gif_for_spotplayer_task_manager-ezgif.com-speed.gif)