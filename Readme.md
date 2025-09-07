### FortiOS 7.4.x – SSL VPN Enabled via CLI
By default, SSL VPN web mode settings are disabled and hidden from the GUI and the CLI. See the link below to enable
https://docs.fortinet.com/document/fortigate/7.4.0/new-features/233856/update-ssl-vpn-default-behavior-and-visibility-in-the-gui-7-4-1

### FortiOS 7.6.x - Agentless VPN
The agentless VPN (formerly SSL VPN web mode) feature is no longer available from the GUI or CLI  FortiGate 40F, 60F, and 90G series models.
However, SSL VPN tunnel mode is no longer supported on any models.
https://docs.fortinet.com/document/fortigate/7.6.3/fortios-release-notes/877104/agentless-vpn-formerly-ssl-vpn-web-mode-not-supported-on-fortigate-40f-60f-and-90g-series-models


### FortiOS 7.4.X+ – SSL VPN Enabled via CLI
To enable SSL VPN web mode:
config system global
    set sslvpn-web-mode enable
end Copy
To enable the VPN > SSL-VPN GUI menus:
config system settings
    set gui-sslvpn enable
end

If SSL VPN web mode and tunnel mode were configured in a FortiOS firmware version before upgrading to FortiOS 7.4.1 and above, then the VPN > SSL-VPN menus and SSL VPN web mode settings remain visible in the GUI.


Great Fortinet Automation Stitches
https://yurisk.info/2023/11/27/fortigate-automation-stitches-collection/
https://github.com/yuriskinfo/Fortinet-tools
https://bluecatnetworks.com/how-tos-2/fortinet-fortigate-automation/


FortiGate VPN SSL Hardening Guide
Harden VPN, this has seen the best Guide By Far, and the same concept can be used for folks with a WAN Interface open to WAN. “PLEASE AVOID”
 
https://yurisk.info/2023/03/21/fortigate-vpn-ssl-hardening-guide/ 
https://www.linkedin.com/pulse/harden-your-fortigate-management-access-interface-get-adonis-sardi%C3%B1as-zdooe/

FortiGate and UniFi: Making DHCP Options Work Together
https://www.linkedin.com/pulse/fortigate-unifi-making-dhcp-options-work-together-adonis-sardi%C3%B1as-8d3be/ 

🔐 Harden Your FortiGate Management Access Interface + Get Real-Time Alerts for New Admin Accounts
https://www.linkedin.com/pulse/harden-your-fortigate-management-access-interface-get-adonis-sardi%C3%B1as-zdooe/ 

CISSP Guide using local resources.
https://www.linkedin.com/pulse/cissp-guide-using-local-resources-adonis-sardi%C3%B1as-x0l4f/ 
