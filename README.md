# Test-H743ZI2-lwip

Simple CubeMX project for Nucleo H743ZI2 with lwip, without OS
Added modifications as suggested in
https://community.st.com/s/article/How-to-create-project-for-STM32H7-with-Ethernet-and-LwIP-stack-working
to get a working base.
Including a _write implementation for debug messages on USB serial. DHCP, NETIF and ICMP messages are enabled.
IP address is obtained via DHCP, can be changed in CubeMX for static address.
