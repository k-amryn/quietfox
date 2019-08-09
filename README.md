![quietfox](https://coekuss.com/quietfox/logo.png)
![](https://coekuss.com/quietfox/clean.png)

## The Goal
This userChrome mod was created to make the Firefox UI cleaner and more modern without sacrificing any of its original features. You can still use themes, and you can still use Compact Mode and Touch Mode. You can pretty much forget that you have a mod installed, it works *quietly* in the background. Here are some of the notable features:


## Customizable values 
Simply open userChrome.css in a text editor and change the values at the top of the file. Restart Firefox to see changes.

```CSS
/* -------------------- 🎨 Customization 🎨 -------------------- */
    --tab-corner-rounding: 7px;
    --animation-speed: 0.2s;
    --button-corner-rounding: 30px;
```
![](https://coekuss.com/quietfox/fluid.gif)

-----

```CSS
/* -------------------- 🎨 Customization 🎨 -------------------- */
    --tab-corner-rounding: 0px;
    --animation-speed: 0s;
    --button-corner-rounding: 0px;
```
![](https://coekuss.com/quietfox/snappy.gif)


## Menus that adapt to your theme
![](https://coekuss.com/quietfox/menus.jpg)

## Address bar buttons appear when needed
![](https://coekuss.com/quietfox/urlbar_buttons.gif)



## How to install
1. [Download](https://coekuss.com/quietfox/quietfox.zip) and unzip.
2. Go to [about:support](about:support) in Firefox and open your Profile Folder
3. Drop your unzipped "chrome" folder into the folder that appears.
4. Restart Firefox

---
✔ Tested on Firefox 68 on Windows 10 and Ubuntu 18.04

### Note about transparent themes
Although deliberate effort has been put into making this mod work with most themes, some transparent themes make menu text hard to read. Transparent themes also make the bottom corners of rounded tabs look wonky, so the file includes instructions to remove tabs' bottom corner rounding if you encounter this issue. I'd also recommend the extension [Firefox Color](https://addons.mozilla.org/en-US/firefox/addon/firefox-color/) to tune the colors to your taste.
