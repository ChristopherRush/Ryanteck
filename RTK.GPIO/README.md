# RTK.GPIO Python Library

<img src="https://drive.google.com/uc?id=1WCpukpmTQwl-og_CEDyViTiW0BDwfyT4" width="400" height="400">

The RTK GPIO board allows you to connect the world of physical computing to you desktop PC or laptop. The RTK GPIO board emulates the original Raspberry Pi 28-pin GPIO header allowing you to program for the Raspberry Pi on your computer. The board is fully compatible with Windows, Mac OS and Linux and supports a range of programming languages such as Python, Java and also use with Scratch.

The board connects to your computer using a micro USB cable (not supplied), which also provides power to the board.

## Linux

The following guide has been tested to work with Debian Linux, in particular on the Raspberry Pi computer itself. There are a number of dependancies that also need to be installed such as some Python3 modules. To install the RTk.GPIO library there are just 4 simple steps:

1. Permission Change

To begin we are going to first add the user to the "dialout" group. This means after installation you don't have to use sudo to run the python programs.

Open the Linux temrinal and type i the following command:
```bash
sudo usermod -a -G dialout $USER
```

2. Python Requirements

Now we are going to make sure that Python and its libraries are installed. For the RTk.GPIO library we need to use Python3 packages. Open up the temrinal and type in the following command:

```bash
sudo apt-get install python3-pip python3-setuptools python3-wheel
```

3. Reboot and Plug in

To make sure everything installed ok and is in sync it is recommended to initialise a reboot. While some aspects will work you may experience issues without a reboot.

After rebooting your Linux OS you can now insert your RTk.GPIO board into your Linux PC or Raspberry Pi. When you insert the USB cable you should see the Red LED light up.

4. Installing the Library

There are a couple of ways you can install the RTk.GPIO library. The easiest way is to use the Python in Package (PIP) management system. To install the RTk.GPIO library use the following command form the terminal:

```bash
sudo -H pip3 install RTk
```

Alterntaviely if you download this GitHub repository you can run the following command:

```bash
sudo python setup.py install
```

## Mac OS

## Windows
