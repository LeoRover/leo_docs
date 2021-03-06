# Getting started

## **Before you power on the Rover**

### How to connect the battery to the Rover?

Connect the mating pair of the 3-pin connectors: the battery and the converter located on the opposite side of the Rover. Then fit the battery cables inside the Rover's back-rib and slide the battery on back-left quarter of the Rover's body. Tighten the 3x M5 screws using the provided screwdriver.

![](.gitbook/assets/1.png)

### How to connect the converter quarter to the Rover?

Connect the mating pair of the 3-pin connectors: the electronics box and the converter. Then fit the battery cables inside the Rover back-rib and slide the converter on back-right quarter of the Rover body. Tighten the 3x M5 screws using the provided screwdriver.

![Old photo, but you&apos;ll know what to do :\)](.gitbook/assets/2.png)

## Operation & maintenance

### **How to connect to the Rover?**

To connect to the Rover, turn Leo on using its main power button located on the left side of the battery. The LED on the button should start blinking green. After ca. 30 s the LED should stop blinking and the Rover should be operational. 

Check your host device for the WiFi network. The default credentials should look like this:

```text
SSID: LeoRover-XXXX
Password: password
```

{% hint style="info" %}
Instead of the `XXXX` keyword, you should see an identifier unique to your Rover's computer.
{% endhint %}

For instructions on how to change WiFi network credentials, you can visit this page:

{% page-ref page="basic-guides/change-the-access-point-settings.md" %}

Connect to the network.

To access the Web User Interface, open your web browser and type in the address line:

```text
http://10.0.0.1/
```

### Leo Rover UI \(leo\_ui\)

![](.gitbook/assets/leo-day-2.png)

### **Turn off the Rover properly**

Due to the system architecture the Rover needs to be turned off the old-school style. Before you click the power button located on the battery it's better to turn off the computer at first.

To do that click upper right corner icon, wait until the Rover shuts down \(WiFi network will disappear\) and shut down the battery.

{% hint style="info" %}
This way you'll extend the life of the software filesystem.
{% endhint %}

### **Battery charging**

First, disconnect the battery from the rover. To do that, untighten 3x inner hex head screws located on the rear left side of the rover. Then, slide the battery off the rover frame and disconnect the 3-pin connector.

Connect the charger provided with the Rover to AC power socket - LED located on the charger will light green.

Connect the battery to the charger and click the battery button. The charger LED will change from green to red - meaning that it's charging now.

When the battery is fully charged, the LED on the battery should turn back green. Turn the battery off and connect it back to the rover.

{% hint style="warning" %}
Do not click the button during charging!
{% endhint %}

### Software update

Refer to:

{% page-ref page="basic-guides/software-update.md" %}

