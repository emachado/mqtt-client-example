mqtt-client-example
===================

MQTT client example written in python that subscribes to a topic at the Eclipse IoT broker and print received messages.
Based on example from https://eclipse.org/paho/clients/python/

If the message received starts with "speak ", it uses espeak to reproduce the
rest of the message.

Requires:
  * paho-mqtt module (https://github.com/eclipse/paho.mqtt.python)
  * espeak

Tested on OrangePi Mini running Ubuntu 16.04 (Armbian)
