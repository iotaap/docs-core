# IoTaaP Class Reference

## Constructor

**IoTaaP_Buzzer()** - Construct a new IoTaaP_Buzzer object.

## Functions

### initBuzzer ()
Initializes onboard buzzer, must be called before buzzer is used.

### generateTone ()
Generates tone on the buzzer.
#### Parameters
- **freq** - Tone frequency
- **forever** - If TRUE, tone will be reporduced until buzzerStop() is called
- **durationMs** - Tone duration, will be ignored if 'forever' is true

### stopTone()
Stops and detaches onboard buzzer. Buzzer must be initialized first.