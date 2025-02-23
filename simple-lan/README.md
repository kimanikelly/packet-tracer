# Simple-LAN

## Network Topology

[Network Topology](./docs/hardware-setup.png)

### PC-PT PC1

- Selected from End Devices/PC

### Switch 2960-24TT

- Selected from Network Devices/Switches

## Network Setup

### Assign the server an IP Address & Subnet Mask

1. Hover over the Server and click it once.
2. The Desktop page should populate. [Desktop page](./docs/desktop-page.png)
3. Once you've navigated to the Desktop page hover over the IP Configuration icon and click it once.
4. The IP Configuration page should populate. [IP Configuration page](./docs/ip-configuration-page.png)
5. Verify the Static radio button is selected.
6. Within the IPv4 Address input field enter an IP Address [Assigning IPv4 Address](./docs/ipv4.png)
7. Within the Subnet Mask input field enter a Subnet Mask [Assigning Subnet Mask](./docs/subnet-mask.png)
8. Exit out of the IP Configuration page, this should bring you back to the Desktop page.
9. Once you're back in the Desktop page hover over the Command Prompt icon and click it once.
   The Command Line should populate. [Command Line](./docs/command-line.png)
10. Within the Command Line type the command `ipconfig` to verify the IP Address & Subnet Mask of the Server. [Verifying the IP Address & Subnet Mask](./docs/ipconfig.png)
11. Within the Command Line type the command `ping` followed by the IP Address the server is assigned to verify that its online and reachable. [Verifying with ping](./docs/ping.png)
12. That completes assigning the Server an IP Address and Subnet Mask. Exit out of the Command Line and Desktop page.

### Assign the PC an IP Address & Subnet Mask

1. Hover over the PC and click it once.
2. The Desktop page should populate. [Desktop page](./docs/desktop-page.png)
3. Once you've navigated to the Desktop page hover over the IP Configuration icon and click it once.
4. The IP Configuration page should populate. [IP Configuration page](./docs/ip-configuration-page.png)
5. Verify the Static radio button is selected.
6. Within the IPv4 Address input field enter an IP Address different from the Server [Assigning IPv4 Address](./docs/ipv4.png)
7. Within the Subnet Mask input field enter the same Subnet as the Server [Assigning Subnet Mask](./docs/subnet-mask.png)
8. Exit out of the IP Configuration page, this should bring you back to the Desktop page.
9. Once you're back in the Desktop page hover over the Command Prompt icon and click it once.
   The Command Line should populate. [Command Line](./docs/command-line.png)
10. Within the Command Line type the command `ipconfig` to verify the IP Address & Subnet Mask of the PC. [Verifying the IP Address & Subnet Mask](./docs/pc-ipconfig.png)
11. Within the Command Line type the command `ping` followed by the IP Address the PC is assigned to verify that its online and reachable. [Verifying with ping](./docs/pc-ping.png)
12. That completes assigning the PC an IP Address and Subnet Mask. Exit out of the Command Line and Desktop page.
