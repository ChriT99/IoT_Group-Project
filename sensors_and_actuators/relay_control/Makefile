# name of your application
APPLICATION = relay_control

# If no BOARD is found in the environment, use this default:
BOARD ?= nucleo-f401re   # todo change the path for RIOT

# This has to be the absolute path to the RIOT base directory:
RIOTBASE ?= $(CURDIR)/../..

# Comment this out to disable code in RIOT that does safety checking
# which is not needed in a production environment but helps in the
# development process:
DEVELHELP ?= 1

# Change this to 0 show compiler invocation lines by default:
QUIET ?= 1

# Modules to include:
USEMODULE += periph_gpio
USEMODULE += xtimer

include $(RIOTBASE)/Makefile.include
