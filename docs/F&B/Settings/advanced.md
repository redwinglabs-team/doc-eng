# Configuration of fiscal printers

Set up printer profiles in Restaurant Manager for each physical printer in your restaurant (eg Receipt, fiscal, kitchen or bar printers). If you have four active units, you should have four corresponding configurations in Restaurant Manager.

Note that adding a physical printer in Fnb also requires some hardware settings and network configurations.

## Add a fiscal printer

1. Go to Main Menu> Settings> Advanced
2. Click on the + button
3. Check the "Enable" box
4. Enter the IP address and the serial number of the reference printer
5. Associate a Counter. Whenever the meter in question is used to close an account, it will send the receipt print request to the printer
5. Click Save

### Finding the IP address of a fiscal printer

#### Retrieve the printer's IP address:

1. Turn on the printer and connect it to the network you use for your devices.
2. To ensure that the printer's IP address does not change, the printer must be assigned a static (reserved) IP address in the router settings.
3. Turn off the printer.
4. While holding down the Feed button, turn on the printer and continue pressing the Feed button for approximately 7 seconds. The IP address appears on the printed receipt.
5. Copy the following string immediately after the found IP address: "/cgi-bin/fpmate.cgi?devid=local_printer&timeout=10000"