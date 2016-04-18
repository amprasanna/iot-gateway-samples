# iot-gateway-samples
This repository contains samples for connecting your gateway to the IBM Watson Internet of Things Platform and perform one or more operations. Currently, there are samples for Java and Node-RED; information and instructions regarding the use of these samples can be found in their respective directories.

Gateways are a specialized class of devices in Watson IoT Platform which serve as access points to the Watson IoT Platform for other devices. Gateway devices have additional permission when compared to regular devices and can perform the following  functions:

* Register new devices to Watson IoT Platform
* Send and receive its own sensor data like a directly connected device,
* Send and receive data on behalf of the devices connected to it
* Run a device management agent, so that it can be managed, also manage the devices connected to it

Refer to the [documentation](https://docs.internetofthings.ibmcloud.com/gateways/mqtt.html) for more information about the Gateway support in Watson IoT Platform.

----

### Sample gateway scenario

Following sample gateway scenario is implemented in the java samples section. Refer to the [java samples section](https://github.com/ibm-messaging/iot-gateway-samples/tree/master/java) for more information.

![Alt text](./gateway-dm-diagram.png?raw=true "Sample Gateway scenario")

----

### License
-----------------------

The library is shipped with Eclipse Public License and refer to the [License file] (https://github.com/ibm-messaging/iot-gateway-samples/blob/master/LICENSE) for more information about the licensing.

