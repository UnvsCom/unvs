UNVS
=============

<b>PLEASE NOTE THIS IS STILL A HIGHLY EXPERIMENTAL PROJECT. 
----------------
WE ARE STILL IN DEVELOPMENT STAGES. USE AT YOUR OWN RISK. WE ACCEPT NO LIABILITY IN ANY INSTANCE & NO GUARANTEE NOR WARRANTY IS PROVIDED. DEVELOPED FOR ENTERTAINMENT - USE IT FOR FUN !</b>

https://UNVS.com

Copyright (c) 2009-2014 Bitcoin Developers.
 
Copyright (c) 2011-2014 Litecoin Developers.  

Copyright (c) 2023 UNVS Developers.

UNVS WALLET RELEASES
----------------

**WINDOWS** exe release download link:  https://github.com/UnvsCom/Wallets

**LINUX** release download link: https://github.com/UnvsCom/Wallets

(Standed installation & allow through firewall.)

**ADVANCED:** You can also clone our most recent git to compile your own wallet. Don't forget to install the required dependancies.

While the following instructions may seem rather 'unusual' to everyday developers, the following Ubuntu based set-up allows for a more novice audience to compile our git repo with all the required dependancies preinstalled on an Ubuntu system. 

This is posted for educational audiences/purposes. We believe the more recent amatuer crypto enthusiasts should have the chance to learn basic crypto codebase as many maximalists got the chance to do so originally.


BUILD VIA PREMADE VIRTUALBOX DESKTOP IMAGE (EDUCATIONAL RESOURCE)
----------------
USE AT YOUR OWN RISK. PROVIDED WITHOUT WARRANTY OR GUARANTEE.

✪ UBUNTU 16 XENIAL PREINSTALLED + (All coin compile dependancies also preinstalled at time of this publication. No updates required.)

username: ubuntu

password: password



**TO BEGIN** 


✪ On a Windows Machine.

✪ Install ORACLE VM VirtualBox 7:  
https://www.virtualbox.org/wiki/Downloads

✪ Download our premade virtual machine OVA file image.  
https://

✪ Import this VM OVA file via the VirtualBox interface menu:  **FILE >  IMPORT APPLIANCE**

Once loaded in, click the **'Green Start Arrow'** button to load the prebuilt Ubuntu system.

Once you are on the Desktop, click the Terminal icon to load terminal window and type/paste in the following commands:

(NOTE: Change branch version in following string to reflect currect release)
```
cd Desktop

git clone --single-branch --branch v1.6 https://github.com/unvscom/unvs.git
```
ALTERNATIVELY
```
cd Desktop

git clone https://github.com/unvscom/unvs.git
```

Once repo is cloned to Desktop, in terminal navigate to **/src folder** with following command and compile code by typing:

```
cd Desktop/unvs/src

make -f makefile.unix
```

Once completed, in terminal navigate back to the **/unvs folder** with following command and compile code by typing:

```
cd ..

qmake
```

Once completed and staying in the **/unvs folder**, type the following command into the terminal to compile codebase:

```
make
```


Once this has completed and staying in the **/unvs folder**, launch the wallet with the following command:

```
./unvs-qt
```

The Wallet client should then auto sync with the network. Peer connections can be seen in the bottom right of the wallet window. Hover mouse cursor over connection icon for total connections obtained from your location.




**FOR WALLET FILE LOCATIONS**
-----------------------------
DEPENDING ON OS. NAVIGATE TO THE FOLLOWING:

**Windows Systems:**
C:\Users\USERNAME\AppData\Roaming\UNVS

(Replace USERNAME with your Windows Username)

**Ubuntu Systems:**
$HOME   or  Home (Folder)

Once you navigate to the 'Home' folder, press CTRL+H and the hidden **.unvs folder** will appear.

✪ The main wallet file is called **wallet.dat**

✪ You can choose to copy the whole contents of this folder or whichever parts you require to back these up ay any time.

✪ For a fresh wallet install, ensure that the appropriate UNVS related Windows or Ubuntu folder is emptied first (after backing the contents up), then install.

✪ If you do a fresh install of the wallet client and desire to use the old data, simply navigate to the folder and back up and delete the newly generated contents, then paste in the old folder contents in replacement, then reload wallet.

✪ Remember, modifying and replacing operational folder contents is HIGHLY RISKY and you must ensure to be disciplined & experienced enough to do this! 




License
-------

UNVS is released under the terms of the MIT license. See `COPYING` for more
information or see http://opensource.org/licenses/MIT

Development process
-------------------

We are continually developing in-house with our own team, but we also receive assistance from freelance developers and community driven support.

We are still in the early stages. Bug fixes, patches and such like will be rolled out in stages. 

Use our services for FUN & Entertainment only !
