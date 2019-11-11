![quietfox](https://coekuss.com/quietfox/logo.png)
![](https://coekuss.com/quietfox/quietfox70/clean2.png)

## The Goal
This userChrome mod was created to make the Firefox UI cleaner and more modern without sacrificing any of its original features. You can still use themes, and you can still use Compact Mode and Touch Mode. You can pretty much forget that you have a mod installed, it works *quietly* in the background. Here are some of the notable features:


## Customizable values 
Simply open userChrome.css in a text editor and change the values at the top of the file. Restart Firefox to see changes.

```CSS
/* -------------------- 🎨 Customization 🎨 -------------------- */
    --tab-corner-rounding: 7px;
    --animation-speed: 0.4s;
    --button-corner-rounding: 20px;
```
![](https://coekuss.com/quietfox/quietfox70/fluid2.gif)

-----

```CSS
/* -------------------- 🎨 Customization 🎨 -------------------- */
    --tab-corner-rounding: 0px;
    --animation-speed: 0s;
    --button-corner-rounding: 0px;
```
![](https://coekuss.com/quietfox/quietfox70/snappy2.gif)


## Theme-adapted menus
![](https://coekuss.com/quietfox/menus.jpg)

## Address bar buttons appear when needed
![](https://coekuss.com/quietfox/urlbar_buttons.gif)



## How to install
1. [Download](https://github.com/coekuss/quietfox/releases/download/v2.0/quietfox70.zip) and unzip
2. Go to `about:support` in Firefox and open your Profile Folder
3. Drop your unzipped "chrome" folder into the folder that appears
4. Go to `about:config` in your Firefox and set the value of `toolkit.legacyUserProfileCustomizations.stylesheets` to `true` (this enables the loading of userChrome mods)
5. Restart Firefox


✔ Tested on Firefox 70 on Windows 10

---

### Older version
If you need Quietfox for Firefox 68 or 69, [here it is.](https://github.com/coekuss/quietfox/releases/download/v1.0/quietfox69.zip)

### Note about transparent themes
Although deliberate effort has been put into making this mod work with most themes, some transparent themes make menu text hard to read. Transparent themes also make the bottom corners of rounded tabs look wonky, so the file includes instructions to remove tabs' bottom corner rounding if you encounter this issue. I'd also recommend the extension [Firefox Color](https://addons.mozilla.org/en-US/firefox/addon/firefox-color/) to tune the colors to your taste.

## P. S.
This mod is the product of many late nights of zen laser focus. If it enhances your web experience, consider donating a small sum to show your support ❤

<img align="top" width="25px" src="https://coekuss.com/quietfox/bitcoin.png"> Bitcoin: 1Lc5r26FTwWSLNH46fE5WH3mvFjNUcHGzi

<img align="top" width="20px" src="https://coekuss.com/quietfox/paypal.png"> PayPal: [paypal.me/coekuss](https://paypal.me/coekuss)
