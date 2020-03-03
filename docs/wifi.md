# IoTaaP Class Reference

## Constructor

**IoTaaP_WiFi()** - Construct a new IoTaaP_WiFi object.

## Functions

### connect()
Connects to the WiFi AP.
#### Parameters
- **ssid**	AP SSID
- **pass**	AP Password

#### Returns
- **wifiConnectionInfo** Returns structure containing status 1 and IP address if connected successfully, or status -1 and IP 0.0.0.0 if there was a problem

### getScanned()
Returns SSID of discovered network.
#### Parameters
- **i**	Specify from which network item want to get the information

#### Returns
- `(String)` SSID string of the specified item on the networks scanned list

### openAP()
Opens WiFi access point with provided credentials. If password is not provided AP will be open. AP IP: 192.168.8.1.
#### Parameters
- **ssid**	AP SSID
- **password**	AP Password (optional)

#### Returns
- `(IPAddress)` Returns local IP address if successfully opened or empty IPAddress if not

### scan()
Scans for open WiFi networks and returns number of networks discovered.

#### Returns
- `(int)` Number of networks discovered