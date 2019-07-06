<p align="center">
  <img src="https://raw.githubusercontent.com/ParaffinIoT/docs/master/images/paraffin_iot_platform.png">
</p>

# Paraffin IoT Platform

## About


#### Paraffin is IoT platform based on node.js and mongodb with MQTT, HTTP and CoAP bridge.

![Paraffin IoT Platform diagram](https://raw.githubusercontent.com/ParaffinIoT/docs/master/images/ParaffinIoT_Diagram_01.png)

Paraffin will enable you to put your IoT API services on your own server simply and painless in one command. It supports the popular MQTT protocol in sync with HTTP. It is in javascript and by Parse Server api server will be able to authorize your device list so broker perform authentication by your entry data in MongoDB by api server.
Broker is based on Ponte and is under development so it should work. It need time to release stable version.


## Features

* Simple and Scalable.
* HTTP, MQTT and CoAP connections together as a bridge.
* MQTT 3.1 and 3.1.1 compliant.
* Sercured with authentication and authorization.


## Installation

Paraffin IoT Platform is installed by two methods. Firstly besure docker and docker-compose is installed.

### Using Shell Script

[![asciicast](https://asciinema.org/a/255799.svg)](https://asciinema.org/a/255799)

Run the following command in your terminal to install the latest official Paraffin IoT Platform release.

```bash
sudo curl -o- https://raw.githubusercontent.com/ParaffinIoT/paraffin/master/install.sh | bash
```


### Using Git

Download Paraffin IoT Platform git
```bash
git clone https://github.com/ParaffinIoT/paraffin

cd paraffin

sudo docker-compose up
```



## Tutorial

You can find a step by step <a href="https://github.com/ParaffinIoT/paraffin/wiki/Tutorial">tutorial</a> in wiki page .

### Development

Paraffin is composed by different microservices.
Follow the installation guidelines for each of them.

| Microservice  | Description |
| ------------- | ------------- |
| [API Server](https://paraffiniot.github.io/apiserver) | API Server |
| [Brokero](https://paraffiniot.github.io/brokero)  | Paraffin Installer Shell Script |
| [Broker](https://paraffiniot.github.io/broker) | MQTT/HTTP/CoAP server/broker |
| [Dashboard](https://paraffiniot.github.io/dashboard) | Paraffin Admin Dashboard |


#### Development Environment Variable

During deployment, every microservice needs to be set to the following environment variables (remember to change them with your own microservices, mongodb). You can customize .env file in every repository.


### Learn more

You can find a test version of Paraffin IoT Platform at paraffin.iokloud.com as soon as possible.

If you find Paraffin useful, consider supporting the project by buying a support package
from [me](http://twitter.com/iokloud) by writing an email to iokloud.com@gmail.com

Check out our [showcase](https://github.com/ParaffinIoT/paraffin/wiki/Paraffin-Showcases) wiki
page! Feel free to add yourself! :)

## Security Issues

__Paraffin-IoT__ sits between your system and the devices: this is a tough role, and we did our best to secure your systems.
However, you might find a security issue: in that case, email iokloud.com@gmail.com


## Feedback

Use the [issue tracker](https://github.com/ParaffinIoT/paraffin/issues) for bugs.
[Tweet](http://twitter.com/iokloud) us for any idea that can improve the project.


## Links

* [authBroker](https://github.com/authbroker/authbroker)
* [Mosca](http://github.com/mcollina/mosca)
* [Ponte](https://github.com/eclipse/ponte)
* [Parse Server](https://parseplatform.org)
* [Mongodb](https://www.mongodb.com/)
* [MQTT protocol](http://mqtt.org)
* [MQTT.js](http://github.com/adamvr/MQTT.js)
* [Paraffin Platform](https://paraffiniot.github.io)


## Authors

[Hadi Mahdavi](https://github.com/expandboard)
[Nana Kwame Zoe](https://github.com/banphlet)
[Kwarteng Wisdom](https://github.com/Wisdom0063)
[Ahmad Rafiee](https://github.com/AhmadRafiee)
