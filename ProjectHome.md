Nighthawk is an experimental implementation of ARP/ND spoofing, password sniffing and simple SSL stripping for Windows.

It requires [WinPcap](http://www.winpcap.org/) and [.NET Framework 4 (Client profile)](http://www.microsoft.com/downloads/en/details.aspx?FamilyID=9CFB2D51-5FF4-4491-B0E5-B386F32C0992) and works best on Vista & Windows 7.

**Features:**
  * ARP spoofing (IPv4) and RA spoofing (IPv6) over local network
  * Password sniffing for most common HTML form fields (name-based matching), HTTP basic authentication, FTP, POP3, SMTP, IMAP
  * Basic SSL stripping (doesn't work on HTTPS-only sites) and cookie stripping
  * Quick attack mode
  * _Windows Phone application for remote access to sniffer results (HawkWP)_

**Changelog:**
  * Nighthawk 0.9.4 (RC)
    * Windows 8 support
    * bug fixes
    * WCF service removed due to instability
  * Nighthawk 0.9.3 (RC)
    * fixed some WCF service related issues
    * updated HawkWP to 1.1
      * lots of bugs fixed, cleaner GUI
  * Nighthawk 0.9.2 (RC)
    * added a simple WCF service for remote access to sniffer results (see Downloads for a WP client)
  * Nighthawk 0.9.1 (RC)
    * updated SharpPcap to version 4.0.0
    * added NBug for better crash reporting
  * Nighthawk 0.9 (RC)
    * fixed scanning of large subnets
    * fixed a crash when WinPcap not installed
    * updated SharpPcap to version 3.7.0
    * added "Quick attack" mode

**Crash reporting:**

From version 0.9.1 onwards you'll now see a new exception window after Nighthawk crashes. If you click on "Send and quit" button, a .ZIP file containing some basic debug information will be created (nothing will actually get sent!) and you can attach it to a bug report to help me fix the problem.

**Disclaimer:**

This software may be used only for educational and security testing purposes with your network administrator's consent. The author takes no responsibility for improper (or even illegal) usage, data loss or other damage that might occur during its usage.