## 🔹 Lab 06 - Cisco Router IP Configuration

This lab demonstrates how to configure and verify router interfaces and host IP addresses to establish end-to-end connectivity across multiple networks.

### ⚙️ Step-by-Step Configuration

#### Step 1 – Check the Current Interface Status

- Use the `show ip interface brief` command to check the IP addresses and status of router interfaces.
- [View Interface Status](images/display-interface-status.png)

#### Step 2 – Configure the G0/0 Interface IP Address

- Enter interface configuration mode using `interface gigabitEthernet 0/0` and assign an IP address with a subnet mask using the `ip address` command.
- [View G0/0 IP Configuration](images/g0-0-ip-configuration.png)

#### Step 3 – Add an Interface Description

- Use the `description` command to document the interface connection.
- [View Interface Description Configuration](images/g0-0-description-configuration.png)

#### Step 4 – Activate the Interface

- By default, Cisco router interfaces are administratively shut down (disabled).
- Use the `no shutdown` command in interface configuration mode to activate the interface.  
- [View Interface Activation](images/g0-0-interface-activation.png)

#### Step 5 – Configure the G0/1 Interface

- Assign an IP address and subnet mask, add an interface description, and enable the G0/1 interface.
- [View G0/1 Interface Configuration](images/g0-1-all-ip-configuration.png)

#### Step 6 – Configure the G0/2 Interface

- Assign an IP address and subnet mask, add an interface description, and enable the G0/2 interface.
- [View G0/2 Interface Configuration](images/g0-2-all-ip-configuration.png)

#### Step 7 – Verify the Interface Configuration

- Use the `show ip interface brief` command to verify the configured interfaces.
- Check the assigned IP addresses and confirm that both `Status` and `Protocol` are **up**.
- [View Interface Status Verification](images/check-interface-status.png)
