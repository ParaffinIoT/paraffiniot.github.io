# Paraffin IoT Platform


## About


> Paraffin is an IoT platform  with MQTT, HTTP and CoAP bridge, based on Node.js and mongoDB.

![Paraffin IoT Platform diagram](https://raw.githubusercontent.com/ParaffinIoT/docs/master/images/ParaffinIoT_Diagram_01.png)

Paraffin will enable you to put your IoT API services on your own server simply and painlessly in one command. It supports the popular MQTT protocol in sync with HTTP. Paraffin is developed using JavaScript. It utilizes `Parse Server` as API Server and a broker based on `Ponte`. The broker performs authentication using your data in residing in MongoDB via the API Server.
Paraffin is still under development.


## Features

* Simple and Scalable.
* HTTP, MQTT and CoAP connections together as a bridge.
* MQTT 3.1 and 3.1.1 compliant.
* Sercured with authentication and JWT.


## Installation

There are two methods for installing Paraffin IoT Platform. Either way, make sure docker and docker-compose are installed before you proceed.

### Using Shell Script

Run the following command in your terminal to install the latest official Paraffin IoT Platform release.

```bash
sudo curl -o- https://raw.githubusercontent.com/ParaffinIoT/paraffin/master/install.sh | bash
```


### Using Git

Download Paraffin IoT Platform's git repository
```bash
git clone https://github.com/ParaffinIoT/paraffin

cd paraffin

sudo docker-compose up
```



## Tutorial

You can find a step-by-step <a href="https://github.com/ParaffinIoT/paraffin/wiki/Tutorial">tutorial</a> in wiki page .

### Development

Paraffin is composed of different microservices.
Each of them have their own installation guidelines to follow.

| Microservice  | Description |
| ------------- | ------------- |
| [API Server](https://paraffiniot.github.io/apiserver) | API Server |
| [Brokero](https://paraffiniot.github.io/brokero)  | Paraffin Installer Shell Script |
| [Broker](https://paraffiniot.github.io/broker) | MQTT/HTTP/CoAP server/broker |
| [Dashboard](https://paraffiniot.github.io/dashboard) | Paraffin Admin Dashboard |


#### Development Environment Variable

During deployment, every microservice needs to be set to the following environment variables (remember to change them with your own microservices, MongoDB).

| Environment Variable | Description |
| ------------- | ------------- |
| `DB_URL=development` | MongoDB URL |
| `NODE_ENV=development` | Development environment |



### Learn more

A test version of Paraffin IoT Platform will be available at paraffin.iokloud.com soon.

If you find Paraffin useful, please consider supporting the project by buying a support package
from [me](http://twitter.com/iokloud) by writing an email to iokloud.com@gmail.com.

Check out our [showcase](https://github.com/ParaffinIoT/paraffin/wiki/IOK-Express-Showcases) wiki
page! Feel free to add yourself! :)

## Security Issues

__Paraffin-IoT__ sits between your system and the devices: this is a tough role, and we did our best to secure your systems.
However, you might find a security issue: in that case, email @iokloud at iokloud.com@gmail.com


## Feedback

Use the [issue tracker](https://github.com/ParaffinIoT/paraffin/issues) for bugs.
[Tweet](http://twitter.com/iokloud) us for any idea that can improve the project.


## Links

* [Mosca](http://github.com/mcollina/mosca)
* [Ponte](https://github.com/eclipse/ponte)
* [Parse Server](https://parseplatform.org)
* [MongoDB](https://www.mongodb.com/)
* [MQTT protocol](http://mqtt.org)
* [MQTT.js](http://github.com/adamvr/MQTT.js)
* [Paraffin Platform](https://paraffiniot.github.io)


## Authors

[Hadi Mahdavi](https://github.com/expandboard),
[Nana Kwame Zoe](https://github.com/banphlet),
[Kwarteng Wisdom](https://github.com/Wisdom0063),
[Ahmad Rafiee](https://github.com/AhmadRafiee)
