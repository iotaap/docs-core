# IoTaaP Class Reference

## Constructor

**IoTaaP_PWM()** - Construct a new IoTaaP_PWM object.

## Functions

### disablePWM()
Detaches PWM from the pin.
#### Parameters
- **pin**	Pin to detach PWM from

### set()
Sets PWM duty cycle to PWM channel. setupPWM() must be called before.
#### Parameters
- **channel**	Preset PWM channel
- **duty**	PWM duty cycle

### setup()
Setups the PWM channel, and attaches pin.
#### Parameters


- **channel**	PWM channel (1-15)
- **freq**	PWM Frequency
- **resolution**	PWM resolution (1-16)
- **pin**	PWM pin










