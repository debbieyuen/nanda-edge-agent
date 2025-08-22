# NANDA for EDGE AI 

## Requirements
* Personal Computer:
  * JetPack SDK 6.2.1
  * Jetson Orin Nano Developer Kit - JetPack 5.1.3 image
  * Balena Etcher
* Hardware Materials:
  * NVIDIA Jetson Orin Nano 8GB Module
  * USB Type-C Power Adapter
  * USB Type-C to Type-A Cable
  * microSD Card (64 GB or higher)
  * NVME SSD 1TB
* Jetson Orin Nano
* 



## Set Up
### Step 1
Install [NVIDIA JetPack SDK](https://developer.nvidia.com/embedded/jetpack). We are currently working with JetPack 6.2.1 and a microSD Card of 128 GB. In order to download, you will need to sign into your [NVIDIA account](https://developer.nvidia.com/account). The SDK Manager needs to meet the minimum requirements of screen resolution equal or larger than 1440x900. Once you have the SDK Manager, log in to your NVIDIA Developer account. After signing in, you will see a screen displaying informatioin about your system configuration including your **host machine** and your **target hardware** in our case we will be working with the Jetson AGX Orin modules.

### Step 2
Next, we can get started with setting up our hardware! If you have the Jetson Orin Nano from the Developer Kit, you will need to upgrade to the latest firmware. This is because the Jetson Orin Nano Developer Kit comes with an old firmware flashed at the factory, which is NOT compatible with JetPack 6.x.
Therefore, you must upgrade to the latest firmware, before inserting SD card flashed with JetPack 6.x image (unless the firmware previuosly updated). Additional instructions are listed [here](https://developer.nvidia.com/embedded/learn/get-started-jetson-orin-nano-devkit#prepare).

### Step 3
Download the SD card image onto your PC. Here, we will be using JetPack 5.1.3 Image. Use [Balena Etcher](https://etcher.balena.io) to flash image to SD card.


## Contribution 
