# ESP32ArduinoEclipseInstaller
an installer generator for installing the ESP32 Eclipse/Arduino toolchains


[![Github All Releases](https://img.shields.io/github/downloads/WPIRoboticsEngineering/ESP32ArduinoEclipseInstaller/total.svg)](https://github.com/WPIRoboticsEngineering/ESP32ArduinoEclipseInstaller/releases)

# Easy Mode
Download and install these, do not change any default values

## [ Supported ] 
### Windows 10 Stand Alone install

Requirements: Windows 10 on x86_64 with 16gb Ram

Development Environment: [Sloeber Windows Installer 0.3.2](https://github.com/WPIRoboticsEngineering/ESP32ArduinoEclipseInstaller/releases/download/0.3.2/WPI-RBE-esp32-0.3.2.exe)

Driver: [Esp32 Driver Windows](https://github.com/WPIRoboticsEngineering/ESP32ArduinoEclipseInstaller/releases/download/0.0.0/CP210x_Universal_Windows_Driver.zip)

Unzip the contents.

Open the folder on your disk and run

```
CP210xVCPInstaller_x64.exe
```

## [ Supported ] 
### Linux Bundled Sloeber

Development Environment: [Sloeber Linux Stand Alone](https://github.com/CommonWealthRobotics/ESP32ArduinoEclipseInstaller/releases/latest/download/eclipse)

```
							
mkdir -p $HOME/bin/
wget https://github.com/CommonWealthRobotics/ESP32ArduinoEclipseInstaller/releases/latest/download/eclipse -O $HOME/bin/eclipse
chmod +x $HOME/bin/eclipse
bash $HOME/bin/eclipse
				

```

## [ Supported ] 
### Macos Bundled Sloeber

Development Environment: [Sloeber MacOS Stand Alone](https://github.com/CommonWealthRobotics/ESP32ArduinoEclipseInstaller/releases/latest/download/eclipse-mac)

```
							
mkdir -p $HOME/bin/
curl -L https://github.com/CommonWealthRobotics/ESP32ArduinoEclipseInstaller/releases/latest/download/eclipse-mac -o $HOME/bin/eclipse-mac
chmod +x $HOME/bin/eclipse-mac
bash $HOME/bin/eclipse-mac
				

```

## [Unofficially supported] 
### MacOS 10.14 or earlier Bundled Sloeber

We reccomend you install Windows 10 with boot camp. If you want to try the native MacOS version, here be dragons.

Development Environment: [Sloeber MacOS Stand Alone](https://github.com/WPIRoboticsEngineering/ESP32ArduinoEclipseInstaller/releases/download/0.1.9/sloeber-MacOS-Esp32.zip)

Driver: [Esp32 Driver MacOS](https://github.com/WPIRoboticsEngineering/ESP32ArduinoEclipseInstaller/releases/download/0.0.0/SiLabsUSBDriverDisk.dmg)


## Thats it, its all installed and configured

You are done, do not continue, go here:

 
## Start a Fresh Arduino Sketch
[Create a Sketch with Git ](StartFreshSketch.md)

[Create a Sketch no version control](StartFreshSketchNOGIT.md)
 
 Or just open Arduino RBE config on your desktop and use as normal. 


# HARD MODE

## [Unsupported, not reccomended] 
### MacOS 10.15+ Bundled Sloeber

We reccomend you install Windows 10 with boot camp. If you want to try the native MacOS version, here be dragons.


#### 1) Install Standard Java 8

First install Java: https://www.java.com/en/download/manual.jsp

#### 2) Install the OpenJDK Framework

https://github.com/AdoptOpenJDK/openjdk8-binaries/releases/download/jdk8u262-b10/OpenJDK8U-jdk_x64_mac_hotspot_8u262b10.pkg

GUI installation

Instructions for running an interactive installation using the macOS PKG installer.

1. Download the .pkg file.

2. Navigate to the folder that contains the file and open it to launch the installation program or drag the icon to your Application folder.

3. The Introduction screen indicates the target location for the installation, which you can change later in the install process. Click Continue.

4. Read the license, click Continue and accept the license if you are happy with the terms.

5. Change the target location for the installation. Click Install to complete the installation.

#### 3) Install Sloeber and the Driver

Development Environment: [Sloeber MacOS Stand Alone](https://github.com/WPIRoboticsEngineering/ESP32ArduinoEclipseInstaller/releases/download/0.1.9/sloeber-MacOS-Esp32.zip)

Driver: [Esp32 Driver MacOS](https://github.com/WPIRoboticsEngineering/ESP32ArduinoEclipseInstaller/releases/download/0.0.0/SiLabsUSBDriverDisk.dmg)

## From scratch setup

I am almost sure you do not want this, but in case you are curious how those bundles are created in the first place you can look at [hardMode.md](hardMode.md)
