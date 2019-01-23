
# pwd_crack
Cert, ftp, ssh, mysql, windows brute force

The cert and ftp programs support the large-capacity dictionary better. The other ones are written before and are not modified at present (the large-capacity dictionary support is poor, and all the data in the dictionary needs to be read out at once)

##cert暴暴###Software Linux system to be installed (ubuntu is recommended)

Install python2.7, an additional python module is required: threadpool

apt-get install python-setuptools
easy_install threadpool
Install the expect software:
apt-get install expect ###How to use: ./cert_crack.py cert filename ##ftp暴暴###Software Linux system to be installed (ubuntu is recommended)

Install python2.7, an additional python module is required: threadpool

apt-get install python-setuptools
easy_install threadpool
### 使用方法: ./ftp_crack.py ip (port(default 21)) ##ssh brute force Linux system (recommended ubuntu)
Install python2.7, you need to install additional python modules: threadpool, MySQLdb

apt-get install python-setuptools
easy_install threadpool

easy_install paramiko
###How to use: ./ssh_crack.py ip (port(default 22))
##mysql brute force Linux system (recommended ubuntu)

Install python2.7, you need to install additional python modules: threadpool, MySQLdb

apt-get install python-setuptools
easy_install threadpool

apt-get install python-mysqldb
###How to use: ./mysql_crack.py ip (port(default 3306))
##windows brute-breaking Linux system (recommended to use ubuntu)

Install python2.7, you need to install additional python modules: threadpool, MySQLdb

apt-get install python-setuptools
easy_install threadpool

easy_install impacket
###How to use: ./win_crack.py ip (port(default 3389))
