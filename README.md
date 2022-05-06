# Opencore-EFI-LG-Gram-13ZD940-GX70K-OC-0.7.9

<img src = "https://user-images.githubusercontent.com/101755125/167093601-fa42a564-bccd-415f-937b-0e566762e02f.png" width="60%"></img>
<img src = "https://user-images.githubusercontent.com/101755125/167093414-bd0f0819-46cc-4267-be1b-547acd665b58.png" width="60%"></img>

I wrote down the detailed description of this EFI in the notion
https://alive-bayberry-ea1.notion.site/LG-Gram-13ZD940-GX70K-Hackintosh-OC-0-7-9-Complete-433fdf384e0c4d22963df2c247d13fce

# Working Features
![Screen Shot 2022-05-05 at 3 14 04 PM](https://user-images.githubusercontent.com/101755125/167093625-3c706a0a-d311-4ead-a6e6-03725fba7623.png)
CPU : Intel(R) i7-4500U Dual-Core @ 1.80 GHz
Memory : DDR3L 8GB 1600MHz
SSD : HFS256G36MNB-2300A 256GB
Graphics : Intel HD Graphics 4400 1536MB ( Laptop ) - HDMI 1.4
SMBIOS : MacbookPro 11,1 (2013)

![Screen Shot 2022-05-05 at 3 16 51 PM](https://user-images.githubusercontent.com/101755125/167093994-9dc6e584-5aaa-4851-ae56-933e8262d9e0.png)

- itlwm/OpenintelWireless.kext Working { Intel(R) Dual Band Wireless AC 7265 ( Gen 1 IWM )}

       Apple Communites Servies + BT Dongle ( Handoff, icloud, instant hospot ) , But Airdrop doesn’t receive files and don’t search nearby airdrop devices + Doesn’t Support Sidecar,Universal Control ( cuz SMBIOS is 2011” )

![Screen Shot 2022-05-05 at 3 16 40 PM](https://user-images.githubusercontent.com/101755125/167093772-f9edbc95-b6fd-4532-89a7-40eec229a019.png)

- Webcam Working

- ![Screen Shot 2022-05-05 at 3 18 24 PM](https://user-images.githubusercontent.com/101755125/167093844-dab7bb67-ccf2-4ec7-94c1-7858e9a8041c.png)

- AppleALC Working

      Bulit-in Speaker,Headphones,Microphone

- Bulit-in Trackpad,Keyboard Working

      ( Trackpad only click right button)
          
- USBInjectAll.kext ( Do not need USBMapping if you use USB 2.0 devices )

      > bulit-in USB 2.0 Micro Type B Port working well

## Not Working yet  
VGA ( Real Macs don't have VGA output, so doesn't have support normally )

Micor SD Card Reader ( Note Tested )

Intel Speed Step

Battery Percentage DDST/SSDT Hot Patch
