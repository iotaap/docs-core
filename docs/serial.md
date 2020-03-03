# IoTaaP Class Reference

## Constructor

**IoTaaP_Serial()** - Construct a new IoTaaP_Serial object.

## Functions

### getString()
Reads data from UART. This function is non-blocking and it will break if delimiter is not received within 1000mS after the last character.
#### Returns
- String Returns data received on UART

### getStringUntil()
Reads data from UART until delimiter char received. This function is non-blocking and it will break if delimiter is not received within 1000mS after the last character.
#### Parameters
- **delimiter**	Termination character

#### Returns
- String Returns data received on UART

### init()
Initializes UART port with specified baud.
#### Parameters
- **baud**	Valid baud rate

### isAvailable()
Checks if data is available on serial port.
#### Returns
- int Returns value different than 0 if true

### printLn()
Prints one line string to UART.
#### Parameters
- **string**	Text to be printed

### readChar()
Reads one character from UART buffer.
#### Returns
- int Character read

### writeChar()
Writes one character to the UART.
#### Parameters
- **ch** Character to be written

#### Returns
- size_t Number of written characters


