This is modified TouchScreen library for TFT LCD Touch Screen Module Board For Arduino, like : http://www.ebay.fr/itm/2-4-inch-TFT-LCD-Touch-Screen-Module-Board-For-Arduino-UNO-NEW-LD-/141859601684?hash=item21077dbd14. It allows to operate the module that A2 and A3 pin shared between the TFT screen and the touch screen, without having to manually switch to pinMode(A2/A3, OUTPUT) after use touch screen for re-enable TFT screen.

The modified library is used in the same way as the base library (see example files). For display library, you can use [Adafruit GFX Library](https://github.com/adafruit/Adafruit-GFX-Library) and [Adafruit TFTLCD-Library](https://github.com/adafruit/TFTLCD-Library) (see examples files for the configuration).

**Warning ! If you use Arduino Mega board, use digital pins 22 through 29 for TFT digital pin, like :**

| LCD PIN | ARDUINO PIN |
|---------|-------------|
| LCD_D0  | 22          |
| LCD_D1  | 23          |
| LCD_D2  | 24          |
| LCD_D3  | 25          |
| LCD_D4  | 26          |
| LCD_D5  | 27          |
| LCD_D6  | 28          |
| LCD_D7  | 29          |