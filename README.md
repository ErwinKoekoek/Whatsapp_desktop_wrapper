#Whatsapp_desktop_wrapper<br/>
Whatsapp Desktop Wrapper for debian/ubuntu

**Tested on**<br/>
- Ubuntu 16.04/18.04
- Debian Strech
- Elementary OS

**pre requirements**<br/>
$ sudo apt-get install wmctrl chromium-browser -y

**Install**<br/>
$ sudo mkdir -p /opt/whatsapp/<br/>
$ sudo wget https://raw.githubusercontent.com/ErwinKoekoek/Whatsapp_desktop_wrapper/master/whatsapp.png -O /opt/whatsapp/whatsapp.png<br/>
$ sudo wget https://raw.githubusercontent.com/ErwinKoekoek/Whatsapp_desktop_wrapper/master/start-whatsapp -O /opt/whatsapp/start-whatsapp<br/>
$ sudo wget https://raw.githubusercontent.com/ErwinKoekoek/Whatsapp_desktop_wrapper/master/whatsapp.desktop -O /opt/whatsapp/whatsapp.desktop<br/>

$ sudo chmod +x /opt/whatsapp/start-whatsapp<br/>
$ sudo cp /opt/whatsapp/whatsapp.desktop /usr/share/applications/.<br/>

$ sudo rm /opt/whatsapp/whatsapp.desktop 1>/dev/null 2>&1<br/>

$ sudo ln -s /opt/whatsapp/whatsapp.desktop ~/.<br/>

