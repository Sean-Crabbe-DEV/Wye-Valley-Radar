# Wye Valley Radar

This is a modified version of <a href="https://github.com/wiedehopf/tar1090">tar1090</a> that will be Embedded into the wye valley plane spotting website

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

## View the added webinterface

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


