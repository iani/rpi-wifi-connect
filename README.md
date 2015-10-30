# rpi-wifi-connect
Configuration of Raspberry Pi to connect to a wifi network

Includes two files:

- interfaces
- wpa_supplicant.conf

The present configuration gives a fixed (static) IP.

They are placed in folders in the same position that is required to put them on the Raspberry Pi - except for some reason the network folder is registered as a submodule and thus, instead of placing the file =interfaces= under =network= I placed it at the root level of the repo.

Edit the contents of these files to adapt to the name of your password, the IP that you want to have, and the password required.
