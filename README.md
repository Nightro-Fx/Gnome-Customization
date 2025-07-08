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
sudo add-apt-repository ppa:ubuntuhandbook1/conkymanager2
sudo apt update
sudo apt install conky-manager2
sudo apt install gnome-tweaks
sudo apt install playerctl
```
> [!TIP]
> Launch command are `extension-manager`, `gnome-tweaks` & `conky-manager2`

## Entension Manager
###### Install the following extentions which you can search for in the Browse tab
<img src="https://github.com/Nightro-Fx/Gnome-Customization/blob/main/img/Browse.png" width="370" alt="Logo"/> <img src="https://github.com/Nightro-Fx/Gnome-Customization/blob/main/img/Extensions.png" width="370" alt="Logo"/>

###### Such extentions can be found in the offical website:
```bash
xdg-open "https://extensions.gnome.org/extension/19/user-themes/"
xdg-open "https://extensions.gnome.org/extension/1160/dash-to-panel/"
xdg-open "https://extensions.gnome.org/extension/3628/arcmenu/"
xdg-open "https://extensions.gnome.org/extension/615/appindicator-support/"
```
> [!TIP]
> To hide the Application Button, Go into Dash to Panel settings using the extention manager and **deselect** the `visible` button of "Show Application button". As an alternative press **Windows Key + A**.

## Conky
### Setting up Widgets:
###### For this tutorial we will use the Antares widget, You can choose your own [here](https://www.gnome-look.org/browse?cat=124&ord=latest)
```bash
xdg-open "https://www.gnome-look.org/p/1831404" 
```
###### Extract the file into the following directory
```bash
xdg-open ~/.config/conky
```
###### Remove the pre-installed widget (Optional)
```bash
rm -r ~/.conky
```
###### Besure to refresh the list every time you make any changes
<img src="https://github.com/Nightro-Fx/Gnome-Customization/blob/main/img/Refresh.png" width="370" alt="Logo"/>

###### Select & Toggle the widget of your choice. 
<img src="https://github.com/Nightro-Fx/Gnome-Customization/blob/main/img/Toggle%26Select.png" width="370" alt="Logo"/>

###### Click on the Edit Widget button
<img src="https://github.com/Nightro-Fx/Gnome-Customization/blob/main/img/Edit_Widget.png" width="370" alt="Logo"/>

###### In the transparency tab, Select Transparent within the dropdown and click Apply.
<img src="https://github.com/Nightro-Fx/Gnome-Customization/blob/main/img/Transparent.png" width="370" alt="Logo"/>

### Setting up the weather:
> [!TIP]
> If your temprature is blank then run: `[ -f ~/.cache/weather.json ] || touch ~/.cache/weather.json` in your terminal.
> After that execute the `weather-v2.0.sh` as a program
