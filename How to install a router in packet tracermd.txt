Here's a detailed guide on how to install and configure a router in Cisco Packet Tracer:

Step 1: Launch Cisco Packet Tracer
Open the Cisco Packet Tracer application on your computer. If you don't have it installed, you can download it from the Cisco Networking Academy website.

Step 2: Create a Network Topology
Click on the "New" button or go to the "File" menu and select "New." This will create a new network topology for you to work with.

Step 3: Add Devices
Drag and drop a router from the "Routers" section of the devices panel onto the workspace area.

Step 4: Connect Devices
Drag and drop PCs or other devices onto the workspace and connect them to the router. To connect devices, select a cable type from the "Connections" panel and click on one device, then click on the other device to establish a connection.

Step 5: Configure Router Interfaces
Double-click on the router to open the configuration window. In the router configuration window, click on the "CLI" tab to access the Command Line Interface.

Step 6: Configure Interfaces
To configure an interface, type the following command:
```
interface interface_name
```
Replace `interface_name` with the actual interface name (e.g., `GigabitEthernet0/0`).

Step 7: Assign an IP Address
To assign an IP address to the interface, use the following command:
```
ip address ip_address subnet_mask
```
Replace `ip_address` with the desired IP address and `subnet_mask` with the subnet mask you want to use.

Step 8: Enable the Interface
To enable the interface, use the following command:
```
no shutdown
```
This will activate the interface.

Step 9: Repeat for Other Interfaces
Repeat Steps 6-8 for all the interfaces you want to configure on the router.

Step 10: Configure Routing
To configure routing on the router, use the following command:
```
router routing_protocol
```
Replace `routing_protocol` with the desired routing protocol (e.g., `rip`, `ospf`, `eigrp`).

Step 11: Save the Configuration
To save the configuration, type the following command:
```
write
```
This will save the configuration to the router's memory.

Step 12: Test the Configuration
Once you have completed the configuration, you can test the connectivity between the devices in your network topology. You can use the "Desktop" tab of the PCs to open a command prompt and ping other devices.

That's it! You have now installed and configured a router in Cisco Packet Tracer. Remember to save your project so you can come back to it later if needed.
