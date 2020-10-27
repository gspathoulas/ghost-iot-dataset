# GHOST-IoT-data-set
Smart-home network traffic IoT dataset

**GHOST** -- Safe-Guarding Home IoT Environments with Personalised Real-time Risk Control -- is a European Union Horizon 2020 Research and Innovation funded project that aims to develop a reference architecture for securing smart-homes IoT ecosystem

 The **GHOST-IoT-data-set** is a public data-set containing IoT network traffic collected with the deployment of the GHOST's capturing module in a real life smart-home installation, with multiple network interfaces and devices. During the capturing, abnormal functioning of devices has been intentionally triggered, to construct a data-set that enables the development of mechanisms that can conduct behavioral analysis against the activity in the smart-home.

 The data-set is going to be available after the publication of the corresponding paper.

The data-set contains data captured on each one of the six network interfaces of the smart-home gateway and is organized into two distinct levels of abstraction, namely packets and flows/batches. 

Specifically, the dataset consist of 12 csv files that contain data correpsonding to :

- Ethernet interface packets
- Ethernet interface flows
- Wifi interface packets
- Wifi interface flows
- PPP interface packets
- PPP interface flows
- Bluetooth interface packets
- Bluetooth interface batches
- RF869 interface packets
- RF869 interface batches
- Zigbee interface packets
- Zigbee interface batches

Detailed description of the dataset's fields are provided on the [Description of fields](https://github.com/gspathoulas/ghost-iot-dataset/blob/master/Description%20of%20fields.pdf), while the **GHOST-IoT-data-set** can be donwloaded from [here](https://github.com/gspathoulas/ghost-iot-dataset/raw/master/data.rar).
