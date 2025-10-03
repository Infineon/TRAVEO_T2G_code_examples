# TRAVEO&#8482; T2G ModusToolbox&#8482;
TRAVEO&#8482; T2G is available with ModusToolbox&#8482;.
TRAVEO&#8482; T2G code example is made up of two parts: the default code examples and the additional code examples.
The additional code examples are available for TRAVEO&#8482; T2G devices in this repository.

Please refer the [ModusToolbox&#8482; software](https://github.com/Infineon/modustoolbox-software) for ModusToolbox&#8482;. It is recommended using latest ModusToolbox&#8482; software.

## Supported device
- [TRAVEO&#8482; T2G body high MCU](https://www.infineon.com/cms/en/product/microcontroller/32-bit-traveo-t2g-arm-cortex-microcontroller/32-bit-traveo-t2g-arm-cortex-for-body/traveo-t2g-cyt4bf-series/): CYT4BFBCHE, CYT4BF8CDS
- [TRAVEO&#8482; T2G Body Entry MCU](https://www.infineon.com/cms/en/product/microcontroller/32-bit-traveo-t2g-arm-cortex-microcontroller/32-bit-traveo-t2g-arm-cortex-for-body/traveo-t2g-cyt2bl-series/): CYT2BL5CAS
- [TRAVEO&#8482; T2G cluster 2D MCU](https://www.infineon.com/cms/en/product/microcontroller/32-bit-traveo-t2g-arm-cortex-microcontroller/32-bit-traveo-t2g-arm-cortex-for-cluster/traveo-t2g-cyt4dn/): CYT4DNJBZS

## Application note
[AN235305](https://www.infineon.com/assets/row/public/documents/10/42/infineon-an235305-getting-started-with-traveo-t2g-family-mcus-in-modustoolbox-applicationnotes-en.pdf?fileId=8ac78c8c8b6555fe018c1fddd8a72801) - GETTING STARTED WITH TRAVEO&#8482; T2G FAMILY MCUS IN MODUSTOOLBOX&#8482;

## Code Example
There is code example on Github. Each Code example provides a README.md file to learn more about that code example, as well as how to use it to create an application.

## How to apply ModusToolbox&#8482; to your own hardware
All ModusToolbox&#8482; applications require a target BSP. Infineon provides BSPs for all of our kits, as well as generic BSPs for each chip architecture, to use as a starting point. For example, you can see generic BSPs in supported device. When working with your own hardware, you can modify an Infineon BSP to match that hardware, or you can create a BSP by specifying the device(s) it contains. The BSP Assistant helps to simplify the process of creating or modifying a BSP to suit your needs. See the following document how to use BSP Assistant tool.<br>

- [ModusToolbox&#8482; BSP Assistant user guide](https://www.infineon.com/ModusToolboxBSPAssistant)
- [MODUSTOOLBOX&#8482; USAGE: How to create own BSP using BSP-assistant tool for TRAVEO T2G/PSOC 4 HV](https://www.infineon.com/assets/row/public/documents/10/56/infineon-infineon-002-36696-0a-v-how-to-create-own-bsp-using-bsp-assistant-tool-training-en-training-en.pdf)

## TRAVEO&#8482; T2G cluster 2D series graphics solutions
KIT_T2G_C-2D-6M_LITE has two types of graphics solutions. 
### Graphics demonstration with Qt Design Studio
KIT_T2G_C-2D-6M_LITE has demonstration code examples ModusToolbox&#8482; and Qt Design Studio working together to output image. It will enable users to quickly start with the evaluation process and contribute to solution development using Qt design studio. Please make sure to check out [here](https://github.com/orgs/Infineon/repositories?language=&q=topic%3Agraphics+demonstration&sort=&type=all).<br>
To use these graphics code examples, it is required some configuration in advance. See the [Steps to use the Qt Design Studio using the ModusToolbox&#8482;](https://www.infineon.com/assets/row/public/documents/10/56/infineon-steps-to-use-the-qt-design-studio-using-the-modustoolbox-training-en.pdf?fileId=8ac78c8c9715623e01973b3fe6e520a4) for more details.

### Graphics code example using Infineon GFX middleware
[GFX middleware](https://github.com/Infineon/tviic2d-gfx-mw) is standalone graphics driver software, it provides interface for graphics sub-system in T2G Cluster devices. KIT_T2G_C-2D-6M_LITE has code example using GFX middleware. It will allow users to develop using most of the functions of the graphics sub-system in T2G cluster devices. Please make sure to check out [here](https://github.com/orgs/Infineon/repositories?language=&q=topic%3Agraphics+gfx-middleware&sort=&type=all).

## Evaluation kit
The code examples support the following types of boards: <br>
*Figure 5. KIT_T2G-B-H_EVK*<BR><img src="./Images/KIT_T2G-B-H_EVK.png" width="600" /><br>
*Figure 6. KIT_T2G-B-H_LITE*<BR><img src="./Images/KIT_T2G-B-H_LITE.png" width="400" /><br>
*Figure 7. KIT_T2G-B-E_LITE*<BR><img src="./Images/KIT_T2G-B-E_LITE.png" width="400" /><br>
*Figure 8. KIT_T2G_C-2D-6M_LITE*<BR><img src="./Images/KIT_T2G_C-2D-6M_LITE.png" width="400" /><br><br>


|   Overview|[KIT_T2G-B-H_EVK](https://www.infineon.com/cms/en/product/evaluation-boards/kit_t2g-b-h_evk/)  |[KIT_T2G-B-H_LITE](https://www.infineon.com/cms/en/product/evaluation-boards/kit_t2g-b-h_lite/)  |[KIT_T2G-B-E_LITE](https://www.infineon.com/cms/en/product/evaluation-boards/kit_t2g-b-e_lite/)|[KIT_T2G_C-2D-6M_LITE](https://www.infineon.com/cms/en/product/evaluation-boards/kit_t2g_c-2d-6m_lite/)|
|-------------------------------|------------------------|--------------------------|-------------------------|-------------------------|
|MCU                            |CYT4BFBCHE (272pin-BGA) |CYT4BF8CDS (176pin-TEQFP) |CYT2BL5CAS (100pin-LQFP) |CYT4DNJBZS (327pin-BGA) |
|Kitprog3 programming/Debug     |✓ (USB Micro-B connector)|✓ (USB Micro-B connector)|✓ (USB Micro-B connector)|✓ (USB Type-C connector)|
|USER LEDs/Buttons/Potentiometer|✓                       |✓                        |✓                        |✓                        |
|CAN FD                         |✓                       |✓                        |✓                        |✓                        |
|Ethernet interface             |10MBPS/100MBPS/1GBPS    |10/100 Mbps               |Not Available            |10MBPS/100MBPS/1GBPS     |
|External memory                |512 MB serial NOR flash memory x1|512 MB Quad SPI NOR flash x2|Not Available|64 Mb HYPERRAM™ x1,<br> 512 Mb SEMPER™ flash x1|
|Z-USB™ FX3 interface           |Not Available           |Not Available             |Not Available            |✓ (USB Type-C connector)     |
|MIPI CSI-2 camera module interface|Not Available        |Not Available             |Not Available            |✓                        |
|Dual LVDS to HDMI interface    |Not Available           |Not Available             |Not Available            |✓                        |
|Arduino                        |✓                       |✓                        |✓                        |✓                        |
|Shield2go                      |Not Available           |✓                        |✓                        |✓                        |
|MikroBUS                       |Not Available           |✓                        |✓                        |✓                        |
|Raspberry Pi interface         |Not Available           |Not Available             |Not Available            |✓                        |

## Developer Community
For questions and support, use the TRAVEO™ T2G Forum:  
- <https://community.infineon.com/t5/TRAVEO-T2G/bd-p/TraveoII>

