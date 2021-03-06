# Change the Rover access point settings

## Prerequisites

{% page-ref page="connect-to-the-console-ssh.md" %}

## Access the access point \(AP\) configuration file

Modify the 'hostapd.conf' configuration file by typing:

```bash
sudo nano /etc/hostapd/hostapd.conf
```

An editor interface should appear.

![](../.gitbook/assets/image%20%2814%29.png)

## Modify the settings

### Change the AP name and password

Modify the `ssid` and `wpa_passphrase` fields.

`ssid` corresponds to the access point name \(default: LeoRover-XXYYY\) and  `wpa_passphrase` is the network password \(default: password\).

Type `Ctrl+O` and `Enter` to save the modified configuration and `Ctrl+X` to exit the editor.

In order to apply the modifications, you need to restart the access point. To do so, just type:

```bash
sudo systemctl restart hostapd
```

### Change the AP channel

{% hint style="info" %}
This may be useful if you notice the network interference in crowded areas or you can use multiple Rovers at once. The Rover default channel is fixed, so you need to choose different ones when using multiple Leo-s.
{% endhint %}

Modify the `channel` field.

`channel` corresponds to the Rover 2.4 GHz Wifi access point broadcast channel. You can choose from 1 to 11.

Type `Ctrl+O` and `Enter` to save the modified configuration and `Ctrl+X` to exit the editor.

In order to apply the modifications, you need to restart the access point. To do so, just type:

```bash
sudo systemctl restart hostapd
```

{% hint style="success" %}
Done.
{% endhint %}

{% hint style="info" %}
In some cases, the changes may appear only after you restart the Rover 
{% endhint %}

