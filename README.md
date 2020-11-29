# dmidecode-randomizer
dmidecode-randomizer deals with the potential threat of dmidecode to a user's privacy and anonymity.

**Introduction** 
Most linux distributions come with a utility known as dmidecode. This utility returns useful information about 
a system, such as BIOS information and detailed information about the hardware, including IDs of the hardware components. 
Yet such information can serve as a unique fingerprint of a system, thereby posing a threat against a user's privacy and anonimity.

Though dmidecode can be easily deleted or deactivated, this is not always an option, since there are programs and packages that
retrieve information about a system using dmidecode. And when it comes to protecting one's privacy, it is always better
to provide false information to the would-be thief of it than making him understand that you want to protect it. 

This project modifies dmidecode in a way that it will no longer be a threat against a user's privacy and anonymity. 
The first stage of its' development concentrates on returning random IDs instead of the original ones. 
The second stage will concentrate on randomizing even general information about one's system. 

This project is to be followed by another -more demanding- project that will randomize the information in the DMI table itself -that is, in the very source of 
the information provided by dmidecode. If you are interested in contributing to it, you can contact me via gmail (malandrakisgeo).

**Disclaimer** 
The project is based upon the code of dmidecode as found on https://github.com/mirror/dmidecode . 
