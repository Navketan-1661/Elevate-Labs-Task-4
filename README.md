Open Firewall Configuration Tool
List Current Firewall Rules  -  netsh advfirewall firewall show rule name=all
Add Rule to Block Inbound Traffic on Port 23 Telnet
Test the Rule  - telnet ip-address 23
Remove the Test Block Rule to Restore Original State  -netsh advfirewall firewall delete rule name="Block Telnet Port 23"
