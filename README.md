<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>
    <h1 align="center">
        <img src="https://github.com/Nightro-Fx/Gnome-Customization/blob/main/img/Gnome.png" width="40" alt="Logo"/> 
        Gnome Customization
    </h1>
  
  <p align="center">
  <a href="https://discord.gg/kNHaaFsGZ2">
    <img src="https://github.com/Nightro-Fx/Performance-FastFlags/blob/main/img/Discord_Join.png" alt="Join Now" width="150">
  </a>
</p>
<p align="center">
  <a href="https://www.youtube.com/@Nightro-Fx">
    <img src="https://github.com/Nightro-Fx/Performance-FastFlags/blob/main/img/Subscribe_Hover.png" alt="Sub Now" width="130">
  </a>
</p>
</body>
</html>


# Getting Started
###### We need to install a few applications which includes: Extension manager, Conky and Tweaks
```bash
sudo apt install gnome-shell-extension-manager
sudo add-apt-repository ppa:tomtomtom/conky-manager
sudo apt update
sudo apt install conky-manager2
sudo apt install gnome-tweaks
```
> [!TIP]
> Launch command are `extension-manager`, `gnome-tweaks` & `conky-manager2`

## Entension Manager
###### Install the following extentions which you can search for in the Browse tab
<img src="https://github.com/Nightro-Fx/Gnome-Customization/blob/main/img/Browse.png" width="370" alt="Logo"/> <img src="https://github.com/Nightro-Fx/Gnome-Customization/blob/main/img/Extensions.png" width="370" alt="Logo"/>

###### Or You can automate the process by running the following:
```bash
# Create temp dir
mkdir -p ~/gnome-extensions && cd ~/gnome-extensions

# Download extensions
wget -O appindicator.zip "https://github.com/Nightro-Fx/Gnome-Customization/raw/refs/heads/main/Gnome%20Extentions/appindicatorsupportrgcjonas.gmail.com.v60.shell-extension.zip"
wget -O arcmenu.zip "https://github.com/Nightro-Fx/Gnome-Customization/raw/refs/heads/main/Gnome%20Extentions/arcmenuarcmenu.com.v64.shell-extension.zip"
wget -O dash-to-panel.zip "https://github.com/Nightro-Fx/Gnome-Customization/raw/refs/heads/main/Gnome%20Extentions/dash-to-paneljderose9.github.com.v66.shell-extension.zip"
wget -O user-theme.zip "https://github.com/Nightro-Fx/Gnome-Customization/raw/refs/heads/main/Gnome%20Extentions/user-themegnome-shell-extensions.gcampax.github.com.v64.shell-extension.zip"

# Install extensions
gnome-extensions install --force appindicator.zip
gnome-extensions install --force arcmenu.zip
gnome-extensions install --force dash-to-panel.zip
gnome-extensions install --force user-theme.zip

# Enable extensions
gnome-extensions enable appindicatorsupportrgcjonas.gmail.com
gnome-extensions enable arcmenuarcmenu.com
gnome-extensions enable dash-to-paneljderose9.github.com
gnome-extensions enable user-themegnome-shell-extensions.gcampax.github.com
