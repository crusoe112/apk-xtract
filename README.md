# APK-Xtract
```
    _    ____  _  __   __  ___                  _   
   / \  |  _ \| |/ /   \ \/ / |_ _ __ __ _  ___| |_ 
  / _ \ | |_) | ' /_____\  /| __| '__/ _` |/ __| __|
 / ___ \|  __/| . \_____/  \| |_| | | (_| | (__| |_ 
/_/   \_\_|   |_|\_\   /_/\_\\__|_|  \__,_|\___|\__|
                              Created by Marc Bohler
```

## Summary
Automates the process of downloading and extracting APK's for static analysis of decompiled Android apps

## Installation
Run the following commands to install (requires sudo privileges):
```bash
chmod +x setup.sh
./setup.sh
```
## Usage
Execute the tool with the Google play URL or app ID of the desired Android app or the APK filename.
```
./apk-xtract [-a ANALYZER] -s APK_SOURCE
-a ANALYZER             jd-gui|jadx
-s APK_SOURCE           GOOGLE_PLAY_URL|APP_ID|APK_FILE
```
## Example
```bash
./apk-xtract -a jadx -s "https://play.google.com/store/apps/details?id=<<APP_ID>>&hl=en&gl=US"
```

