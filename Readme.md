Commands to be issued:
=======================
 (C) 2018 Shayantan , Prateek 

source ~/.profile 
workon cv
cd /home/pi/pi-home-surveillance
sudo modprobe bcm2835-v4l2

python pi_surveillance.py --conf conf.json