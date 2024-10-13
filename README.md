# Setting up Machine Learning in Raspberry pi via MacBook 
This Process includes setting up the Raspberry pi headlessly (remote configuration) 

## Step 1 : Install Raspberry pi Imager for the provided link
    https://downloads.raspberrypi.org/imager/imager_latest.dmg
  Install the raspberry pi imager
 
  Choose the device model ( i.e : Raspberry pi 3 Model B+ , Raspberry pi Pico ,Raspberry pi 4)
  
  Choose the Storage  ( Minimum required space : 32 GB ) for flawless performance
  
  Select the Required Operating System
  
  Raspberry Pi 64 bit 
  
  Raspberry Pi 32 bit
  
  Raspberry Pi Leagacy
  
  Choose the OS with respect to the Raspberry PI you own becase some of the RPI works smooth in bit system

  click command + Shift + n , It opens an dialogue box 

  Under General edit the Username and set a password

  If you wish to connect using your mobile hostspot  fill the SSID and Password 

  Then We need to enable SSH in Raspberry PI

  Click the SERVICES besides to GENERAL and enable SSH and  enable Password authorization

  Then Click NEXT

  It usually takes some time to write and also verify it after that a successful message will be displayed

 ## Step 2 : TO Connect via SSH

Insert the micro SD card into the raspberry pi

Power on the Raspberry pi (always use RPI adapter ) Power mismatch affects the Raspberry Pi

Open the Terminal and type the following command

           ping raspberrypi.local 
           
if the above commad does not work then use

            ping raspberrypi

If is works then it will display

PING raspberrypi <Raspberrypi's IP >: 56 data bytes

64 bytes from <Raspberrypi's IP>: icmp_seq=0 ttl=64 time=34.420 ms






  

  
  
    


