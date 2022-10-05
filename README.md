# miniProject

## Project Introduction
This is a mini Django project in preparation for the 2022/23 Honours Project, presenting (1) an Intraday Candlestick Graph for S&P 500 Index at 5-min interval (2) Spider-web graph/ Radar map (3) Daily Close prices for S&P 500 stocks in information technology and financials sector Graph. 

## Authors

Hailey, Sami, Yong

## Project directory structure
```text
MiniProject
  |-- MiniProject
        |-- MiniProject (Django project settings)
              |-- asgi.py
              |-- settings.py
              |-- urls.py
              |-- wsgi.py
        |-- static (Data Collection files)
              
        |-- visual (Django app)
              |-- apps.py
              |-- views.py (website views)
  |-- .env
  |-- manage.py
```

## Clone repo
```shell
git clone "https://github.com/YongjiangChen/miniPoroject.git"
```
## Installation
In the cloned folder, open a terminal where requirements.txt is

```shell
pip install -r requirements.txt
```

## Running
Enter the manage.py directory in the terminal, and run server

```shell
python manage.py runserver
```
Ctrl-Click on the local server link poped in the terminal to open the web page

## Repo update
```shell
git pull
```

## Commit to the project
Upload file on github webpage or using git:
```shell
git add <file to be updated>
```

```shell
git commit -m "commit message"
```

```shell
git push origin main
```
