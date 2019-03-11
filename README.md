# Paraffin IoT Platform Website


## About


#### Paraffin is IoT platform based on node.js, ponte and mongodb with MQTT, HTTP and CoAP bridge.

Paraffin will enable you to put your IoT API services on your own server simply and painless in one command. It supports the popular MQTT protocol in sync with HTTP. It is in javascript and by Parse Server api server will be able to authorize your device list so broker perform authentication by your entry data in MongoDB by api server.
Broker is based on Ponte and is under development so it should work. It need time to release stable version.


## Features

* Simple and Scalable.
* HTTP, MQTT and CoAP connections together as a bridge.
* MQTT 3.1 and 3.1.1 compliant.
* Sercured with authentication and JWT.


## Steps to run

Firstly besure docker and docker-compose is installed.


Download Paraffin IoT Platform git;
```bash
git clone https://github.com/ParaffinIoT/paraffin

cd paraffin

sudo docker-compose up
```



## Tutorial

You can find a step by step <a href="https://github.com/ParaffinIoT/paraffin/wiki/Tutorial">tutorial</a> in wiki page .



## Paraffin API

The Thing API defines a set of services to create, update or control any things. 

```
POST /signup
POST /signin
POST /thing
GET /thing
GET /thing/:clientid
PUT /thing/:clientid
DELETE /thing/:clientid
```

Example: for invoking list of created things as locally;
```
GET http://localhost:1337/api/thing/
```




### Learn more

You can find a test version of Paraffin IoT Platform at paraffin.iokloud.com as soon as possible.

If you find Paraffin useful, consider supporting the project by buying a support package
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
* [Mongodb](https://www.mongodb.com/)
* [MQTT protocol](http://mqtt.org)
* [MQTT.js](http://github.com/adamvr/MQTT.js)



## Authors

[Hadi Mahdavi](https://github.com/expandboard)
[Nana Kwame Zoe](https://github.com/banphlet)
[Kwarteng Wisdom](https://github.com/Wisdom0063)
[ahmad Rafiee](https://github.com/AhmadRafiee)
