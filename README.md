<h3 align="center">RedPot</h3>

<p align="center"> A Web Server + SSH + MySQL HoneyPot designed to be setup and run on a virtual machine.
    <br> 
</p>

## 📝 Table of Contents

- [About](#about)
- [Getting Started](#getting_started)
- [Deployment](#deployment)
- [Built Using](#built_using)
- [Authors](#authors)
- [Acknowledgments](#acknowledgement)
- [Warning](#warning)


## 🧐 About <a name = "about"></a>

The purpose of this project was to build a honeypot that emulates a web server, a mysql server and an ssh server from scratch in python, and gather data from the intrusions it receives to build graphs in a secure web server using html, css and javascript.

## 🏁 Getting Started <a name = "getting_started"></a>

These instructions will get you a copy of the project up and running on your virtual machine for development and testing purposes. See [deployment](#deployment) for notes on how to deploy the project on a live system.

### Prerequisites

```
Virtual machine (preferably ubuntu 16.04 -> 20.04)
```
```
Python
```

### Installing


```
git clone https://github.com/grt4/RedPot

cd Redpot

chmod +x install.sh
 
sudo ./install.sh
```

## 🚀 Deployment <a name = "deployment"></a>

### Setup environment

```
chmod +x setup.sh  

sudo ./setup.sh
```

### Run Redpot

```
chmod +x redpot.sh  

sudo ./redpot.sh
```

### View Intrusions Graphs

- Graphs can be viewed at http://<IPmachine\>:5001

## ⛏️ Built Using <a name = "built_using"></a>

- [Python](https://www.python.org)
- [MySQL](https://www.mysql.com)
- [Apache](https://httpd.apache.org)
- [JavaScript](https://www.javascript.com)

## ✍️ Authors <a name = "authors"></a>

- [@kod34](https://github.com/kod34)

## 🎉 Acknowledgements <a name = "acknowledgement"></a>

- [fake-ssh honeypot](https://github.com/cheeseandcereal/fake-ssh)

## ❗ Warning <a name = "warning"></a>

- Installing this honeypot on your personal machine might lead to losing your data.

