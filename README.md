# Cam87-box
 
## to be filled

### BOM
boards can be ordered almost fully SMD assembled from JLCpcb
there are few components to add to complete the project
* Power board
	* USB type B Molex
	* DC Jack 2.1mm
	* header M 2.54 1x4
	* header M 2.54 2x3
	* JST connector 2pts
	* JST connector 3pts
* Logic board
	* Header F 2.54 1x4
	* header F 2.54 2x3
	* header M 90° 2.54 2x9
	* EL7457CSZ : from ebay or aliexpress
	* CXD1267AN : from ebay or aliexpress
* Sensor board
	* header F 2.54 2x9
	* DS18B20 temp sensor
	* ICX453AQ : from old Nikon DSLR (40D, 50D, 70D)
* cooling system
	* TEC module : good results with TEC2-19003 or TEC2-25408
	* 40x40 heatsink
	* 40x40 fan

### Revision history
#### v1.2 - official release !
* some minors fix and cleaning
* cleaned connection between logic and sensor
#### v1.1 - first fully working board
* temp sensor moved to sensor board
* reworked cooling driver
	* new mosFET
	* bigger self
#### v1.0 - first build - it's working !
* cooling driver don't support enough current to drive TEC
* mistake with calibrating res for step-up
* bad connection on EEPROM

### Credits & usefull links
* Original post from GRIM : http://www.astroclub.kiev.ua/forum/index.php?topic=28929.msg599742&language=english#msg599742
* French board on Cam86 and Cam87 : https://www.webastro.net/forums/topic/148427-camera-ccd-fabriqu%C3%A9-maison-cam86/

