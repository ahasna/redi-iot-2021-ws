# Session #2 Hands-On Guide

## MQTT Fx

MQTT Fx is a visual MQTT Client which can be used to publish and subscribe to Public and Private Brokers. It can also be used for debugging and testing IoT Applications during development phase.

To use MQTT FX please follow these steps:

### Download & Install

Download & Install MQTT FX for your OS from [here](https://softblade.de/en/download-2/)

![MQTT FX Download](img/mqtt-fx-download.png)

- After starting MQTT FX for the first time, you'll be prompted to activate it. Please use the Activation key below to activate a trial version of the software:

```text
-----BEGIN CERTIFICATE-----
MIIFnjCCA4YCCQDm7/FV5GARMzANBgkqhkiG9w0BAQ0FADCBqTELMAkGA1UEBhMC
REUxEDAOBgNVBAgMB0JhdmFyaWExETAPBgNVBAcMCEVybGFuZ2VuMRcwFQYDVQQK
DA5Tb2Z0YmxhZGUgR21iSDEZMBcGA1UECwwQd3d3LnNvZnRibGFkZS5kZTEcMBoG
A1UEAwwTU29mdGJsYWRlIFJvb3QgQ0EgMTEjMCEGCSqGSIb3DQEJARYUY29udGFj
dEBzb2Z0YmxhZGUuZGUwHhcNMjEwNzMxMTQ0NzU2WhcNMjExMTI4MTQ0NzU2WjB4
MQswCQYDVQQGEwJERTEMMAoGA1UECAwDTlJXMREwDwYDVQQHDAhFcmxhbmdlbjES
MBAGA1UECgwJU29mdGJsYWRlMRIwEAYDVQQDDAlTb2Z0YmxhZGUxIDAeBgkqhkiG
9w0BCQEWEW5pa29Ac29mdGJsYWRlLmRlMIICIjANBgkqhkiG9w0BAQEFAAOCAg8A
MIICCgKCAgEAqUE9p71j0zzCIQJlacOrA/k7EvNO98jdVUS77opS2ONUg6mwWZ8H
QJrJbce00xN8RPTPfKG4gmpWYY9JEIl9U4baYGAjMALiEaInxODZ8TF1IqyKdmyL
9Q7t+Fd+goGZy1rZUeLDxU40OXZ0okJu1vc5lrXkVDQtscPeEvB/HORsV9+9LM0v
hUIx+S+SmF0CCh/oNWlmIW5lL0kViD49YC8jaULLzEgljh4rV3rQwKp40MBmFJkt
E3eMa3vfjHwDTlsTY84gLhAY5gYPzlTJPCXFrMlmiSGc5/tl3TTyT1+TJAEP3pGJ
ktRbEmlQi5FwOaGgSfbUj+5Sq1t+ZLp0stmB2wYh0izN/zklTB9FJMN93o/dbqVm
TS4ygxiUD3wuxL/yQryMoSHkPgZQfEEd4fHc22eetCrBwJRgs4wP528WfZ/Kup8o
SpAXexJlptFfiLY00XzXNxDWfzwEKBbJ5JUnNRIvzZ2Pul1ZYZ+/FKjjLUG7hmBW
nkkmUcu3758bbCRccwqiIlLcQrzx48TnOkiIpEoIEPKpBFkwpURLYMyrMfK9CSFO
l28/xYqf7WNdywABCmqCIiQIyvoIHDvYF3HR3fcEJ/4kqAA+Zt0A6X3uK2Bvsr9h
LuwaZnKPC2r3ghvqKIvTzvztj7isL4RRTrkf/0hZ/Xg5MIxsZCsRZ3cCAwEAATAN
BgkqhkiG9w0BAQ0FAAOCAgEAcrqWfOWEjMte0XhDZ2A4IUePW4uxZFxJ+Y1QFyY5
TBh0Kn0vAM1KRTieM8BLYvLhIBBCcGm5k5UHUvxVoNwO2N50k+EcCJpSqImi34Il
vhKUBrVs1BIlZ4uhcvUnEcwZQwrNDEKpaW2NApkvfAy3Iha8FiyMm02gzRwCu87/
PivLlnNWjIY4wn9Tv4f62TTHCKcz7XQphzZW7v3euadHe4hyr0NfJC1qzykiVflV
mDae8vm8gI6GRYu9+fpx+xB2TL3TV6jNF4hUVy1dQNJ0BEJF5xNMY8MtQA56QfJT
IsX53SpvVDzjPNb5ZyDtuLdYGeX6fse4XbowX32ROzjPdGpf8FFFwKsXHBkLn/Nu
UTOXqIXmM3DWcSKJI2QH/83vRZxfwTvvyeBSO4UHw/Be+5JHbvWFZtj+X1NfO9Ss
fUwaXbMS8LfKttyIoTIQrFNSvIdQQFch17Fi1/RAzsPBhSTinTWQccRu2m9x8Xkz
Fl5igOqu3Y7MWXQMh34Vzq+4zLiJSCddFIQDLFN926qc5jvNfTbq0gSznsGrW4Ec
ILxeJiT85mF4NpDuv91q7S0n7fcrhuxrv/6S2WhnwpeAXbHKg/LInksKov2w2KQL
kCIoNft6bwbDof59I6BQEdkdBz/VtTP17XPHo4xn1xAF80jeu1UbcioiK0P05HGe
Vi0=
-----END CERTIFICATE-----
```

![MQTT FX Activate](img/mqtt-fx-activate.png)

### Add and connect to a Public Test Broker (HiveMQ Public Broker)

![MQTT FX Broker Config 1](img/mqtt-fx-add-broker-1.png)

![MQTT FX Broker Config 2](img/mqtt-fx-add-broker-2.png)

![MQTT FX Broker Config 3](img/mqtt-fx-add-broker-3.png)

### Subscribe to a topic

![MQTT FX Broker Config 4](img/mqtt-fx-add-broker-4.png)

### Publish to a topic

![MQTT FX Broker Config 5](img/mqtt-fx-add-broker-5.png)

![MQTT FX Broker Config 6](img/mqtt-fx-add-broker-6.png)

## IoT Project - Hands On

### Back-end Setup

#### Get the code onto your Raspberry Pi

- connect to your Pi as explained [here](https://github.com/ahasna/redi-iot-2021-ws/tree/main/hands-on/session-1#connect-to-raspberry-pi)

- clone the project example code by executing these commands:

```bash
cd ~
git clone https://github.com/ahasna/iot-sensor.git
```

- install dependencies (programming libraries):

```bash
cd ~/iot-sensor
pi3 install -r requirements.txt
```

- edit the following in `run.py` and make sure to have a unique topic name:

```python
# VARS
mqtt_broker = "broker.mqttdashboard.com"
mqtt_broker_port = 1883
temp_topic = "redi-iot-2021/t" # <-- update temperature topic and make sure it is unique
humidity_topic = "redi-iot-2021/h" # <-- update humidity topic and make sure it is unique
```

- save your changes

- run the code:

```bash
python3 /home/pi/iot-sensor/run.python

# you should get an output similar to this:

Connected to MQTT Broker: broker.mqttdashboard.com  on Port: 1883

Light Topic:  redi-iot-2021/asem/light
Temp. Topic:  redi-iot-2021/asem/t
Humidity Topic:  redi-iot-2021/asem/h

Temperature: 27 C Humidity: 37 %
```

Congratulations your backend is good to go :tada:

### Front-end Setup

- download the code as `.zip` file from [here](https://github.com/ahasna/iot-dashboard)

![MQTT FX Broker Config 6](img/iot-project-fe-1.png)

- unzip the code and open it in an editor (VS Code for example :wink:)

- edit `js/app.js` and update the topics to match the values you have setup in the previous step:

```js
  //MQTT
  const mqtt_broker = "broker.mqttdashboard.com";
  const temp_topic = "redi-iot-2021/t";
  const humidity_topic = "redi-iot-2021/h";
  const light_topic = "redi-iot-2021/light";
```

![MQTT FX Broker Config 6](img/iot-project-fe-2.png)

- save your changes and open `index.html` in browser. If all went well you should see the following result:

![MQTT FX Broker Config 6](img/iot-project-fe-3.png)

Congrats once again! You have finished your first end-to-end IoT Solution :tada: :tada:

## Further Reading and Resource

- [Python for Everybody](https://www.py4e.com/) a great beginner course to learn Python

- [Python Tutorial for Beginners](https://www.youtube.com/watch?v=YYXdXT2l-Gg&list=PL-osiE80TeTt2d9bfVyTiXJA-UTHn6WwU&ab_channel=CoreySchafer)

- [Node-RED: Low-code programming for event-driven applications](https://nodered.org/)

- [MQTT Official Website](https://mqtt.org/)

- [MQTT Essentials](https://www.hivemq.com/mqtt-essentials/)

- [Paho MQTT Python Client](https://www.eclipse.org/paho/index.php?page=clients/python/index.php)

- [HiveMQ Public MQTT Broker](https://www.hivemq.com/public-mqtt-broker/)

- [Eclipse Mosquitto Open Source MQTT Broker](https://mosquitto.org/)

- [How-To Get Started with Mosquitto MQTT Broker on a Raspberry Pi](https://www.youtube.com/watch?v=AsDHEDbyLfg&ab_channel=BRUHAutomation)

- [Understanding MQTT: How Smart Home Devices Communicate](https://www.youtube.com/watch?v=NjKK5ab0-Kk&ab_channel=TheHookUp)

- [Node Red MQTT on the Raspberry Pi](https://www.youtube.com/watch?v=WxUTYzxIDns&ab_channel=RichardWenner)

- [Creating A Machine Learning IoT App on Raspberry Pi with Node-RED and TensorFlow.js](https://www.youtube.com/watch?v=6sFrQaDtK5Q&ab_channel=PaulVanEck)

## Contact

if you have any questions or you need any help doing some cool IoT or any other Programming stuff, feel free to send me an email to: `asem.hasna@gmail.com`

Happy Coding!
