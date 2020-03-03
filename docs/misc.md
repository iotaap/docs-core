# IoTaaP Class Reference

## Constructor

**IoTaaP_Misc()** - Construct a new IoTaaP_Misc object.

## Functions

### blinkOnboardLed()
Blinks onboard LED for given interval and repeats loop.
#### Parameters
- **LED**	Onboard LED, can be ONBOARD_LED1 or ONBOARD_LED2

- **interval**	Time in ms between LED states

- **loops**	Number of loops to repeat

### clearPin()
Clears the pin (LOW state)
#### Parameters
- **pin** Pin to be cleared

### getBatteryPercentage()
Returns current battery percentage.
#### Returns
- `(double)` Battery percentage

### getBUT1()
Reads state of Button1.
#### Returns
- true if pressed
- false if not pressed

### getBUT2()
Reads state of Button2.
#### Returns
- true if pressed
- false if not pressed

### makePinInput()
Defines pin as INPUT, must be called before reading pin state.
#### Parameters
- **pin**	Pin to be defined as input

### makePinOutput()
Defines pin as OUTPUT, must be called before setting pin state.
#### Parameters
- **pin**	Pin to be defined as input

### restart()
Restarts **IoTaaP**.

### setPin()
Sets the pin (HIGH state)
#### Parameters
- **pin** Pin to set

### sleep()
Deep sleep with timer Wake Up after defined time in seconds (default 1);.
#### Parameters

- **seconds**	Time in seconds
