<properties 
   pageTitle="Install your StorSimple 8600 device"
   description="Describes how to unpack, rack mount, and cable your StorSimple 8600 device."
   services="storsimple"
   documentationCenter="NA"
   authors="SharS"
   manager="adinah"
   editor="tysonn" />
<tags 
   ms.service="storsimple"
   ms.devlang="NA"
   ms.topic="article"
   ms.tgt_pltfrm="NA"
   ms.workload="TBD"
   ms.date="06/09/2015"
   ms.author="v-sharos" />

# Install your StorSimple 8600 device

## Overview
Your Microsoft Azure StorSimple 8600 is a dual enclosure device and consists of a primary and an EBOD enclosure. This tutorial explains how to unpack, rack-mount, and cable the StorSimple 8600 device hardware before you configure the StorSimple software.

## Unpack your StorSimple 8600 device

The following steps provide clear, detailed instructions on how to unpack your StorSimple 8600 storage device. This device is shipped in two separate boxes, one for the primary enclosure and another for the EBOD enclosure.

### Prepare to unpack your device

Before you unpack your device, review the following information.

>[AZURE.WARNING]
> ![heavy weight icon](./media/storsimple-8600-hardware-installation/HCS_HeavyWeight_Icon.png)
>
> 1. Make sure that you have two people available to manage the weight of the device if you are handling it manually. A fully configured device can weigh up to 32 kg (70 lbs.).
>
> 2. Place the box on a flat, level surface.

Next, complete the following steps to unpack your device.

#### To unpack your device

1. Inspect the boxes and the packaging foam for crushes, cuts, water damage, or any other obvious damage. If the box or packaging is severely damaged, do not open the box. Please contact Microsoft Support to help you assess whether the device is in good working order.

2. Open the two boxes and unpack the primary and EBOD enclosures. The following figure shows the unpacked view of your storage device.
 
    **Figure 1 Unpacked view of your storage device**

    ![Unpack your storage device](./media/storsimple-8600-hardware-installation/HCSUnpackyour4Udevice.png) 

     Label | Description 
     ----- | -------------
     1     | Packing box
     2     | SAS cables (in accessories and cables tray)
     3     | Bottom foam
     4     | Device
     5     | Top foam
     6     | Accessory box

3. After unpacking the two boxes, make sure that you have:

  - 1 primary enclosure (the primary enclosure and EBOD enclosure are in two separate boxes) 
  - 1 EBOD enclosure
  - 4 power cords, 2 in each box
  - 2 SAS cables (to connect the primary enclosure to EBOD enclosure)
  - 1 crossover Ethernet cable
  - 2 serial console cables
  - 1 serial-USB converter for serial access
  - 4 single QSFP-to-SFP+ adapters for use with 10 GbE network interfaces
  - 2 rack mount kits (4 side rails with mounting hardware, 2 each for the primary enclosure and EBOD enclosure), 1 in each box
  - Getting started documentation

    If you did not receive any of the items listed above, contact Microsoft Support. 

The next step is to rack-mount your device. 

## Rack-mount your StorSimple 8600 device

Follow the next steps to install your StorSimple 8600 storage device in a standard 19-inch rack with front and rear posts. This device comes with two enclosures: a primary enclosure and an EBOD enclosure. Both of these need to be rack-mounted. 

The installation consists of multiple steps, each of which is discussed in the following procedures.

### Site preparation

The enclosures must be installed in a standard 19-inch rack that has both front and rear posts. Use the following procedure to prepare for rack installation. 

#### To prepare the site for rack installation

1. Make sure that the primary and EBOD enclosures are resting safely on a flat, stable, and level work surface (or similar).

2. Verify that the site where you intend to set up has standard AC power from an independent source or a rack Power Distribution Unit (PDU) with an uninterruptible power supply (UPS).

3. Make sure that one 4U (2 X 2U) slot is available on the rack in which you intend to mount the enclosures. 

>[AZURE.WARNING]
> ![heavy weight icon](./media/storsimple-8600-hardware-installation/HCS_HeavyWeight_Icon.png)
> 
> Make sure that you have two people available to manage the weight if you are handling the device setup manually. A fully configured enclosure can weigh up to 32 kg (70 lbs.).

### Rack prerequisites

The enclosures are designed for installation in a standard 19-inch rack cabinet with:

- Minimum depth of 27.84 inches from rack post to post
- Maximum weight of 32 kg for the device
- Maximum back pressure of 5 Pascal (0.5 mm water gauge)

### Rack-mounting rail kit

A set of mounting rails will be provided for use with the 19-inch rack cabinet. The rails have been tested to handle the maximum enclosure weight. These rails will also allow installation of multiple enclosures without loss of space within the rack. Install the EBOD enclosure first.

#### To install the EBOD enclosure on the rails

1. With the enclosure on the work surface, remove the left and right front flange caps by pulling the caps free. The flange caps simply snap onto the flanges.

2. Typically, these rails are installed at the factory. If they are not, then install the left-rail and right-rail slides to the sides of the enclosure chassis. They attach using six metric screws on each side. To help with orientation, the rail slides are marked **LH – Front** and **RH – Front**, and the end that is affixed towards the rear of the enclosure has a tapered end.

    **Figure 2 Attaching rail slides to the sides of the enclosure**

    ![Attaching rail slides to enclosure chassis](./media/storsimple-8600-hardware-installation/HCSAttachingRailSlidestoEnclosureChassis.png) 

    Label | Description
    ----- | -----------
    1     | M 3x4 button-head screws
    2     | Chassis slides
 
3. Attach the left rail and right rail assemblies to the rack cabinet vertical members. The brackets are marked **LH**, **RH**, and **This side up** to guide you through correct orientation.

4. Locate the rail pins at the front and rear of the rail assembly. Extend the rail to fit between the rack posts and insert the pins into the front and rear-rack post vertical member holes. Be sure that the rail assembly is level.

5. Secure the rail assembly to the rack vertical members by using two of the metric screws provided. Use one screw on the front and one on the rear.

6. Repeat these steps for the other rail assembly.

    **Figure 3 Attaching rail assemblies to the rack**

     ![Attaching rail slides to rack cabinet](./media/storsimple-8600-hardware-installation/HCSAttachingRailSlidestoRackCabinet.png) 

     Label | Description
     ----- | -----------
     1     | Clamping screw
     2     | Square-hole front rack post screw
     3     | Left front-rail location pins
     4     | Clamping screw
     5     | Right front-rail location pins

### Mounting the EBOD enclosure in the rack 

Using the rack rails that were just installed, perform the following steps to mount the EBOD enclosure in the rack. 

#### To mount the EBOD enclosure

1. With an assistant, lift the enclosure and align it with the rack rails. 

2. Carefully insert the enclosure into the rails, and then push it completely into the rack cabinet.

    **Figure 4 Mounting the enclosure in the rack**

    ![Inserting device in the rack](./media/storsimple-8600-hardware-installation/HCSInsertingDeviceintheRack.png)

3. Secure the enclosure into the rack by installing one provided Phillips-head screw through each flange, left and right.

4. Install the flange caps by pressing them into position and snapping them into place.

    **Figure 5 Installing the flange caps**

     ![Installing flange caps](./media/storsimple-8600-hardware-installation/HCSInstallingFlangeCaps.png)
 
     Label | Description
     ----- | -----------
     1     | Enclosure fastening screw


### Mounting the primary enclosure in the rack

After you have finished mounting the EBOD enclosure, you will need to mount the primary enclosure following the same steps.

> [AZURE.NOTE]
> 
> - It is possible to have a few empty slots in the rack between the primary enclosure and the EBOD enclosure. 
> - Use the provided 2m SAS cable to connect the primary enclosure to the EBOD enclosure.
> - There are no constraints on the relative placement of the head unit to the EBOD unit. Therefore, the primary enclosure can be placed in the top slot and the EBOD enclosure below — or vice versa.

The next step is to cable your device for power, network, and serial access.

## Cable your StorSimple 8600 device

The following procedures explain how to cable your StorSimple 8600 device for power, network, and serial connections.

### Prerequisites

Before you begin to cable your device, you will need:

- Your primary enclosure and the EBOD enclosure, completely unpacked
- 4 power cables (2 each for the primary and the EBOD enclosure) that came with your device
- 2 SAS cables supplied with the device to connect the EBOD enclosure to the primary enclosure
- Access to 2 Power Distribution Units (PDUs) (recommended)
- Network cables
- Provided serial cables
- Serial-USB converter with the appropriate driver installed on your PC (if needed)
- Provided single QSFP-to-SFP+ adapters for use with 10 GbE network interfaces
- [Supported transceivers, cables, and switches for 10 GbE network interfaces](https://msdn.microsoft.com/library/azure/dn891474.aspx) 

### SAS cabling

Your device has a primary and an EBOD enclosure. These enclosures need to be connected together using the SAS cables.

Next, identify the primary enclosure and the EBOD enclosure.

#### To identify primary and EBOD enclosures

1. Identify the primary and the EBOD enclosures. The two enclosures can be identified by looking at the respective backplanes. See the following figure for guidance.

    **Figure 6 Back of the primary and EBOD enclosures**

    ![Primary and EBOD enclosure](./media/storsimple-8600-hardware-installation/HCSBackplaneofprimaryandEBODenclosure.png)

     Label | Description
     ----- | -----------
     1     | Primary enclosure
     2     | EBOD enclosure


2. Locate the serial numbers on both the primary enclosure and the EBOD enclosure. The serial number sticker is affixed on the back ear of each enclosure. The serial numbers must be identical on both enclosures. Contact Microsoft Support immediately if the serial numbers do not match. See the following figure to help you locate the serial numbers.

    **Figure 7 Rear view of enclosure showing location of serial number**

    ![Location of serial number](./media/storsimple-8600-hardware-installation/HCSRearviewofenclosureindicatinglocationofserialnumbersticker.png)

     Label | Description
     ----- | -----------
     1     | Ear of the enclosure


Next, use the provided SAS cables to connect the EBOD enclosure to the primary enclosure.

#### To connect the primary and EBOD enclosures

1. Identify the four Serial Attached SCSI (SAS) ports on the primary enclosure and EBOD enclosure. The SAS ports are labeled as EBOD on the primary enclosure and CTRL on the EBOD enclosure, as shown in Figure 8.

    **Figure 8 Location of SAS ports on primary and EBOD enclosures**

    ![Location of SAS ports](./media/storsimple-8600-hardware-installation/HCSSAScablingforyourdevice.png)

     Label | Description
     ----- | -----------
     A     | Primary enclosure
     B     | EBOD enclosure
     1     | Controller 0
     2     | Controller 1
     3     | EBOD controller 0
     4     | EBOD controller 1
     5,6   | SAS ports on primary enclosure (labeled EBOD)
     7,8   | SAS ports on EBOD enclosure (labeled CTRL)

2. Use the provided SAS cables to connect the EBOD ports to the CTRL ports. 

    The EBOD port on controller 0 should be connected to the CTRL port on EBOD controller 0. The EBOD port on controller 1 should be connected to the CTRL port on EBOD controller 1. See Figure 8 for guidance.

### Power cabling

Both the primary and the EBOD enclosures include redundant Power and Cooling Modules (PCMs). In each enclosure, each PCM must be installed and connected to a different power source to ensure high availability. 

Perform the following steps to cable your device for power.

#### To cable for power

1. Make sure that the power switches on all the PCMs are in the OFF position.

2. For the primary enclosure, connect the power cords to both PCMs. The power cords are identified in red in the following diagram.

3. Ensure that the two PCMs of the primary enclosure use separate power sources.

4. Attach the power cords to the rack power distribution units as shown in the following figure. 

5. Repeat steps 2 through 4 for the EBOD enclosure.

6. Turn on the EBOD enclosure by flipping each PCM power switch to the ON position.

7. Verify that the EBOD enclosure is turned on by checking that the EBOD controller LEDs (green LEDs on the back of the chassis) have turned ON.

8. Now, turn on the primary enclosure by flipping each PCM switch to the ON position.

9. Verify that the system is up by ensuring the device controller LEDs have turned ON.

10. Verify that the connection between the EBOD controller and the device controller is active by checking the SAS LEDs (4 LEDs next to the SAS port) on the EBOD controller. The SAS LEDs should be green.

> [AZURE.IMPORTANT] To ensure high availability of your system, you are advised to strictly adhere to the power cabling scheme shown in the following diagram.

   **Figure 9 Power cabling for your device**

   ![Power cabling diagram](./media/storsimple-8600-hardware-installation/HCSCableYour4UDeviceforPower.png)

     Label | Description
     ----- | -----------
     1     | Primary enclosure
     2     | PCM 0
     3     | PCM 1
     4     | Controller 0
     5     | Controller 1
     6     | EBOD controller 0
     7     | EBOD controller 1
     8     | EBOD enclosure
     9     | PDUs
 

### Network cabling

Your device is in an active-standby configuration: at any given time, one controller module is active and processing all disk and network operations while the other controller module is on standby. If a controller failure occurs, the standby controller immediately activates and continues all the disk and networking operations. 

To support this redundant controller failover, you need to cable your device network as shown in the following steps.

#### To cable for network connection

1. Your device has six network interfaces on each controller: four 1 Gbps and two 10 Gbps Ethernet ports. Refer to the following illustration to identify the data ports on the backplane of your device.

    **Figure 10 Back of your device showing the data ports**

     ![Backplane of 8600 device](./media/storsimple-8600-hardware-installation/HCSBackplaneof2UDevicewithPortsLabeled.jpg)
 
     Label   | Description
     ------- | -----------
     0,1,4,5 |  1 GbE network interfaces
     2,3     | 10 GbE network interfaces
     6       | Serial ports

2. For high availability, the device requires a minimum of two connections for each controller.
    1. The DATA 0 port is automatically enabled and configured via the serial console of the device. Apart from DATA 0, another data port also needs to be configured through the Management Portal.
    2. Identify identical network interfaces on each controller. For instance, if you choose to connect DATA 0 and DATA 3 for one of the controllers, you need to connect the corresponding DATA 0 and DATA 3 on the other controller. 

3. For high availability, ensure that you connect:
   1. Identical interfaces on each controller to the relevant network to ensure availability through a controller failure.
   2. Interfaces from each controller to at least two different switches to ensure availability through a switch failure.
   3. DATA 0 port to the primary LAN (network with Internet access). The other data ports can be connected to SAN/iSCSI LAN (VLAN) segment of the network, depending on the intended role.

At a minimum, configure one network interface for cloud access and one for iSCSI. For high availability and performance, configure two pairs of network interfaces on each controller. See the following diagram for network cabling. (The minimum network configuration is shown by solid blue lines. For high availability and performance, additional configuration required is shown by dotted lines.)

**Figure 11 Network cabling for your device**

![Cable your 4U device for network](./media/storsimple-8600-hardware-installation/HCSCableYour4UDeviceforNetwork.png)

Label | Description
----- | -----------
A    | LAN with Internet access
B    | Controller 0
C    | PCM 0
D    | Controller 1
E    | PCM 1
F    | EBOD controller 0
G    | EBOD controller 1
H,I  | Hosts (for example, file servers)
0-5  | Network interfaces
6    | Primary enclosure
7    | EBOD enclosure

### Serial port cabling

Perform the following steps to cable your serial port.

#### To cable for serial connection

1. Your device has a serial port on each controller that is identified by a wrench icon. Refer to Figure 10 to locate the serial ports on the backplane of your device.

2. Identify the active controller on your device backplane. A blinking blue LED indicates that the controller is active. 

3. Use the provided serial cable (if needed, the USB-serial converter for your laptop), and connect your console or computer (with terminal emulation to the device) to the serial port of the active controller.

4. Install the serial-USB drivers (shipped with the device) on your computer.

5. Set up the serial connection as follows: 
   - 115,200 baud
   - 8 data bits
   - 1 stop bit
   - No parity
   - Flow control set to **None**

6. Verify that the connection is working by pressing Enter on the console. A serial console menu should appear.

> [AZURE.NOTE] **Lights-Out Management:** When the device is installed in a remote datacenter or in a computer room with limited access, ensure that the serial connections to both controllers are always connected to a serial console switch or similar equipment. This allows out-of-band remote control and support operations in case of network disruption or unexpected failures.

You have completed cabling your device for power, network access, and serial connection.The next step is to configure the software on your device.

## Next steps

You are now ready to [deploy and configure your on-premises StorSimple device](storsimple-deployment-walkthrough.md) 