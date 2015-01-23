
##Hello!


#####How to install the Pyramid Web Framework?
On Linux - Ubuntu or Mint


- Install the prerequisite tools (in Linux):
```
sudo apt-get update
sudo apt-get install python3-dev python3-setuptools
sudo easy_install virtualenv
```

- Configure the environment:
```
cd ~
mkdir pyramid_sites
cd pyramid_sites
```

and...

```
virtualenv --no-site-packages env
source env/bin/activate
easy_install pyramid
easy_install pyramid_jinja2
```

#####Pyramid IDE - Pycharm installation:
On Linux - Ubuntu or Mint


- Add a repository and run Pycharm installation:
```
wget -q -O - http://archive.getdeb.net/getdeb-archive.key | sudo apt-key add -
sudo sh -c 'echo "deb http://archive.getdeb.net/ubuntu trusty-getdeb apps" >> /etc/apt/sources.list.d/getdeb.list'
sudo apt-get update
sudo apt-get install pycharm
```


- Optional: to uninstall pycharm, do:
```
sudo apt-get remove pycharm
```

PyCharm requires Oracle Java. If you don't have it on your system, install it.


######Done
