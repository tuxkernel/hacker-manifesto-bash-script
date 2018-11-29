# hacker-manifesto-bash-script
This bash script reproduce "The conscience of a hacker" by The Menthor (Loyd Blankenship) and show you as screensaver-text

**Requirements:**

- bash (4.4.12 or above)
- pv (1.16 or above)

**Installation and execution:**

The script requires bash and pv programs installed before. Open a terminal and type:

**$ sudo apt-get install bash pv**

Then download it:

**$ wget https://github.com/tuxkernel/hacker-manifesto-bash-script/archive/master.zip**

and unzip it:

**$ unzip master.zip**

Navigate to directory:

**$ cd hacker-manifesto-bash-script-master/**

Now move the script to /usr/bin/:

**$ sudo cp hacker-manifesto /usr/bin**

and make executable:

**$ sudo chmod +x /usr/bin/hacker-manifesto**

and change the owner. For example:

**$ sudo chown blackout:blackout /usr/bin/hacker-manifesto**

**NOTE:** Change **blackout:blackout** for your user name.

Finally, just run as:

**$ hacker-manifesto

You can stop it with:

**CTRL + Z**

That's all. Enjoy it!

**Tuxkernel...**
