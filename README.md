# Quoty McWalletface

From me ........ Read the .ino file, especially the comments in the header. I do not have the time to support other boards or setups, unfortunately.

Make sure you also view Adafruit for basic instructions on installing libraries for the ThinkInk feather and/or Nano Thermal Printer. I do not follow Adafruit's power instructions on the thermal printer though, preferring a 1amp DC power source instead of a 2amp that requires a logic stepdown chip to prevent burning out the 3.3v ESP32 board.


# Version 1.0 Features:

• A random quote generator to hide your wallet in plain sight.

• A hidden menu with three tools: 
    
    1) An airgapped PSBT signer
    
    2) An airgapped Bitcoin Wallet generator with code to save to SD card (optional) or print via a thermal printer (optional)
    
    3) A flashlight with an optional strobe function
    

Note that this version's code includes SD and Thermal Printing, but if you know what you are doing, you can comment that out of the code for a faster experience.
