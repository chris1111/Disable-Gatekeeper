# Disable-Gatekeeper in macOS Sequoia 15
View [Disable-Gatekeeper.mobileconfig](https://github.com/chris1111/Disable-Gatekeeper/blob/main/Disable-Gatekeeper.mobileconfig)

View [Install Disable-Gatekeeper Script](https://github.com/chris1111/Disable-Gatekeeper/blob/main/Install%20Disable-Gatekeeper.scptd/Contents/Resources/Scripts/main.scpt)

### Starting from macOS 15, sudo spctl --master-disable is no longer supported to disable Gatekeeper.

- We need to disable it with Configuration Profiles.

Download ➤ [Disable-Gatekeeper](https://github.com/chris1111/Disable-Gatekeeper/raw/main/Install%20Disable-Gatekeeper.zip)

View Video Install Disable-Gatekeeper ⇩

[![Modular Image Creation](https://github.com/user-attachments/assets/68f65560-03ae-4dfe-908f-554e30e2906b)](https://youtu.be/Y-KID-_1YKA)

After runing the script; Double click to install Disable Gatekeeper

![Install](https://github.com/user-attachments/assets/d09dae59-b109-4737-ab6c-101f461a547d)


View Video Uninstall Disable-Gatekeeper ⇩

[![Modular Image Creation](https://github.com/user-attachments/assets/68f65560-03ae-4dfe-908f-554e30e2906b)](https://youtu.be/EJttKJnIlAQ)

After uninstalling the profiles, reset to `App Store & Known Developers` Then `Reboot macOS` 

![Screenshot Reset](https://github.com/user-attachments/assets/55f81b78-0377-47a1-b0c5-dcad31511e8c)

Thanks to [Apple](https://it-training.apple.com/tutorials/deployment/dm105/), [hoishing](https://gist.github.com/hoishing/cadd905b095e15531467255b537f6906) 
