# fruity-osx

This HowTo will guide you through the setup of the fruitymesh source code under Mac OSX.

If you don't know what Fruitymesh is and does follow this [link](https://github.com/mwaylabs/fruitymesh/wiki) to the FruityMesh Github page to learn about it.

## Installation
#### 1. First of all make sure that you have **git** installed. If not get it from [here](https://git-scm.com/download/mac).
 
#### 2. The following software is already in this repo included:
 +  GCC v4.9  [GNU Compiler Collection](https://launchpad.net/gcc-arm-embedded/4.9)
 +  Nordic SDK v14  [nRF5 SDK v14.x.x](https://developer.nordicsemi.com/nRF5_SDK/nRF5_SDK_v14.x.x/) 


#### 3. Go to your preferred download location, clone the project:

 + `git clone https://github.com/mirohero/fruity-osx.git`

#### 4. and install Eclipse from this source.
 +  Eclipse IDE for C/C++ Developers  [Eclipse Photon](https://www.eclipse.org/downloads/packages/release/photon/r/eclipse-ide-cc-developers)
   
#### 5. Then you need to install Segger from here:
 + Segger  [J-Link Software and Documentation pack for macOS](https://www.segger.com/downloads/jlink/#J-LinkSoftwareAndDocumentationPack)

#### 6. As a last step make the setup.sh in the repo root executable and start it:
 + `chmod +x setup.sh`
 + `./setup.sh`
