# LubuMaster DOWNLOAD: [OVA](https://github.com/Virtual-Machines/LubuMaster/releases/download/latest/LubuMaster.ova) - [ISO](https://github.com/Virtual-Machines/LubuMaster/releases/download/latest/LubuMaster.iso)
[**Your OPINION is important**](https://github.com/Virtual-Machines/LubuMaster/issues/1) - Last update: 2020-01-04

LubuMaster is a distribution that builds a custom Lubuntu 18.04.3 Minimal

Generating live environment on virtual machine (using the OVA):

![LubuMasterBuild](https://raw.githubusercontent.com/Virtual-Machines/LubuMaster/master/LubuMasterBuild.png)


Test the liveCD (included as ISO):

![LubuMasterLive](https://raw.githubusercontent.com/Virtual-Machines/LubuMaster/master/LubuMasterLive.png)

- Minimal Lubuntu Bionic 18.04.3 (lubuntu-core package)
- Linux Kernel 5 HWE (Hardware Enablement)
- VirtualBox Guest Additions (bidirectional clipboard between host and guest, shared folders capable, Seamless Mode...)
- [Pinguy Builder](https://pinguyos.com/2015/09/pinguy-builder-an-app-to-backupremix-buntu/)
- Synaptic package manager
- Basic python http server included. Example: python3 -m http.server 8080
- Command-line download manager: wget
- NAT port forwarding configured on 8080 that allows web browser testing outside virtual machine
- It can be used as a base of development environments, to test software...
- OVA and ISO files less than 500 MB
- User and pass of system is the same: lubuntu
- Import OVA on VirtualBox using "File -> Import Appliance (or Control + I)"
