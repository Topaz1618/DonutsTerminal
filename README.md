<img src='static/images/meowfile.png' width='400' title='MeowFile, A file management system'>

A web application written in Python, based on Tornado and paramiko, to connect to a remote server through a browser ssh made by [Topaz](https://topaz1618.github.io/about)|[Website](http://topazaws.com/)|[Blog](https://topaz1618.github.io/blog/)

[Chinese README](https://github.com/Topaz1618/FileManageSystem/blob/master/README_CN.md)


## Environment
- Python 3.6.5
- Tornado 5.0.1
- CentOS 7.4

### Installation

1. Download MeowFile

```
 # Download the latest version of JumperServer source code from github

 git clone https://github.com/Topaz1618/JumpServer.git
 cd JumpServer/
```

2.Install dependencies
```
 pip3 install -r requirements.txt
```
3.Run
```
 python main.py &
```

### Configuration

Set the following lines to your own Ip and port in main.py
```
 app.listen('8048', '127.0.0.1')
```


### Screenshots

1. Login Page
![avatar](static/img/login.png)

2. Terminal
![avatar](static/img/terminal.png)

3. Execution command effect 1
![avatar](static/img/terminal1.png)

4. Execution command effect 2
![avatar](static/img/terminal2.png)


### Precautions
- Available under Mac and Linux, not tested in Windows environment

