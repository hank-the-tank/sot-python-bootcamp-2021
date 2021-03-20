### Install for Mac
#### Install Homebrew
```
$ /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)" 
```
#### Install Python
```text
$ brew install python@3.8
```
#### Check Python is installed
```text
$ python3 --version
```
#### Install pip
```text
$ python get-pip.py
```
### Install for Linux
#### Install Python 
```text
$ sudo apt-get update
```
```text
$ sudo apt-get install python3.8
```
```text
$ python3 --version
```
#### Install pip
```
$ sudo apt install python3-pip
```
### Install virtual
```text
$ sudo pip3 install virtualenv 
```
### Install packages
```
$ pip install -r requirements.txt
```
### Active virtual environment
```text
$ source venv/bin/activate
```
### Run the app
```
$ python app.py
```

#### Pacakges
1. [Requests](https://requests.readthedocs.io/en/master/)
2. [Beautiful Soup](https://www.crummy.com/software/BeautifulSoup/bs4/doc/)

#### Reference
[Homebrew](https://brew.sh/)
[Python Software Foudation](https://www.python.org/downloads/)
[Pip documentation](https://pip.pypa.io/en/stable/installing/)