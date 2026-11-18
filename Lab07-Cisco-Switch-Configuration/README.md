## 🔹 Lab 07 - Cisco Switch Configuration

This lab demonstrates how to configure switch interfaces, set interface speed and duplex, assign interface descriptions, disable unused ports, and configure host IP addresses to provide end-to-end communication across the network.

### ⚙️ Step-by-Step Configuration

#### Step 1 – Review the Network Topology

- The lab uses the following network topology to provide end-to-end connectivity across two switches, four hosts, and a router.
- [View Topology](images/topology.png)

#### Step 2 – Configure Host IP Addresses

- Assign static IPv4 addresses and subnet masks to the hosts within the 172.16.0.0/16 network.
- [View IP Configuration](images/configure-pc1-ip-address.png)

#### Step 3 – Configure Switch Hostname

- Change the switch hostname to SW1 for easier identification and management.
- [View Hostname Configuration](images/changeHostName.png)

#### Step 4 – Check Initial Interface Status

- Use the `show interface status` command to check the initial status of switch interfaces, including connectivity, speed, and duplex settings.
- [View Interface Status](images/interfaceStatus.png)

#### Step 5 – Configure Switch Uplink Interfaces (Speed/Duplex)

- Configure the SW1 GigabitEthernet0/2 uplink interface with a speed of 1000 Mbps, full-duplex mode, and a description identifying its connection to SW2.
- [View Uplink Configuration](images/configure-g0-2.png)

#### Step 6 – Configure FastEthernet Ports for End Hosts

- Configure FastEthernet0/1–2 interfaces and add a description to identify them as host-facing ports.
- [View Port Configuration](images/configure-f0-2.png)

#### Step 7 – Disable Unused FastEthernet Interfaces

- Add a **not in use** description to FastEthernet0/3–24 interfaces and use the `shutdown` command to disable unused ports.
- [View Port Configuration](images/addShutdown.png)

#### Step 8 – Save and Verify Configuration

- Save the switch configuration and verify the final interface status, including configured and disabled ports.
- [View Save Configuration](images/save.png)
- [View Final Interface Status](images/showConfig.png)
