# Suspisious-Activity-Alert-Raspberry-Pi-Python


## Items you need for this setup

1. [Doorsensor](https://www.amazon.com/WINGONEER-Window-Sensor-Magnetic-Systemd/dp/B06XHHMBX1/ref=sr_1_4?crid=2FP6T4PKHJ803&keywords=door+sensor+raspberry+pi&qid=1555654064&s=gateway&sprefix=door+sensor+rasp%2Caps%2C171&sr=8-4)
2. [Raspberry Pi](https://www.amazon.com/CanaKit-Raspberry-Premium-Clear-Supply/dp/B07BC7BMHY/ref=sr_1_3?crid=141OPPSH8D2DP&keywords=raspberry+pi&qid=1555654271&s=gateway&sprefix=rasp%2Caps%2C196&sr=8-3)
3. [Usb Camera](https://www.amazon.com/Logitech-Widescreen-designed-Calling-Recording/dp/B004FHO5Y6/ref=sr_1_3?keywords=usb+camera&qid=1555654309&s=gateway&sr=8-3)
> Any usb camera can be used.
> you can also use piCamera module for rasperryPi. just need to install corresponding drivers

## Code & Operating System Setup

Installed Raspberry Pi with the basic operating system nothing special.
We don�t need to do anything particularly special when setting up the Raspberry Pi [from here](https://www.raspberrypi.org/downloads/raspbian/).
Download Raspbian Stretch with desktop for Desktop veresion and Raspbian Stretch Lite for CLI version

```
sudo apt-get install rpi.gpio
sudo apt-get install fswebcam
```


### References
[Email alert reference](https://makersportal.com/blog/2017/9/23/using-raspberry-pi-and-python-to-send-email-alerts)
[SMS alert reference](https://www.twilio.com/docs/sms/quickstart/python#send-an-outbound-sms-with-python)