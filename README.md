# dmidecode-randomizer
dmidecode-randomizer deals with the potential threat of dmidecode to a user's privacy and anonymity.

# **Introduction** 
Most linux distributions come with a utility known as dmidecode. This utility returns useful information about 
a system, such as BIOS information and detailed information about the hardware, including IDs of the hardware components. 
Yet such information can serve as a unique fingerprint of a system, thereby posing a threat against a user's privacy and anonimity.

Though dmidecode can be easily deleted or deactivated, this is not always an option, since there are programs and packages that
retrieve information about a system using dmidecode. And when it comes to protecting one's privacy, it is always better
to provide false information to the would-be thief of it than making him understand that you want to protect it. 

This project is a minor modification of dmidecode in a way that it no longer poses a threat against a user's privacy and anonymity,
by making it return random IDs instead of the original ones. 

It will be followed by another project that replaces the DMI table itself with another one containing fake, yet real-looking, data, 
thus preventing the attackers from gathering even general information about one's system.

If you are interested in contributing to it, you can contact me via gmail (malandrakisgeo).

# **Disclaimer** 
The project is based on the code of dmidecode as found on https://github.com/mirror/dmidecode . 
This is a distinct project, and its' author has no intention of claiming cretid for the original dmidecode.
