# MOKOCloud User Guide

<font size = "3">Before login MOKOCloud, please use the APP to config the Gateway connect the network. For Remote Gateway or Others, you can use any MQTT broker. For LoRa Gateways, please use Chirpstack and configure the LoRa Device to the appropriate frequency band through the APP.</font>

-------------------

### Supported product models：

***Remote Gateway***

<font size = "4">`MKGW-mini 01``MK107``MK107D Pro``MK107D Pro-35D``MK110 Plus 01`</font>

***Remote Gateway with metering***

<font size = "4">`MK110 Plus 02``MK110 Plus 03`</font>

***POE Gateway***

<font size = "4">`MKGW3`</font>

***Cellular Gateway***

<font size = "4">`MKGW4`</font>

***USB Gateway***

<font size = "4">`MKGW7`</font>

***Other Gateway***

<font size = "4">`MKGW1`</font>

***LoRa Device***

<font size = "4">`LW003-B``LW001-BG PRO(L)``LW001-BG PRO(M)``LW004-PB``LW004-CT``LW005-MP``LW007-PIR``LW008-MT`</font>

> MKGW1、MKGW2 user Web to configure parameters,LoRa Device use APP `MKLoRa` ,Other gateway use APP `MKScannerPro`

-------------------

### Guide

- **[<font size = "4">How to add a Gateway</font>](## How to add a Gateway)**
- **[<font size = "4">Gateway information</font>](## Gateway information)**
- **[<font size = "4">Configure Gateway parameters</font>](## Configure Gateway parameters)**
- **[<font size = "4">How to view scanned Bluetooth Devices</font>](## How to view scanned Bluetooth Devices)**
- **[<font size = "4">How to connect the scanned Bluetooth Device</font>](## How to connect the scanned Bluetooth Device)**
- **[<font size = "4">View historical data of Bluetooth Devices</font>](## View historical data of Bluetooth Devices)**
- **[<font size = "4">Simulation demo</font>](## Simulation demo)**

## How to add a Gateway

### Configuring Gateway connect to network,eg:

***MKGW3(PoE)***
	
![image text](img-folder/network_settings.png)
	
***MKGW2(LoRa)***
	
![image text](img-folder/network_settings_lora.png)
	
Confirm your account is online.If your account shows as “Disconnected” after logging in, please contact the administrator.

![image text](img-folder/login_status.png)
	
### Add Gateway

***Use APP to add batches***

![image text](img-folder/add_batches.png)

***Manually add***

> Gateway Management -> Create Gateway

![image text](img-folder/add_manually.png)
	
## Gateway information

### Gateway list

> After adding the gateway successfully, it will be in offline status by default. Click on "Subscribe", and once the platform receives the data reported by the gateway, it will be updated to online status.

![image text](img-folder/gateway_info.png)

> You can view information such as the name, MAC address, product model, online status, and latest update time of the added gateway. It supports configuring scanning filters, reporting parameters, gateway settings, as well as restarting and resetting the gateway. You can also filter the current list of gateways by model, name, and MAC address.

