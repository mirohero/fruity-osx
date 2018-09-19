# fruity-osx

This HowTo will guide you through the setup of the fruitymesh source code under Mac OSX.

If you don't know what Fruitymesh is follow this [link](https://github.com/mwaylabs/fruitymesh/wiki) to the FruityMesh Github page to learn about it.

## Installation
#### 1. First of all make sure that you have **git** installed. If not get it from [here](https://git-scm.com/download/mac).
 
#### 2. The following software is already in this repo included:
 +  GCC v4.9  [GNU Compiler Collection](https://launchpad.net/gcc-arm-embedded/4.9)
 +  Nordic SDK v14  [nRF5 SDK v14.x.x](https://developer.nordicsemi.com/nRF5_SDK/nRF5_SDK_v14.x.x/) (Patched version, see license.txt in files/sdk5_14)


#### 3. Go to your preferred download location, clone the project:

 + `git clone https://github.com/mirohero/fruity-osx.git`

#### 4. and install Eclipse from this source.
 +  Eclipse IDE for C/C++ Developers  [Eclipse Photon](https://www.eclipse.org/downloads/packages/release/photon/r/eclipse-ide-cc-developers)
   
#### 5. Then you need to install Segger from here:
 + Segger  [J-Link Software and Documentation pack for macOS](https://www.segger.com/downloads/jlink/#J-LinkSoftwareAndDocumentationPack)

#### 6. As a last step make the setup.sh in the repo root executable and start it:
 + `chmod +x setup.sh`
 + `./setup.sh`

## Eclipse Setup
#### 1. Open your newly installed Eclipse IDE and click on `File -> Open Projects from File System` an choose the fruitymesh-directory in the repository root:
![alt text](https://github.com/mirohero/fruity-osx/blob/master/images/eclipse_1.png)

#### 2. Open the debug configuration, double click GDB Segger to create a new configuration and add the path to the firmware on the first page and your device name on the second page:
![alt text](https://github.com/mirohero/fruity-osx/blob/master/images/eclipse_2.png)
![alt text](https://github.com/mirohero/fruity-osx/blob/master/images/eclipse_3.png)



#### Now you are ready to write or change the source code and compile it. For flashing instructions head over to the [FruityMesh GitHub Page](https://github.com/mwaylabs/fruitymesh/wiki/Quick-Start#flashing-the-precompiled-firmware)
