# This project has been ported into FigmaPlus. Please check this repository instead.
https://github.com/figma-plus/figma-plus

---

# Figma Plugins Panel — v.2.0.2
The unofficial plugins panel for Figma App.  

[Changelog](#new-in-this-version)  
[Download & Installation](#download-and-installation)  
[How to use](#how-to-use-the-panel)    
[Faqs and Troubleshooting](#faqs-and-troubleshooting)  

![alt text](https://raw.githubusercontent.com/PaperTiger/figma-plugins/master/cover.jpg?token=AHoqgaAnAQoQtEygmvWrsvbW781LSID-ks5apoIFwA%3D%3D "Figma Plugin Panel Cover")

---

## Changelog

#### 2.0.2
**General**
- Update Mac Desktop Client to the test Figma release (63)
  [Download Figma Desktop App (Mac)](https://www.dropbox.com/s/16a3rquisr112ap/figma-app-latest.zip?dl=0)



#### 2.0.1 
**Dark UI Plugin**
- Fix color issue on Comments Panel
- Improved Support for the Emoji Panel
- Fix SVGs color bug on Windows
- Improved color for texts on selected input field

#### 2.0 

**General**
- [NEW] Completely revamped Plugin Panel now using React
- [NEW] Panel is now available natively on the Desktop Figma App on Mac. [Download the client below](#download-and-installation).
- [NEW] Added a new extension for Firefox. [Download the extension](#download-and-installation).
- [NEW] Added a PDF Export Plugin, Credits (https://figma-pdf.gweltaz-calori.com/)  

**Dark UI Plugin**
- [NEW] Better and improved color palette  
- [NEW] Now the File's Background color will change when the plugin is activated and the Canvas selected  
- [IMPROVEMENT] Better browser support  
- [FIX] A lot of bug fixes 

#### 1.0.5
- [IMPROVEMENT] Bug Fixes, Better browsers support

#### 1.0
- Initial Release

---

## How to Use the Panel
Look for the ```Plugin Panel Button``` on the toolbar.

![alt text](https://raw.githubusercontent.com/PaperTiger/figma-plugins/master/panel-preview.png "Figma Plugin Panel Preview")
---

## Faqs and Troubleshooting

### Desktop App
#### I'm getting the error 'Figma is damaged and can't be opened' when I launch the Figma Desktop App.
To solve this issue follow those steps:

1. Launch this Terminal command: ```sudo spctl --master-disable```
2. Go to ```System Preferences > Security and Privacy```, then select ```Anywhere``` from the ```Allow apps downloaded from:``` section.

#### I can't find the Plugin Icon.
The Plugin Button is available on the ```File Browser``` and the ```Editor``` toolbars. If the button doesn't show up, try to close and restart either the app or the browser. If problems persist, send us a email.

#### Is there any Desktop App Client for Windows?
- We don't support a of the Plugins Panel on Windows at the moment. If you're interested making a port for Win, get in touch with us at team@papertiger.com

--

### Dark Theme Plugin
#### The rulers' color is still white.
At the moment there's no way to change the colors / theme of the rulers on Figma. 

#### Some UI elements look unstyled.
If you spot something weird on the UI feel free to shoot us a screenshot at team@papertiger.com

--

### Generate PDF Plugin
#### I'm getting the error 'The file key is invalid'
Make sure to turn on ```Public Access``` on your file by clicking on the ```Share Button``` then ```Enable link access```

---

## For any other issue or question, send us an email at team@papertiger.com
