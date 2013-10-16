## 2110 - Mapping RFA Shares ##

- Note: The full address of all RFA shares starts with \\\\rfa01\\bwh-sleepepi-PROJECTNAME. A full list of RFA shares can be found [here](https://github.com/sleepepi/howto/blob/master/2000-file-storage/2100-research-file-area-rfa.md)

### Windows 7

1. Open a new explorer window to **My Computer**
2. Click **Map network drive**
3. Select a drive letter that is not already taken, and enter the RFA share's path into the Folder path. Be sure to leave "Reconnect at logon" checked and "Connect using different credentials" unchecked.
4. Click **Finish**. If you have sufficient network permissions, the drive will map automatically and appear in the "My Computer" window under "Network Locations"


### Windows XP

1. Open a new explorer window to **My Computer**
2. Open the **Tools** menu on the menubar. Click **Map network drive**
3. Select a drive letter that is not already taken, and enter the RFA share's path into the Folder path. Be sure to leave "Reconnect at logon" checked.
4. Click **Finish**. If you have sufficient network permissions, the drive will map automatically and appear in the "My Computer" window under "Network Locations"


### Mac OS X

1. Open a new finder window and **Connect to Server** under the **Go** menu. Alternatively, use the keyboard shortcut **⌘+K**
2. To add any RFA share, you must first prepend the address with **smb:**. Also, all network paths on Mac must use forward slashes, rather than backslashes. For example: \\\\rfa01\\bwh-sleepepi-bestair on Windows will become smb://rfa01/bwh-sleepepi-bestair on Mac.
3. Because drive mappings are not saved when restarting or logging off your computer, it is advised that you click the **+** button to save commonly used share mappings to a favorites list before clicking **Connect**


### Key Contacts

Michael Cailler (mcailler@research.bwh.harvard.edu) and Michael Rueschman (mrueschman@partners.org) at Sleep Medicine Epidemiology.


### Next Section

[2200 - Massive Array of Disks (MAD)](https://github.com/sleepepi/howto/blob/master/2000-file-storage/2200-massive-array-of-disks-mad.md)
