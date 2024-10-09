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
- **[<font size = "4">How to view scanned Bluetooth Devices</font>](## How to view scanned Bluetooth Devices)**
- **[<font size = "4">How to connect the scanned Bluetooth Device</font>](## How to connect the scanned Bluetooth Device)**
- **[<font size = "4">View historical data of Bluetooth Devices</font>](## View historical data of Bluetooth Devices)**
- **[<font size = "4">Simulation demo</font>](## Simulation demo)**

## How to add a Gateway

### Configuring Gateway connect to network,eg:

***MKGW3(PoE)***
	
![MKGW3](img-folder/network_settings.png)
	
***MKGW2(LoRa)***
	
![MKGW2](img-folder/network_settings_lora.png)
	
Confirm your account is online.If your account shows as “Disconnected” after logging in, please contact the administrator.

![image text](img-folder/login_status.png)
	
### Add Gateway

***Use APP to add batches***

![addBatches](img-folder/add_batches.png)

***Manually add***

> Gateway Management -> Create Gateway

![addManually](img-folder/add_manually.png)
	
## Gateway information

### Gateway list

> After adding the gateway successfully, it will be in offline status by default. Click on "Subscribe", and once the platform receives the data reported by the gateway, it will be updated to online status.

![GatewayInfo](img-folder/gateway_info.png)

> You can view information such as the name, MAC address, product model, online status, and latest update time of the added gateway. It supports config scanner filters, payload parameters, gateway settings, as well as restarting and resetting the gateway.

### Configure Scanner filter, and Payload Parameters

> MOKOCloud can help you setting the gateway's scanning filter conditions. It supports filtering by RSSI, MAC address, Name, Raw Data, and Duplicate Data. 

> You can also configure the payload parameters of the uplink scanning data. This can be done under: “Gateway Management -> Scanner & Upload Option”.

![GatewayConfigFilter](img-folder/gateway_config_filter.png)

![GatewayConfigPayload](img-folder/gateway_config_payload.png)

### Configure Gateway Parameters

> In the detail page, you can modify the gateway's network access method, MQTT parameters, function parameters, gateway OTA, and other functions. This can be done under: “Gateway Management -> Detail”.

![GatewayDetail](img-folder/gateway_detail.png)

#### Set Up WiFi

> Some gateways only support WiFi for network access. After modifying WiFi parameters, the gateway needs to be restarted for the changes to take effect.

![GatewaySettingsWifi](img-folder/gateway_settings_wifi.png)

#### Set Up MQTT

> Changing the MQTT server or parameters that the gateway connects to requires a restart of the gateway for the changes to take effect.

![GatewaySettingsMQTT](img-folder/gateway_settings_mqtt.png)

#### Network Setting

> Some gateways that support both Ethernet and WiFi can choose to switch between network access methods. Changes will take effect after the gateway is restarted. 

![GatewaySettingsNetwork](img-folder/gateway_settings_network.png)

#### Function Configuration

> This includes configuring parameters such as scan switch, indicator light switch, and heartbeat packet interval. Changes take effect immediately after configuration.

#### OTA

> The gateway will automatically download and upgrade the firmware package. After a successful upgrade, the gateway will restart and rejoin the network.

![GatewaySettingsOTA](img-folder/gateway_settings_ota.png)