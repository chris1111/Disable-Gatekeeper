# Disable-Gatekeeper in macOS Sequoia 15
View [Disable-Gatekeeper.mobileconfig](https://github.com/chris1111/Disable-Gatekeeper/blob/main/Disable-Gatekeeper.mobileconfig)

View [Install Disable-Gatekeeper Script](https://github.com/chris1111/Disable-Gatekeeper/blob/main/Install%20Disable-Gatekeeper.scptd/Contents/Resources/Scripts/main.scpt)

View [Building your own Notarize App](https://github.com/chris1111/Disable-Gatekeeper/blob/main/Create%20App.md)

### Starting from macOS 15, sudo spctl --master-disable is no longer supported to disable Gatekeeper.

- We need to disable it with Configuration Profiles.

Download ➤ [Disable-Gatekeeper](https://github.com/chris1111/Disable-Gatekeeper/raw/main/Install%20Disable-Gatekeeper.zip)

View Video Install Disable-Gatekeeper ⇩

[![Modular Image Creation](https://github.com/user-attachments/assets/68f65560-03ae-4dfe-908f-554e30e2906b)](https://youtu.be/Y-KID-_1YKA)

After runing the script; Double click to install Disable Gatekeeper

![Install](https://github.com/user-attachments/assets/097b7f35-0e24-4853-8273-435f0b0a01d4)


View Video Uninstall Disable-Gatekeeper ⇩

[![Modular Image Creation](https://github.com/user-attachments/assets/68f65560-03ae-4dfe-908f-554e30e2906b)](https://youtu.be/EJttKJnIlAQ)

After uninstalling the profiles, reset to `App Store & Known Developers` Then `Reboot macOS` 

![Screenshot Reset](https://github.com/user-attachments/assets/55f81b78-0377-47a1-b0c5-dcad31511e8c)

Thanks to [Apple](https://it-training.apple.com/tutorials/deployment/dm105/), [hoishing](https://gist.github.com/hoishing/cadd905b095e15531467255b537f6906) 
