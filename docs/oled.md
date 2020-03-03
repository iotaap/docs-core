# IoTaaP Class Reference

## Constructor

**IoTaaP_OLED()** - Construct a new IoTaaP_OLED object.

## Functions

### displayBitmap()
Displays bitmap on OLED. initOLED() must be called before.
#### Parameters

- **x**	Start X coordinate (usually 0)
- **y**	Start Y coordinate (Usually 0)
- **bitmap**	Bitmap to show
- **color**	Bitmap color (usually 1)

### init()
Initializes integrated OLED.

### setBrightness()
Sets OLED brightness.
#### Parameters

- **perc**	Brightness percentage (0-100)

### showText()
Shows text on integrated OLED. OLED must be initialized first.
#### Parameters

- **text**	Text to be printed
- **x**	Text location on x coordinate
- **y**	Text location on y coordinate