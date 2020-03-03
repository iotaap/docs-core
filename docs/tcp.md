# IoTaaP Class Reference

## Constructor

**IoTaaP_TCP()** - Construct a new IoTaaP_TCP object.

## Functions

### close()
Closes opened TCP connection.

### connect()
Connects to the TCP server.

#### Parameters 
- **host**	Host IP or DNS
- **port**	Host port

#### Returns
`(WiFiClient)` Returns configured WiFiClient object or empty object if there was a problem

### readString()
Reads string from TCP until delimiter is received.
#### Parameters
- **delimiter**	Delimiter character

#### Returns
- `(String)` Returns received payload

### send()
Sends payload to opened TCP connection.
#### Parameters
- **payload**	Payload to be sent







