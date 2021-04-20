# Installing the mirror

## Installing Pyenv

### Install the pre-requested.
```
$ sudo apt-get install -y build-essential libssl-dev zlib1g-dev libbz2-dev libreadline-dev libsqlite3-dev wget curl llvm libncurses5-dev libncursesw5-dev xz-utils tk-dev libffi-dev liblzma-dev python-openssl git
```

### Setting up python env
Follow the installation guid on [[Pyenv github]](https://github.com/pyenv/pyenv) and [[Pyenv-virtualenv]](https://github.com/pyenv/pyenv-virtualenv)

### Install Github Desktop version:
[[Installation Guid]](https://gist.github.com/berkorbay/6feda478a00b0432d13f1fc0a50467f1)

### Setting up the GPU:

##### To show the availible drivers:
```
ubuntu-drivers devices
```

##### Install the recommended:
```
sudo ubuntu-drivers autoinstall
```

##### Install specific driver:
```
sudo apt install nvidia-340
```
