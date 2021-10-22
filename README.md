# Rubber Ducky Password Stealer

With this software it is possible to retrieve user passwords from a Windows 10/11 system. For example, passwords from browsers, installed programs and system saved passwords such as WiFi passwords. In addition, there is also an optional option to add scripts that retrieve system information, program information, network information, etc. It is also possible to add your own .bat scripts that are automatically executed next to the current scripts.

The above data is stored in text files on the SD card of the Rubber Ducky. This data is stored in a folder with the target's computer and username so that there are no complications when running on multiple computers or user accounts.

The Twin Duck firmware, custom payload, custom scripts and third party programs made it possible to achieve this. Thanks to the external parties mentioned on this GitHub page who are an important part of this software.

The purpose of this software is to recover forgotten passwords, improve your own digital security and gain knowledge about a Rubber Ducky, the Twin Duck firmware, writing scripts in combination with the use of external programs etc. It is not intended to be used for malicious purposes. 

## Requirements

- Rubber Ducky with the [Twin Duck firmware](https://raw.githubusercontent.com/hak5darren/USB-Rubber-Ducky/master/Firmware/Images/c_duck_v2.1.hex) installed (Open link, Ctrl+S to save file).
- Micro SD card (Default 128mb micro SD card didn't work in my case).

## Compatibility

- Windows 10/11 x32/x64 (Windows 8/8.1, not tested yet).
- Windows Security must be used as virus scanner for this software to work.
- Successful operation on the target system depending on the language support of the payload.

## Setup Rubber Ducky environment

1. Rename the label of the Rubber Ducky storage to: "RDPS".
2. Download the [latest release](https://github.com/Krouwndouwn/Rubber_Ducky_Password_Stealer/releases) (environment and scrips, payload with the right language (a payload equal to the target system) and extra scripts for getting system information (optional)) and extract the rar files to the root location of the Rubber Ducky storage.
3. Disable Windows Security otherwise the downloaded files will be removed from the system in the next step.
4. Download the [Windows Password Recovery Tools](https://www.nirsoft.net/password_recovery_tools.html) with command-line support from Nirsoft and extract them to: "(Rubber Ducky storage)\files\nirsoft\".
5. Manualy download the command-line tools: BulletsPassView ([x32](https://www.nirsoft.net/utils/bulletspassview.zip)/[x64](https://www.nirsoft.net/utils/bulletspassview-x64.zip)), OperaPassView ([x32](https://www.nirsoft.net/toolsdownload/operapassview.zip)), RouterPassView ([x32](https://www.nirsoft.net/toolsdownload/routerpassview.zip)) and WirelessKeyView ([x32](https://www.nirsoft.net/toolsdownload/wirelesskeyview.zip)/[x64](https://www.nirsoft.net/toolsdownload/wirelesskeyview-x64.zip), password: "WKey4567#"). Also extract the downloaded x32 files (only the .exe files) to: "(Rubber Ducky storage)\files\nirsoft\".
6. Rename the just downloaded x64 files to: "(filename)_x64.exe" and move them to: "(Rubber Ducky storage)\files\nirsoft\" Also do this for the x64 files located in: "(Rubber Ducky storage)\files\nirsoft\x64\" and remove the x64 folder afterwards. Feel free to delete Nirsoft files that are of no use to you. Learn more about what these files do on the [Nirsoft website](https://www.nirsoft.net/).
7. Rename all extrensions of the files located in: "(Rubber Ducky storage)\files\nirsoft\" from: ".exe" to: ".ps". The idea behind this is to reduce Windows Security's alertness to these files when the Rubber Ducky is just plugged into the target.
8. // Soon...
9. Safely remove the Rubber ducky storage.
10. Turn Windows Security back on.

Tip: Update external programs regularly for desired results.

## Usage

// Soon...

## Make your own changes

// Soon...

## Issues

Please feel free [submit an issue](https://github.com/Krouwndouwn/Rubber_Ducky_Password_Stealer/issues/new) for any of the following reasons:

- Reporting a bug.
- Reporting a grammatical error.
- Suggesting a feature.
- Suggesting a improvement.
- Any other issue with the payloads, scripts or GitHub page.

## Disclaimer

// Soon...
