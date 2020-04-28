# Development Environment Setup

## Linux

Install python3-dev and python3-pip with the OS package manager.
```
# Ubuntu
apt install python3-dev python3-pip

# Arch Linux
pacman -Syu python3-dev python3-pip
```

After `python` and `pip` are successfully installed We can getting started to install Tensorflow. Currently We only use CPU only so We only need `tensorflow-cpu`.

```
pip3 install tensorflow-cpu

```

## MacOS

Make sure `brew` installed in the system.

Install python3 among with pip

```
# download and install setuptools
curl -O https://bootstrap.pypa.io/ez_setup.py
python3 ez_setup.py

# download and install pip
curl -O https://bootstrap.pypa.io/get-pip.py
python3 get-pip.py

```

After `python` and `pip` are successfully installed We can getting started to install Tensorflow. Currently We only use CPU only so We only need `tensorflow-cpu`.

```
pip3 install tensorflow-cpu

```
