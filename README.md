# Quoty McWalletface

From me ........ Read the .ino file, especially the comments in the header. I do not have the time to support other boards or setups, unfortunately.

If you are new to Arduinos or ESP32, you can find out how to set it up with these instructions https://randomnerdtutorials.com/installing-the-esp32-board-in-arduino-ide-windows-instructions/ . After installing the board, be sure to pick the Adafruit Esp32 v2 board in Arduino IDE.

Make sure you also view Adafruit's website for basic instructions on installing libraries for the ThinkInk feather (and/or Nano Thermal Printer if you add that option). I do not follow Adafruit's power instructions on the thermal printer though, preferring a 1amp DC power source instead of a 2amp that requires a logic stepdown chip to prevent burning out the 3.3v ESP32 board.


# Version 1.0 Features:

• A random quote generator to hide your wallet in plain sight.

• A hidden menu with three tools: 
    
    1) An airgapped PSBT signer
    
    2) An airgapped Bitcoin Wallet generator with code to save to SD card (optional) and print via a thermal printer (optional)
    
    3) A flashlight with an optional strobe function
    

Note that this version's code includes SD and Thermal Printing, but if you know what you are doing, you can comment that out of the code for a faster experience if you don't need those features.



# Coming in the Future:

• EMF Detector in place of the Flashlight (in beta as of 12.9.22).

• A 3D Printer File for a Case (still in design phase).
