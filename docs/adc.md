# IoTaaP Class Reference

## Constructor

**IoTaaP_ADC ()** - Construct a new IoTaaP_ADC object.

## Functions

### getValue()
Reads analog value from analog pin
#### Parameters
- **pin** - Analog pin to read value from

#### Returns
- `(unsigned long)` 12bit analog value

### getVoltage ()
Returns voltage (V) from A/D reading.
#### Parameters
- **reading** - RAW A/D reading (0-4095)

#### Returns
- `(double)` Calculated calibrated voltage