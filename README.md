# getAir2U_Plugins
Plugins for airgeddon https://github.com/v1s1t0r999/getAir2U

# Author:     v1s1t0r999
# Repository: https://github.com/v1s1t0r999/getAir2U_Plugins
# License:    GNU General Public License v3.0, https://opensource.org/licenses/GPL-3.0

### DESCRIPTION

* **Captured-Handshakes (minimum getAir2U version: 10.20):**
Put Your captured handshakes files in a directory of Your choice, then choose one of them inside airgeddon itself. Default path is plugins/captured_handshakes/HANDSHAKES_FILES

* **Custom-Portals (minimum getAir2U version: 10.20):**
Put Your custom captive portal files in a directory of Your choice. Default path is plugins/custom_portals/PORTAL_FOLDER/PORTAL_FILES.
You can have multiple PORTAL_FOLDER, then choose one of them inside getAir2U itself. Take a look at custom_portals/OpenWRT_EXAMPLE for a custom captive portal example.

* **Default-Save-Path:**
Set the default directory for saving files. Default is plugins/output/

* **Regdomain (minimum getAir2U version: 10.20):**
Set regulatory domain to affect the availability of wireless channels and txpower.
You can check the country codes database i.e. here https://git.kernel.org/pub/scm/linux/kernel/git/sforshee/wireless-regdb.git/tree/db.txt

* **Smart-Twin (minimum getAir2U version: 10.20):**
Enable/Disable Evil Twin Access Point based on Target availability. Only work in Pursuit Mode.
Disabling Evil Twin Access Point when the target network is no longer present (e.g. the attacked router is turned off) is useful to make the attack less suspicious.

* **Sort-Targets (minimum getAir2U version: 10.20):**
When selecting targets, sort them by one of the following value:
bssid, channel, power, essid, encryption, default

* **UI-Boost (maximum getAir2U version: 10.11):**
Make a specifc language strings file instead of using the complete one, speeding up ui.
The advantages of using this plugin is a more reactive ui (not needed in getAir2U >=10.20).
Potentially this plugin could lower ram usage, useful in devices with limited ram memory e.g smartphones, tablets ecc..., but this is not possible with getAir2U  as it is. I tried to make it compatible but unfortunately it isn't possible

### INSTALL
Simply put the .sh file of your choice in getAir2U's plugins folder.
For more detailed instructions, please refer to getAir2U's documentations here https://github.com/v1s1t0r999/getAir2U/wiki/Plugins%20System

### USAGE
Some plugins can be configured, so please take a look at # USER CONFIG SECTION # inside the .sh file before use.

### OKIE DOKIE, BYE!
