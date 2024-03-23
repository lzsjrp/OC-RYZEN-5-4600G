### OpenCore 0.9.4 for Ryzen 5 4600g
#### macOS 14 Sonoma

[Download Here](https://github.com/lhseeli/OC-RYZEN-5-4600G/releases/download/250224/EFI.zip)

___
#### Hardware
 - AMD Ryzen 5 4600g [**with Radeon Graphics**](https://chefkissinc.github.io/nred)
   - Cores: 6 (12 Threads)
   - Clock: 3.7GHz
 - 2x 8 GB 3200 MHz DDR4
 - A320MH 2.0
___
#### Before Installing
  - BIOS
      - Secure Boot (Off) 
      - CSM (Off)
      - VRAM (1GB+)
  - OC
      - Generate your serial number using this [script](https://github.com/corpnewt/GenSMBIOS)
   
> [!NOTE]  
> You can enable Secure Boot if you enroll this [PK, DB, and KEK](https://github.com/lhseeli/OC-RYZEN-5-4600G/releases/download/250224/KEYS.zip) keys in your BIOS or in [KeyTool.efi](https://github.com/lhseeli/OC-RYZEN-5-4600G/releases/download/250224/KeyTool.efi)  
> Or make your own keys by following this [guide](https://github.com/perez987/OpenCore-and-UEFI-Secure-Boot)
___
#### Kexts

| Name       | Version       | Source       |
| -------------|:-------------:| -----:|
| AMDRyzenCPUPowerManagement | 0.7.1 | https://github.com/trulyspinach/SMCAMDProcessor |
| AppleALC | 1.8.3 | https://github.com/acidanthera/AppleALC |
| AppleMCEReporterDisabler | 1.2 | https://dortania.github.io/OpenCore-Install-Guide/ktext.html#extras |
| Lilu | 1.6.6 | https://github.com/acidanthera/Lilu |
| NootedRed | 1.0.0 * | https://github.com/ChefKissInc/NootedRed |
| RealtekRTL8111 | 2.1.0 | https://github.com/Mieze/RTL8111_driver_for_OS_X |
| RestrictEvents | 1.1.2 | https://github.com/acidanthera/RestrictEvents |
| SMCAMDProcessor | 0.7.1 | https://github.com/trulyspinach/SMCAMDProcessor |
| VirtualSMC | 1.3.2 | https://github.com/acidanthera/VirtualSMC |

* Kext has no version, project under development, to download the latest version go to [Actions](https://github.com/ChefKissInc/NootedRed/actions) and download the latest Artifacts.zip
