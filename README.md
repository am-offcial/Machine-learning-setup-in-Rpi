# Setting up Machine Learning in Raspberry pi via MacBook 
This Process includes setting up the Raspberry pi headlessly (remote configuration) 

## Step 1 : Install Raspberry pi Imager for the provided link
    https://downloads.raspberrypi.org/imager/imager_latest.dmg
  Install the raspberry pi imager
 
  Choose the device model ( i.e : Raspberry pi 3 Model B+ , Raspberry pi Pico ,Raspberry pi 4)
  
  Choose the Storage  ( Minimum required space : 32 GB ) for flawless performance
  
  Select the Required Operating System
   
  Raspberry Pi 64 bit or Raspberry Pi 32 bit or   Raspberry Pi Leagacy
  
  Choose the OS with respect to the Raspberry PI you own becase some of the RPI works smooth in bit system

  click command + Shift + n , It opens an dialogue box 

  Under General edit the Username and set a password

  If you wish to connect using your mobile hostspot  fill the SSID and Password 

  Then We need to enable SSH in Raspberry PI

  Click the SERVICES besides to GENERAL and enable SSH and  enable Password authorization

  Then Click NEXT

  It usually takes some time to write and also verify it after that a successful message will be displayed

 ## Step 2 : Ping Raspberry Pi

Insert the micro SD card into the raspberry pi

Power on the Raspberry pi (always use RPI adapter ) Power mismatch affects the Raspberry Pi

Open the Terminal and type the following command

           ping raspberrypi.local 
           
if the above commad does not work then use

            ping raspberrypi

If is works then it will display

PING raspberrypi <Raspberrypi's IP >: 56 data bytes

64 bytes from <Raspberrypi's IP>: icmp_seq=0 ttl=64 time=34.420 ms

if both of the methods doesn't work then add the ip address to the known host 

Enter the following command in the terminal

        sudo nano /etc/hosts

add the ip address and add the host name (i.e Eg: 192.168.XXX.XXX   raspberrrypi )

and try pinging the raspberrypi

## Step 3 : Connect Via SSH

For MAcbook users Opne system preference -> Shairing -> Enable Remote Login.

After that quit and restart your terminal

Enter the following command in terminal

        ssh username@raspberrypi
        
username -> The name you set during the OS booting

raspberrypi  -> Hostname or enter the IP address

Enter the password of your Raspberry pi

An yes or No will be asked (Type = 'yes')

Then your directory will be changed to raspberry pi

## Step 4 : Connect Via VNC

Download and install VNC viewer

        https://www.realvnc.com/en/connect/download/viewer/macos/

To connect via VNC we need to enable VNC in the raspberry pi

go to the RPI terminal whihcis connected via ssh and type the following command

        raspi-config

A Window will be opened in that select Interface -> Vnc Server -> Enable 

And Enter the raspberry pi IP address in the VNC Viewer Box and a pop up window will be enabled 

Enter your Username if asked and enter your Raspberry pi Password and click connect

Now you can remote desktop the Raspberry pi 

## Step 5 : Installing Dependencies

First always update and upgrade the Raspberyy pi software

        sudo apt update
        sudo apt upgrade

To install PIP use the following commands


## Step 6 : Creating a Virtual environment

to creata 










  

  
  
    


