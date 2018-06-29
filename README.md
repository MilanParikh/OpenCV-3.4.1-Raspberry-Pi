# OpenCV 3.4.1 Precompiled for Raspberry-Pi
Prebuilt .deb files to save time 

# Instruction

## 1. apt update
```
$ sudo apt update
$ sudo apt upgrade
```
If you are busy, you can skip 'upgrade', but 'update' is necessary.

## 2. Download
```bash
~ $ git clone https://github.com/MilanParikh/OpenCV-3.4.1-Raspberry-Pi.git
~ $ cd OpenCV-3.4.1-Raspberry-Pi
~/OpenCV-3.4.1-Raspberry-Pi $ cd stretch/3.4.1
```
## 3. Installation
```
~/opencv-for-rpi/stretch/3.4.0 $ sudo apt-get install -y ./OpenCV*.deb
```
or
```
~/opencv-for-rpi/stretch/3.4.0 $ sudo dpkg -i ./*.deb
~/opencv-for-rpi/stretch/3.4.0 $ sudo apt install -f
```

## 3. Reboot
