# Mining Monitor 

	This monitor is a fork of https://github.com/anselal/antminer-monitor

	- Dashboard
	- Antminers Monitor

### Fresh Installation

> All commands must be typed without the leading dollar sign `$`
  1. Download the latest official release of #AntminerMonitor from https://github.com/anselal/antminer-monitor/releases
or the latest unofficial release from https://github.com/anselal/antminer-monitor/archive/master.zip
  2. Unzip the downloaded file in a folder of your preference
  3. Open a windows command prompt or a terminal and navigate to the folder where you unzipped the file using the `cd` command
e.g. If you unzipped the file in the folder `C:\Users\foo\Downloads\antminer-monitor-master` type the following command and press <Enter>
```sh
$ cd C:\Users\foo\Downloads\antminer-monitor-master
```
  > You command prompt or terminal should now look like  `C:\Users\foo\Downloads\antminer-monitor-master>`
  4. **This step apply only to *Mac* users**. If you are a Windows or Linux user continue to step 5.
  > Mac users should run all the commands with sudo eg. `sudo python get_pip.py`
  
Install `pip` using one of the following methods:
 - Download `get-pip.py` from https://bootstrap.pypa.io/get-pip.py and save it inside `antminer-monitor-master`. Run the following command to install it:
 > It will ask for the administrator password. Type it and press <Enter>. While typing your password you won't see the characters on your screen. This is only for security measures.
```sh
$ sudo python get_pip.py
```
or
 - Install pip using `easy_install`. Again it may ask for the administrator password.
```sh
$ sudo easy_install pip
```
  5. Install requirements (Mac users don't forget `sudo`)
```sh
$ python -m pip install -r requirements.txt
$ python create_db.py
```

### Run the app
 (Mac users don't forget `sudo`)
```sh
$ python manager.py runserver
```


### Donations

  - LTC: `Lf7vSN1getxWGthKAioSS86ds4rGdPN5Ra`
