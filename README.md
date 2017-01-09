<!---
  category: DevicesSensorsAndPower
  samplefwlink: http://go.microsoft.com/fwlink/p/?LinkId=820786
-->

# Bluetooth Low Energy client sample

Shows how to act as a client to communicate with a Bluetooth Low Energy (LE) device
using the Bluetooth GATT protocol. Acts as a GATT client to access nearby GATT servers like
heart rate sensors or temperature sensors.

> **Note:** This sample is part of a large collection of UWP feature samples. 
> If you are unfamiliar with Git and GitHub, you can download the entire collection as a 
> [ZIP file](https://github.com/Microsoft/Windows-universal-samples/archive/master.zip), but be 
> sure to unzip everything to access shared dependencies. For more info on working with the ZIP file, 
> the samples collection, and GitHub, see [Get the UWP samples from GitHub](https://aka.ms/ovu2uq). 
> For more samples, see the [Samples portal](https://aka.ms/winsamples) on the Windows Dev Center. 

Specifically, this sample shows how to:

- Enumerate nearby Bluetooth LE devices
- Query for supported services
- Query for supported characteristics
- Read and write data
- Subscribe to indicate and notify events

Search for "BT_Code" to find the portions of the sample that are particularly
relevant to Bluetooth.
Note in particular the "bluetooth" capability declaration in the manifest.

**Note** The Windows universal samples require Visual Studio 2015 to build and Windows 10 to execute.

To obtain information about Windows 10 development, go to the [Windows Dev Center](http://go.microsoft.com/fwlink/?LinkID=532421)

To obtain information about Microsoft Visual Studio 2015 and the tools for developing Windows apps, go to [Visual Studio 2015](http://go.microsoft.com/fwlink/?LinkID=532422)

## Related topics

### Samples

[Bluetooth Rfcomm](../BluetoothRfcommChat)

[Bluetooth Advertisement](../BluetoothAdvertisment)

[Device Enumeration and Pairing](../DeviceEnumerationAndPairing)

### Reference

[Windows.Devices.Bluetooth namespace](https://msdn.microsoft.com/library/windows/apps/windows.devices.bluetooth.aspx)

[Windows.Devices.Bluetooth.GenericAttributeProfile namespace](https://msdn.microsoft.com/library/windows/apps/windows.devices.bluetooth.genericattributeprofile.aspx)

[Windows.Devices.Enumeration namespace](https://msdn.microsoft.com/library/windows/apps/windows.devices.enumeration.aspx)

### Conceptual

[Bluetooth GATT Scenarios](https://msdn.microsoft.com/windows/uwp/devices-sensors/gatt-scenarios)

## System requirements

**Client:** Windows 10 Anniversary Edition

**Server:** Windows Server 2016 Technical Preview

**Phone:** Windows 10 Anniversary Edition

## Build the sample

1. If you download the samples ZIP, be sure to unzip the entire archive, not just the folder with the sample you want to build. 
2. Start Microsoft Visual Studio 2015 and select **File** \> **Open** \> **Project/Solution**.
3. Starting in the folder where you unzipped the samples, go to the Samples subfolder, then the subfolder for this specific sample, then the subfolder for your preferred language (C++, C#, or JavaScript). Double-click the Visual Studio?2015 Solution (.sln) file.
4. Press Ctrl+Shift+B, or select **Build** \> **Build Solution**.

## Run the sample

The next steps depend on whether you just want to deploy the sample or you want to both deploy and run it.

### Deploying the sample

- Select Build > Deploy Solution. 

### Deploying and running the sample

- To debug the sample and then run it, press F5 or select Debug >  Start Debugging. To run the sample without debugging, press Ctrl+F5 or selectDebug > Start Without Debugging. 
