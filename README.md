# TRAVEO™ T2G ModusToolbox™
TRAVEO™ T2G is available with ModusToolbox™.
TRAVEO™ T2G code example is made up of two parts: the default code examples and the additional code examples.
The additional code examples are available for TRAVEO™ T2G devices in this repository.

To use a code example into ModusToolbox™, follow the guide at **[How to setup](#How-to-setup)**.

Please refer the [ModusToolbox™ software](https://github.com/Infineon/modustoolbox-software) for ModusToolbox™. It is recommended using latest ModusToolbox™ software.

## Supported device
- [TRAVEO™ T2G body high MCU](https://www.infineon.com/cms/en/product/microcontroller/32-bit-traveo-t2g-arm-cortex-microcontroller/32-bit-traveo-t2g-arm-cortex-for-body/traveo-t2g-cyt4bf-series/): CYT4BFBCHE, CYT4BF8CDS
- [TRAVEO™ T2G Body Entry MCU](https://www.infineon.com/cms/en/product/microcontroller/32-bit-traveo-t2g-arm-cortex-microcontroller/32-bit-traveo-t2g-arm-cortex-for-body/traveo-t2g-cyt2bl-series/): CYT2BL5CAS
- [TRAVEO™ T2G cluster 2D MCU](https://www.infineon.com/cms/en/product/microcontroller/32-bit-traveo-t2g-arm-cortex-microcontroller/32-bit-traveo-t2g-arm-cortex-for-cluster/traveo-t2g-cyt4dn/): CYT4DNJBZS

## Application note
[AN235305](https://www.infineon.com/dgdl/?fileId=8ac78c8c8b6555fe018c1fddd8a72801) - GETTING STARTED WITH TRAVEO™ T2G FAMILY MCUS IN MODUSTOOLBOX™

## Code Example
Each Code example provides a README.md file to learn more about that code example, as well as how to use it to create an application. Each README.md contains the following information:

- **Device**: The devices used by code example
- **Board**: The evaluation kit used by code example
- **Scope of work**: An abstract of code example
- **Introduction**: A generic introduction on the used module and it main features
- **Hardware setup**: The used hardware and how to configure it
- **Implementation**: A detailed explanation of how to implement the module's configuration using HAL and/or PDL and exploits their features
- **Run and Test**: The steps to follow to make sure the code is working properly and interact with it
- **References**: Related documents and web pages

[TRAVEO™ T2G MCU Code examples](https://github.com/orgs/Infineon/repositories?q=mtb-t2g-&type=all&language=&sort=) on GitHub

## How to setup
To use the additional code examples, set the following environment variable on your PC. <br>
**Before perform this process, Modus toolbox should be closed if you run Modus toolbox.**


- Variable name = CyRemoteManifestOverride
- Variable value = https://github.com/Infineon/mtb-t2g-super-manifest/raw/main/mtb-super-manifest-fv2.xml

*Figure 1. System variable setting*<BR><img src="./Images/SystemVariable.png" width="1000" />

From the menu, run the Eclipse IDE of ModusToolbox™ application. Then, open the Eclipse IDE window after workspace location setting.
- Click the **New Application** of Start in the Quick Panel, after that, open the Project creator.

*Figure 2. ModusToolbox™ Eclipse IDE*<BR><img src="./Images/Modustoolbox.png" width="1000" />

- Select the Board support package (BSP) what want to use, and click the **Next>** button.

*Figure 3. Project Creator*<BR><img src="./Images/ProjectCreator.png" width="1000" />

- Open the Select application window. You can choose and use **Additional Code Examples** and **Advanced Solutions** for TRAVEO™ T2G.

*Figure 4. Select application*<BR><img src="./Images/AdditionalCE.png" width="1000" />

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
