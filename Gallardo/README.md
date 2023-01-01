# Gallardo RainMeter skin
This is a RainMeter skin mainly based in the [Modena](https://www.deviantart.com/apexxx-sensei/art/Modena-770512921) merged with [CPU/GPU Temperature and Usage Monitor](https://www.deviantart.com/classic2203/art/Rainmeter-CPU-GPU-Temperature-and-Usage-Monitor-889867033) skins, but broadly modified by me, so that components are  positioned on the left, right and bottom edges of the desktop workspace area automatically, irrespective of the screen resolution being used.

# Pre-requisites
Although must components work out-of-the-box, you will face errors when at first trying to load the components named "CPU Temperature and Usage Monitor" and "GPU Temperature and Usage Monitor". This is due to the fact that it has external dependency on the installation of [Open Hardware Monitor](https://openhardwaremonitor.org/) to access CPU and GPU temperatures, as RainMeter doesn't provide means to retrieve that information. 
 Also, for the network compononents to show acurate bar readings for Upload and Download percentage, you need to modify the maximum upload and download bandwidth as according to your network connection as specified below.  


# Setup Instructions
These are the changes that you need to do to make everything work with your own hardware:

1. Download and install [Open Hardware Monitor](https://openhardwaremonitor.org/downloads/) before loading this skin
2. In Open Hardware Monitor "Options" menu, enable "Run on Windows Startup", turn on "Start Minimized", "Start to Tray" and "Minimize on Close" options
3. Copy the exact names for your CPU and GPU as shown in Open Hardware Monitor _(ex: Intel Core i7-4710HQ) (ex: NVIDIA NVIDIA GeForce GTX 850M)_
4. Open RainMeter manage window
5. Select the "CPU Temperature and Usage.ini" in the folder "CPU Temperature and Usage" and click the "Edit" button 
6. Replace the value of "CpuName" variable with your own hardware name, under the VARIABLES section _(ex: CpuName=Intel Core i7-4710H)_
7. Select the "GPU Temperature and Usage.ini" in the folder "GPU Temperature and Usage" and click the "Edit" button 
8. Replace the value of "GpuName" variable with your own hardware name, under the VARIABLES section _(ex: GpuName=NVIDIA NVIDIA GeForce GTX 850M)_
9. Select the "Download.ini" in the folder "Download" and click the "Edit" button 
8. Replace the value of "MaxDownloadMbits" variable with your own bandwith download value _(ex: MaxDownloadMbits=120)_
9. Select the "Download.ini" in the folder "Upload" and click the "Edit" button 
10. Replace the value of "MaxUploadMbits" variable with your own bandwith upload value _(ex: MaxUploadMbits=6)_
11. Now you can load all component from the skin and everything should be working

# Screenshots

## CPU and Disks
![Gallardo Skin - CPU + Disks.png](https://github.com/hvmonteiro/rainmeter-skins/blob/ea5c7ae46a6b07c0add7844072473bc2376ae099/Gallardo/@Resources/Gallardo%20Skin%20-%20CPU%20+%20Disks.png)

## CPU and GPU
![Gallardo Skin - CPU + GPU.png](https://github.com/hvmonteiro/rainmeter-skins/blob/ea5c7ae46a6b07c0add7844072473bc2376ae099/Gallardo/@Resources/Gallardo%20Skin%20-%20CPU%20+%20GPU.png)

## Clock
![Gallardo Skin - Clock.png](https://github.com/hvmonteiro/rainmeter-skins/blob/ea5c7ae46a6b07c0add7844072473bc2376ae099/Gallardo/@Resources/Gallardo%20Skin%20-%20Clock.png)

## Links
![Gallardo Skin - Links.png](https://github.com/hvmonteiro/rainmeter-skins/blob/ea5c7ae46a6b07c0add7844072473bc2376ae099/Gallardo/@Resources/Gallardo%20Skin%20-%20Links.png)

## Network 
![Gallardo Skin - Network.png](https://github.com/hvmonteiro/rainmeter-skins/blob/ea5c7ae46a6b07c0add7844072473bc2376ae099/Gallardo/@Resources/Gallardo%20Skin%20-%20Network.png)

## Running on a 5K Super UltraWide QHD (5120x1440) desktop
![Gallardo Skin - Desktop (5K - SUWQHD).png](https://github.com/hvmonteiro/rainmeter-skins/blob/ea5c7ae46a6b07c0add7844072473bc2376ae099/Gallardo/@Resources/Gallardo%20Skin%20-%20Desktop%20(5K%20-%20SUWQHD).png)


