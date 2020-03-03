# IoTaaP Class Reference

## Constructor

**IoTaaP_MQTT()** - Construct a new IoTaaP_MQTT object.

## Functions

### apiLoop()
API function that will publish IoTaaP input states to the topic 'api/transfer'. Almost non-blocking.
#### Parameters

- **interval** Time in ms between two state readings. Default 10ms.

### callbackInnerFunction()
Inner function to be used in MQTT callback as direct API listener on topic `api/listen/<control_topic>`.
#### Parameters
- **controlTopic**	Topic where control JSON is published
- **topic**	Callback topic parameter
- **message**	Callback message parameter
- **length**	Callback length parameter

### connect()
Connects to the MQTT server on a desired port.
#### Parameters
- **clientID**	Client ID that will be used in communication
- **server**	MQTT server IP address or URL
- **port**	MQTT port of the server
- **secure**	If true MQTTS will be used and ca_cert is required, MQTT will be used by default
- **user**	Optional MQTT instance username
- **password**	Optional MQTT instance password
- **ca_cert**	CA Certificate or Root certificate used to verify SSH connection

#### Returns
- true if successfully connected
- false if there was a problem

### enableApi()
Subscribes to **IoTaaP** API topics and enables Serial function.
#### Parameters
- **serialBaud**	Optional baud rate if Serial is used. Default 115200.

###  keepAlive()
Keep the connection with MQTT alive, and reconnect if lost. Should be put in the main loop.
#### Returns
- uint16_t Returns 2 if succesfully reconnected, returns 0 if there was a problem and returns 1 if already connected

### publish()
Publish payload to the specified topic.
#### Parameters
- **topic**	MQTT topic
- **payload**	MQTT topic payload
- **retain**	Retain last message

#### Returns
- true if successfully connected
- false if there was a problem

### subscribe()
Subscribe to the MQTT topic.
#### Parameters
- **topic**	Topic name






