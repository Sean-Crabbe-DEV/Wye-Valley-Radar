# Wye Valley Plane Spotting Radar & Website

![Screenshot1](https://github.com/Sean-Crabbe-DEV/Wye-Valley-Radar/blob/main/screenshots/main.jpg)

This is the repository for the official Wye Valley Plane Spotting website & radar. The website is based on bootstrap 4 and the radar is a customised version of <a href="https://github.com/wiedehopf/tar1090">tar1090</a> 

the radar (tar1090) needs to be supplied with data or no aircraft will be displayed i suggest using a program such as dump1090 to supply the data
```
sudo apt-get install dump1090-fa
```

## Installation

```
git clone https://github.com/Sean-Crabbe-DEV/Wye-Valley-Radar.git
cd Wye-Valley-Radar/
chmod +x install.sh
sudo ./install.sh
```

## Uninstall
```
chmod +x uninstall.sh
sudo ./uninstall.sh
sudo rm /etc/default/tar1090
```

```
cd ~
sudo rm -r Wye-Valley-Radar/
```

## The radar web interface

Click the following URL and replace the IP address with address of your Raspberry Pi:

http://192.168.x.yy/tar1090


If you are curious about your coverage, try this URL:

http://192.168.x.yy/tar1090/?pTracks


## Keyboard Shortcuts

- Q and E zoom out and in.
- A and D move West and East.
- W and S move North and South.
- C or Esc clears the selection.
- M toggles multiselect.
- T selects all aircraft
- B toggle map brightness


