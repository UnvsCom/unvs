UNVS 
=============

<b>PLEASE NOTE THIS IS STILL A HIGHLY EXPERIMENTAL PROJECT. 
----------------
WE ARE STILL IN DEVELOPMENT STAGES. USE AT YOUR OWN RISK. WE ACCEPT NO LIABILITY IN ANY INSTANCE & NO GUARANTEE NOR WARRANTY IS PROVIDED. DEVELOPED FOR ENTERTAINMENT - USE IT FOR FUN !</b>

https://UNVS.com

Copyright (c) 2009-2014 Bitcoin Developers.
 
Copyright (c) 2011-2014 Litecoin Developers.  

Copyright (c) 2023 UNVS Developers.

UNVS WALLET NODES & COMMANDS
----------------

You can download our wallet releases from:

https://github.com/UnvsCom/Wallets

**Here is a list of our released & Trusted Node IP Addresses:**

78.141.242.233




**Here is a list of our ports:**

P2P Port: 2333

RPC Port: 2332

**Here is a list of our released DNS SEEDERS:**

seeder.unvse.com

seeder2.unvse.com

seeder3.unvse.com

seeder4.unvse.com

seeder5.unvse.com

seeder6.unvse.com

seeder7.unvse.com

seeder8.unvse.com

seeder9.unvse.com

seeder10.unvse.com

These are all HARDCODED into our wallet codebase to assist with auto sync on wallet load.

If we add more Trusted IP Nodes in the future, they will be published here only.

**DO NOT ADD UNKNOWN / UNTRUSTED IP NODES INTO YOUR WALLET.**



WALLET COMMANDS
---------------

Navigate to the top of the wallet window menu and select:
**Help > Debug Window**

Then select the **'Console'** tab from the small pop up window.

Then follow any of the most commonly used commands from the list below. (Press enter after typing any in)

To Start Mining, type:

```
setgenerate true
```

To Stop Mining, type:

```
setgenerate false
```

To add one of our listed Master IP nodes to sync to, type:
```
addnode IPADDRESS add
```

( replace IPADDRESS with the IP address )


Sometimes a port is also required, in this instance, type:

```
addnode IPADDRESS:PORT add
```

( example:     addnode 000.0.00.00:2332 add )


To remove an IP from the node list, type:

```
addnode IPADDRESS remove
```
To remove an IP with port from the node list, type:

```
addnode: IPADDRESS:NODE remove
```

For a full list of usable commands, type: 

```
help
```

A full list of console commands will be listed, but the above list are the most commonly used.









License
-------

UNVS is released under the terms of the MIT license. See `COPYING` for more
information or see http://opensource.org/licenses/MIT

Development process
-------------------

We are continually developing in-house with our own team, but we also receive assistance from freelance developers and community driven support.

We are still in the early stages. Bug fixes, patches and such like will be rolled out in stages. 

Use our services for FUN & Entertainment only !
