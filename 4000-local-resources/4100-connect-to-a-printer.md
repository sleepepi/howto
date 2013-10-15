## 4100 Connect to a Printer

The primary printer, a **RICOH Aficio MP 6001**, is located in the BLI-225 office. Another printer, a **RICOH Aficio MP 6002**, is located in BLI-252.

* RICOH Aficio MP 6001 -- IP: 172.23.134.56
* RICOH Aficio MP 6002 -- IP: 172.23.134.188

* Note: To get the drivers, you will have to map the sleepepi RFA share (\\\\rfa01\\bwh-sleepepi\\software)

### Windows 7


1. Click the **Start button**
2. Click **Devices and Printers**
3. Click **Add a printer**
4. Click **Add a network, wireless or Bluetooth printer**
5. Click **The printer that I want isn't listed**
6. Choose **Add a printer using a TCP/IP address or hostname** and click **Next**
7. Type the IP address in the **Hostname or IP address** field, uncheck the **Query the printer and automatically select the driver to use** box, and click **Next**
8. Click **Have Disk**, click **Browse**, navigate to the driver location on the RFA, `software/RICOH Drivers` click **Open**, click **OK**, and click **Next**
9. Enter a printer name, e.g. **RICOH Aficio 6001**, and click **Next**
10. Choose **Do not share this printer** and click **Next**
11. Click **Finish**


### Windows XP

1. Click the **Start button**
2. Click **Printers and Faxes**
3. Click **Add a Printer**
4. On the second page of the Add Printer Wizard, ensure that the option for a local printer is selected and uncheck "Automatically detect and install my Plug and Play printer"
5. Select the option to **Create a new port** and choose **Standard TCP/IP Port**
6. In the IP Address field, enter the IP address for the printer you wish to use (see above)
7. You will eventually be prompted to select drivers for the printer. Navigate to the RICOH drivers folder on the software section of the RFA and select the appropriate drivers.
8. Continue following the Wizard's instructions to finish adding the printer.


### Mac OS X

Before you begin, download and install the following programs and drivers from the software section of the RFA space:

* gplgs-8.71.dmg
* foomatic-rip-4.0.6.230.dmg
* pxlmono-1.9.dmg
* RicohPrinterDrivers1.0.0.dmg


1. Open System Preferences
2. Go to the Print and Scan subsection
3. Click the **+** icon and choose to "Add Printer by IP"
4. Enter the IP for the printer you wish to add (see above)
5. Change Use: to RICOH Aficio MP 6001 PXL
6. Change Finisher from "Not Installed" to "Finisher SR4050"


### Key Contacts

Michael Cailler (mcailler@partners.org) and Michael Rueschman (mrueschman@partners.org) at Sleep Medicine Epidemiology.


### Next Section

[4200 - Reserve a Conference Room](https://github.com/sleepepi/howto/blob/master/4000-local-resources/4200-reserve-a-conference-room.md)
