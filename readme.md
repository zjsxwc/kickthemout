![KickThemOut Logo](http://nikolaskama.me/content/images/2017/02/kickthemout_small.png)

# KickThemOut

> [KickThemOut](https://nikolaskama.me/kickthemoutproject) - **Kick Devices Off Your Network**

A tool to kick devices out of your network and enjoy all the bandwidth for yourself.
It allows you to select specific or all devices and ARP spoofs them off your local area network.

- Compatible with Python **3+** 🎉.

- *Not* compatible with Windows.

Authors: [Nikolaos Kamarinakis](mailto:nikolaskam@gmail.com) & [David Schütz](mailto:xdavid@protonmail.com).

[![Build Badge](https://travis-ci.org/k4m4/kickthemout.svg?branch=master)](https://travis-ci.org/k4m4/kickthemout)
[![License Badge](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/k4m4/kickthemout/blob/master/LICENSE)
[![Compatibility](https://img.shields.io/badge/python-3-brightgreen.svg)](https://github.com/k4m4/kickthemout)
[![GitHub Stars](https://img.shields.io/github/stars/k4m4/kickthemout.svg)](https://github.com/k4m4/kickthemout/stargazers)

---

<p align="center">✨Read my latest post: <a href="https://nikolaskama.me/kickthemout-v2-0/"><i>KickThemout v2.0! 🎉</i></a></p>
    
-------------

# 安装

## Debian 8 Jessie 安装
```
export LC_ALL='en_US.utf8'
sudo apt-get update && sudo apt-get install nmap
sudo apt-get insyall tcpdump
sudo apt-get install python3-pip

git clone https://github.com/k4m4/kickthemout.git
cd kickthemout/
sudo -H pip3 install -r requirements.txt

sudo python3 kickthemout.py
```


## macOS运行不了


# 使用方式

```
Usage: sudo python3 kickthemout.py [options]

Options:
  --version             show program's version number and exit
  -h, --help            show this help message and exit
  -p PACKETS, --packets=PACKETS
                        number of packets broadcasted per minute (default: 6)
  -s, --scan            perform a quick network scan and exit
  -t TARGETS, --target=TARGETS
                        specify target IP address(es) and perform attack

Examples:
  sudo python3 kickthemout.py --target 192.168.1.10 
  sudo python3 kickthemout.py -t 192.168.1.5,192.168.1.10 -p 30
  sudo python3 kickthemout.py (interactive mode)
```

To view all available options run:

```
~/kickthemout ❯❯❯ sudo python3 kickthemout.py -h
```


<br/>

# Demo

Here's a short demo:

[![Asciinema Demo](https://nikolaskama.me/content/images/2017/01/kickthemout_asciinema.png)](https://asciinema.org/a/98200?autoplay=1&loop=1)

(For more demos click [here](https://asciinema.org/~k4m4))


<br/>

# Developers

* Nikolaos Kamarinakis - [@nikolaskama](https://twitter.com/nikolaskama)
* David Schütz - [@xdavidhu](https://twitter.com/xdavidhu)


<br/>

# Disclaimer

KickThemOut is provided as is under the MIT Licence (as stated below). 
It is built for educational purposes *only*. If you choose to use it otherwise, the developers will not be held responsible. Please, do not use it with evil intent.


<br/>

# License

Copyright (c) 2017-18 by [Nikolaos Kamarinakis](mailto:nikolaskam@gmail.com) & [David Schütz](mailto:xdavid@protonmail.com). Some rights reserved.

KickThemOut is under the terms of the [MIT License](https://www.tldrlegal.com/l/mit), following all clarifications stated in the [license file](https://raw.githubusercontent.com/k4m4/kickthemout/master/LICENSE).


For more information head over to the [official project page](https://nikolaskama.me/kickthemoutproject).
You can also go ahead and email me anytime at **nikolaskam{at}gmail{dot}com** or David at **xdavid{at}protonmail{dot}com**.
