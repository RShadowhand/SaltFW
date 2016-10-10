# SaltFW

Slim Alternative Firmware for 3DS!  
### Features: 
- **Arm9loaderhax only.**
- **No EmuNAND Support.**
- **No payload chainloading.**
- **No config, perfect for minimalists and children.**
- Automatic **firmware protection** patching for all FIRMs.
- Automatic signature check patching.
- Automatic TWL/AGB patching.
- Automatic region-free patching.
- Automatic reboot patching.
- Optional splash screen.
- Optional region/language patching.
- Optional firmware.bin loading for NTR.
- **Install and forget.**

### How to install standalone:
1. **FOR A9LH**: Drop `arm9loaderhax.bin` to the root of your SD.
2. **FOR ShadowNAND**: Drop `boot.bin` to the root of your SD.
3. DONE!

### How to install and use with a bootmanager:
1. Drop `SaltFW.bin` to `SD:/ShadowNAND/`. **OR** drop `boot.bin` to either `SD:/ShadowNAND/` or SD root.
2. Set your choice of bootmanager to load the file as default.
3. DONE!

### How to use splash/bootlogo
1. Create `ShadowNAND/` folder in the root of your SD.
2. Put `splash.bin` **OR** `splashbottom.bin` **OR** **BOTH** in `ShadowNAND/` folder
3. DONE!

### How to use `firmware.bin`
1. Download [this](http://www70.zippyshare.com/v/Fbj6n1vB/file.html).
2. Put `firmware.bin` from the folder for your device, to `SD:/ShadowNAND`.
3. DONE!

### How to use Region/Language emulation
1. Create `/ShadowNAND/` folder in the root of your SD.
2. Create `_locales` folder in `ShadowNAND`.
3. Create a `txt` file titleID of the game you want to edit. (e.g. `0004000000055E00.txt`)
4. Inside the file, put `RGN LN` where RGN is the region code, and LN is the language code. (e.g. `JPN JP`)
5. DONE!

### Compiling
You'll need armips, [bin2c](https://sourceforge.net/projects/bin2c/), and a recent build of [makerom](https://github.com/profi200/Project_CTR) added to your PATH. [HERE](http://www91.zippyshare.com/v/ePGpjk9r/file.html) is a pre-compiled version of armips for Windows.  
Then, just run "make" and everything should work!  
You can find the compiled files in the 'out' folder.

### Credits
AuroraWright for her great coding.  
TuxSH for helping with Luma3DS.  
Rei for his initial ground work.  
And everyone else they mentioned in their credits sections.  

### License
See `LICENSE.txt`
