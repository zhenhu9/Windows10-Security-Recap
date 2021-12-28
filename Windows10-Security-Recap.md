Windows10 Security Recap

Windows Security features in setting should all be enabled:

- Virus & threat protection
- Account protection
- Firewall & network proction
- App & brower control
- Device security
- Device performance & health
- Family options

All those features should be enabled, such as blocking all of three type of networks' incoming connections, etc. Secure boot should enabled in your BIOS or UEFI. If your computer has a tpm, no matter 1.2 or 2.0 version, this should be enabled. When you reinstall Windows 10, you should do a "clear tpm" in `Device security/Security processor details`, if the system display that information.

**Notes**: There is also a "clear tpm" option in `Security processor troubleshooting`. Don't touch it, if you don't understand how tpm works and there are more information about tpm the links it gives.

Control Panel

`Control Panel/System and Security/Allow remote access/Remote Assistance/Allow Remote Assistant connections to this computer` don't enable this, if you don't need it. Turn on System Protection and create a restore point.

DNS settings

- Google: 8.8.8.8, 8.8.4.4; 2001:4860:4860::8888, 2001:4860:4860::8844
- Cloudflare: 1.1.1.1, 1.0.0.1; 2606:4700:4700::1111, 2606:4700:4700::1001
- OpenDNS: 208.67.222.222, 208.67.220.220; 2620:0:ccc::2, 2620:0:ccd::2; 2620:119:35::35, 2620:119:53::53
- Quad 9: 9.9.9.9, 149.112.112.112; 2620:fe::fe, 2620:fe::fe:9
- Microsoft: 4.4.4.4

**Note**: Ipv4 DNS support more features. There are some advises [here](https://support.opendns.com/hc/en-us/community/posts/245247727-What-are-the-IPv6-addresses-for-OpenDNS-).

## References

- [Firewall & network protetion in Windows Security](https://support.microsoft.com/en-us/windows/firewall-network-protection-in-windows-security-aef9838b-d081-fd75-3b1b-e5fa794c003b)

## Documentations

- [Windows security](https://docs.microsoft.com/en-us/windows/security/)
