![quietfox](https://coekuss.com/quietfox/logo.png)
![](https://coekuss.com/quietfox/quietfox70/clean2.png)

## The Goal
This userChrome mod was created to make the Firefox UI cleaner and more modern without sacrificing any of its original features. You can still use themes, and you can still use Compact Mode and Touch Mode. You can pretty much forget that you have a mod installed, it works *quietly* in the background. Here are some of the notable features:


## Customizable values 
Simply open userChrome.css in a text editor and change the values at the top of the file. Restart Firefox to see changes.

### Toolbar Customizations

```CSS
/* -------------------- 🎨 Customization 🎨 -------------------- */
    --tab-corner-rounding: 7px;
    /* --menu-corner-rounding: 10px; */
    /* --menu-item-height: 30px;     */
    --button-corner-rounding: 20px;
    --animation-speed: 0.4s;
```
![](https://coekuss.com/quietfox/quietfox70/fluid2.gif)

<br>

```CSS
/* -------------------- 🎨 Customization 🎨 -------------------- */
    --tab-corner-rounding: 0px;
    /* --menu-corner-rounding: 10px; */
    /* --menu-item-height: 30px;     */
    --button-corner-rounding: 0px;
    --animation-speed: 0.0s;
```
![](https://coekuss.com/quietfox/quietfox70/snappy2.gif)

### Menu Customizations
```CSS
/* -------------------- 🎨 Customization 🎨 -------------------- */
    /* --tab-corner-rounding: 7px;     */
    --menu-corner-rounding: 10px;
    --menu-item-height: 30px;
    /* --button-corner-rounding: 20px; */
    /* --animation-speed: 0.4s;        */
```

<p align="center">
    <img src="https://coekuss.com/quietfox/tall_rounded.png">
</p>

<br>

```CSS
/* -------------------- 🎨 Customization 🎨 -------------------- */
    /* --tab-corner-rounding: 7px;     */
    --menu-corner-rounding: 0px;
    --menu-item-height: 25px;
    /* --button-corner-rounding: 20px; */
    /* --animation-speed: 0.4s;        */
```
<p align="center">
    <img src="https://coekuss.com/quietfox/short_sharp.png">
</p>


## Theme-adapted menus
![](https://coekuss.com/quietfox/menus72.jpg)

## Address bar buttons appear when needed
![](https://coekuss.com/quietfox/urlbar_buttons.gif)



## How to install
1. [Download](https://github.com/coekuss/quietfox/releases/download/v5/quietfox75.zip) and unzip
2. Go to `about:support` in Firefox and open your Profile Folder
3. Drop your unzipped "chrome" folder into the folder that appears
4. Go to `about:config` in your Firefox and set the value of `toolkit.legacyUserProfileCustomizations.stylesheets` to `true` (this enables the loading of userChrome mods)
5. Restart Firefox


✔ Tested on Firefox 75 on Windows 10 and Ubuntu 19.10

---

### Older version
If you need Quietfox for an older version of Firefox, [see the releases page.](https://github.com/coekuss/quietfox/releases)

### Note about transparent themes
Although deliberate effort has been put into making this mod work with most themes, some transparent themes make menu text hard to read. Transparent themes also make the bottom corners of rounded tabs look wonky, so the file includes instructions to remove tabs' bottom corner rounding if you encounter this issue.

## P. S.
This mod is the product of many late nights of zen laser focus. If it enhances your web experience, consider donating a small sum to show your support ❤

<img align="top" width="25px" src="https://coekuss.com/quietfox/bitcoin.png"> Bitcoin: 1Lc5r26FTwWSLNH46fE5WH3mvFjNUcHGzi

<img align="top" width="20px" src="https://coekuss.com/quietfox/paypal.png"> PayPal: [paypal.me/coekuss](https://paypal.me/coekuss)
