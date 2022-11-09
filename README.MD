![prototype scheme](https://raw.githubusercontent.com/maltsevvv/rpi_fan/master/fan.png) 
```
##### FAN Enable if temp < 65C
sudo nano /boot/config.txt
```
`dtoverlay=gpio-fan,gpiopin=14,temp=65000`

`sudo reboot` 
