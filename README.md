Welcome to the first realease of the DevCenter Network IRCd
We present you DevCenterIRCd-1.0, a MODIFIED UnrealIRCd, so most of the credits fhould go to the UnrealIRCd team 
that can be found at https://www.unrealircd.org.

INSTALLATION:

DevCenterIRCd can be installed same as UnrealIRCd:

* Run ./Config
* Run make
* Run make install
* Now change to the directory where you installed DevCenterIRCd, e.g. cd /home/user/devcenterircd.

CONFIGURATION:

Configuration files are stored in the conf/ folder by default (e.g. /home/user/devcenterircd/conf)

CREATE A CONFIGURATION FILE:

If you are new, then you need to create your own configuration file: Copy conf/examples/example.conf to conf/ 
and call it devcenterircd.conf. Then open it in an editor and carefully modify it.

GENERATING SSL LINKING PASSWORD

In the installed folder run the following command: ./devcenterircd spkifp 
e.g. cd /home/user/devcenterircd && ./devcenterircd spkifp 

STARTING IRCD:

Run ./devcenterircd start in the directory where you installed DevCenterIRCd.

For questions and remarks, you can find us on http://www.devcenter.info or using IRC on:
* irc.devcenter.info (ipv4 servers)
* irc6.devcenter.info (ipv6 servers)

ENJOY DEVCENTER!
-----------------
|  Last update  |
-----------------
| On 06.04.2018 |
-----------------
|    By ZioN    |
-----------------
