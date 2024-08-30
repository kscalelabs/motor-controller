# List of Known Errata
1. The 5V regulator circuit is incorrect. Please remove the 5V regulator and supply an external 5V, or jump the USB 5V (currently NC) 
2. R23 (resistor in VBUS sense) is incorrectly specced to 10k instead of 18k, feeding up to 4.8V to a GPIO pin
