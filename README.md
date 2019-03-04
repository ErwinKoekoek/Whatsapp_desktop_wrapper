# Whatsapp_desktop_wrapper
- Whatsapp Desktop Wrapper for debian/ubuntu

## Tested on
- Ubuntu 16.04/18.04
- Debian Strech
- Elementary OS

## pre requirements
$ sudo apt-get install wmctrl chromium-browser -y

## Install
$ sudo mkdir -p /opt/whatsapp/<br/>

#### Copy files
$ sudo wget https://raw.githubusercontent.com/ErwinKoekoek/Whatsapp_desktop_wrapper/master/whatsapp.png -O /opt/whatsapp/whatsapp.png<br/>
$ sudo wget https://raw.githubusercontent.com/ErwinKoekoek/Whatsapp_desktop_wrapper/master/start-whatsapp -O /opt/whatsapp/start-whatsapp<br/>
$ sudo wget https://raw.githubusercontent.com/ErwinKoekoek/Whatsapp_desktop_wrapper/master/whatsapp.desktop -O /opt/whatsapp/whatsapp.desktop<br/>

#### Rights
$ sudo chmod +x /opt/whatsapp/start-whatsapp<br/>
$ sudo cp /opt/whatsapp/whatsapp.desktop /usr/share/applications/whatsapp.desktop<br/>
$ sudo rm /opt/whatsapp/whatsapp.desktop 1>/dev/null 2>&1<br/>

#### Create shortcut
$ sudo ln -s /opt/whatsapp/whatsapp.desktop ~/whatsapp.desktop<br/>
