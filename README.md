# MacType-Profile
Best mactype experience on Windows 10

## Preview
Windows 10:
![mactype1](/assets/mactype1.png)
![mactype2](/assets/mactype2.png)

Windows 11:
![image](https://user-images.githubusercontent.com/4571571/215567446-cede3325-49f0-4af9-9564-3db247c6add7.png)

## How to install
* Download and install [MacType](https://github.com/snowie2000/mactype/releases) *( If you are a c++ developer or atleast you are not strange with it, you can download latest updated source, and build it )*
* Download MacOS fonts and copy them into `C:\Windows\Fonts` *(also you can Install fonts by right-click on fonts and click **Install**)*
  * You can download [Recommended fonts](https://github.com/blaisck/sfwin)
* Adjust your windows 10 scale to `125%`
  * For changing of Windows 10's scale, you need to Right-click on Desktop, click on *Advanced scaling settings* under **Scale and layout**
* Download and copy `MacType-Arash.ini` profile into `%ProgramFiles%\MacType\ini`
* Run wizard, select `Tray Mode` ( as the creator said ), and select `MacType-Arash v2.0`
* **Enjoy the ride :heart::boom:**

## Workarounds
### `:` Character showing unspecified glyph for some fonts in TaskBar clock
POSSIBLE WORKAROUND: [Windows 10 System Tray Clock COLON Issue Workaround](https://github.com/iamr8/MacType-Profile/issues/4#issue-928437139)

### Use in Google Chrome, Microsoft Edge and Mozilla Firefox
* Download [Tampermoney](https://www.tampermonkey.net/) addons for your own Browser
* Download `mactype.user.js` from https://github.com/syhyz1990/mactype ( For more question, You need to translate the repo to your own language )
* Drag and Drop it into Browser ( while you've installed tampermonkey )

## Known Issues
Our current font (MacOS Font) doesn't respect the Windows font system. Accordingly, you might encounter a **square glyph** for certain characters of non-English texts. *Workarounds are being welcomed* :heart:
