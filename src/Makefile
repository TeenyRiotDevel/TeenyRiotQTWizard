# Parameters for compiling
#
#	 add tap
#	$ brew tap sudar/arduino-mk
#	 to install the last stable release
#
#	$ brew install arduino-mk
#	 to install the development version
#
#	$ brew install --HEAD arduino-mk
#	

ARDUINO_DIR     = %{ArduinoPath}
ARDMK_DIR       = /usr/local/opt/arduino-mk/Arduino.mk

TARGET          = output
USER_LIB_PATH   = ../libraries
#ARDUINO_LIBS    =


# Avrdude code for programming

BOARD_TAG               = AVR_TEENYRIOT
ARDUINO_PORT            = 


# Auto-detected from boards.txt

# MCU             = atmega328p
# F_CPU           = 16000000
# AVRDUDE_ARD_PROGRAMMER  = stk500v2
# AVRDUDE_ARD_BAUDRATE    = 115200


# Arduino makefile

include $(ARDMK_DIR)/Arduino.mk
