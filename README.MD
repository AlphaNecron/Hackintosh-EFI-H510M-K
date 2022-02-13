## EFI for MacOS Big Sur on H510M-K

OpenCore version: v0.7.8  
MacOS version: 11.6.3

![img](https://user-images.githubusercontent.com/57827456/153759331-3ef98eb4-fb6b-479c-a2dc-ed2b5e833201.png)

### Specifications
| Component | Model |
| --- | --- |
| Motherboard | ASUS PRIME H510M-K |
| CPU | Intel Core i3 10100F 4C/8T |
| GPU | ASUS NVIDIA GT 730 2G DDR5 (GK208 variant) |
| Audio Codec | Realtek ALC897 |
| SSD | Lexar 480GB SSD |
| Ethernet | Intel I-219V (Onboard) |

#### Working
- App Store and other apps
- Sleep
- Ethernet
- USB ports
- USB tethering

#### Not working
- AirDrop - Requires compatible WLAN/Bluetooth card


### Notes
- Remember to use GenSMBIOS and change MASKED properties in `config.plist`.
- Only Big Sur and lower is supported.