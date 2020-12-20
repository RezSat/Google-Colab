Follow the Steps to configure it correctly,

## Step 1:

Go to ngrok website and make a account : https://ngrok.com

Find your auth token : https://dashboard.ngrok.com/auth/your-authtoken

Copy the auth token and save it somewhere safe.

## Step 2:

Download Turbo VNC

TurboVNC Download Link :

32Bit

https://tenet.dl.sourceforge.net/project/turbovnc/2.2.5/TurboVNC-2.2.5-x86.exe

64Bit

https://tenet.dl.sourceforge.net/project/turbovnc/2.2.5/TurboVNC-2.2.5-x64.exe

## Step 3:

Go to https://colab.research.google.com/

upload guicolab.ipynb file (which is jupyter notebook file extension)

make sure Runtime Type is set to GPU, you can find it on the navigation bar -> Runtime -> change runtime type and set it to GPU.

## Step 4:

Click on the run icon/play button like icon in the "Start GUI Colab" section.

It will do all the things for you automatically.

At the sartup it will ask you to type the ngrok Auth Token, then copy it and paste it there and hit enter.

## Step 5:
After finishing all the installs/downloads it will show up as screen like this,
```
✂️✂️✂️✂️✂️✂️✂️✂️✂️✂️✂️✂️✂️✂️✂️✂️✂️✂️✂️✂️✂️✂️✂️✂️
root password: 12345678
colab password: 12345678
✂️✂️✂️✂️✂️✂️✂️✂️✂️✂️✂️✂️✂️✂️✂️✂️✂️✂️✂️✂️✂️✂️✂️✂️
Ready to Connect TurboVNC viewer:
Your ngrok address : your ngrok port
✂️✂️✂️✂️✂️✂️✂️✂️✂️✂️✂️✂️✂️✂️✂️✂️✂️✂️✂️✂️✂️✂️✂️✂️
VNC password: 12345678
VNC view only password: 87654321
✂️✂️✂️✂️✂️✂️✂️✂️✂️✂️✂️✂️✂️✂️✂️✂️✂️✂️✂️✂️✂️✂️✂️✂️

```

where "Your ngrok address" & "your ngrok port" will be replace with yours respectively.

Open the Turbo VNC(vncviewer.exe) and it will ask you to type VNC Server then copy the full line which shows "Your ngrok address:your ngrok port" and paste it on there in the VNC viewer and click 'connect'.

It will ask you a password and give it "VNC password" value , which is 12345678 and now you will be connected automatically, enjoy ! and to run it 12 hours, go to the section where it shows " Script Google Colab Keep Running 12 Hours" and double click on it, it show you the javascript code , copy that code and Open Developer  Tools(Edge : Ctrl + Shift + I, Chrome : Ctrl + Shift + J, etc. It will different from your browser and os, so find it your own.)

After opening Developer Tools, switch to the Console Tab , paste the javascript code and hit enter.


## Setup Ethereum Miner on Google Colab:

```
sudo add-apt-repository ppa:ethereum/ethereum
sudo apt update
sudo apt install ethereum
sudo apt-key adv --keyserver keyserver.ubuntu.com  --recv-keys 2A518C819BE37D2C2031944D1C52189C923F6CA9
sudo apt update
sudo apt install ethereum

download the latest version and unzip with " tar -xvf filename" and make sure you are in root mode, use 'sudo su ' for long term root mode)
https://github.com/ethereum-mining/ethminer/releases

at last inside the folder on ethminer (where ever it extracts) type the below command,
./ethminer -G -P stratum1+tcp://YOUR_ETHEREUM_ADDRESS@us1.ethpool.org:3333


```

# Done !


Donations:
```
Ethereum : 0xdDa3f78891ddBA5F3cf8476716df8e0fa328418d
Paypal : paypal.me/cyberrex599
Patreon : patreon.com/yehanwasura

```

# Thank You,