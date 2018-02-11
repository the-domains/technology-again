---
publisher: {}
dateModified: '2018-02-11T04:42:23.468Z'
via: {}
description: Protect your Windows devices against Spectre and Meltdown
title: ''
inFeed: true
author: []
datePublished: '2018-02-11T04:42:25.262Z'
sourcePath: _posts/2018-01-23-protect-your-windows-devices-against-spectre-and-meltdown.md
datePublishedOriginal: '2018-02-11T04:42:25.262Z'
starred: true
_type: Blurb

---
Protect your Windows devices against Spectre and Meltdown

Applies to: Windows 10Windows 10 MobileWindows 8.1 More

This article discusses the impact of the recently disclosed processor vulnerabilities, named "Spectre" and "Meltdown," for Windows customers and provides resources to help keep your devices protected at home, at work, and across your enterprise.

Summary

Microsoft is aware of new vulnerabilities in hardware processors named "Spectre" and "Meltdown". These are a newly discovered class of vulnerabilities based on a common chip architecture that, when originally designed, was created to speed up computers. The technical name is "speculative execution side-channel vulnerabilities". You can learn more about these vulnerabilities at Google Project Zero.

Who is affected?

Affected chips include those manufactured by Intel, AMD, and ARM, which means all devices running Windows operating systems are potentially vulnerable (e.g., desktops, laptops, cloud servers, and smartphones). Devices running other operating systems such as Android, Chrome, iOS, and MacOS are also affected. We advise customers running these operating systems to seek guidance from those vendors.

At this time of publication, we have not received any information to indicate that these vulnerabilities have been used to attack customers.

Protections we've provided to date

As of January 3, 2018, Microsoft released several updates to help mitigate these vulnerabilities and help protect customers. We have also deployed updates to secure our cloud services and Internet Explorer and Microsoft Edge browsers. We are continuing to work closely with industry partners including chip makers, device manufacturers, and app vendors.

What steps should I take to protect my devices?

You will need to update both your hardware and your software to address this vulnerability. This includes firmware updates from device manufacturers and, in some cases, updates to your antivirus software as well.

To receive all available protections, follow these steps to get the latest updates for both software and hardware:

Note

Before your begin, make sure your antivirus (AV) software is up to date and compatible. Check your antivirus software manufacturer's website for their latest compatibility information.

Keep your Windows device up to date by turning on automatic updates.

Check that you've installed the January 2018 Windows operating system security update from Microsoft. If automatic updates are turned on, the updates should be automatically delivered to you, but you should still confirm that they're installed. For instructions, see Windows Update: FAQ

Install available hardware (firmware) updates from your device manufacturer. All customers will need to check with their device manufacturer to download and install their device specific hardware update. See below for a list of device manufacturer websites. 

Note

Customers who only install the January 2018 Windows operating system security updates from Microsoft will not be fully protected against the vulnerabilities. Antivirus software updates should be installed first. Operating system and firmware updates should follow.

Resources

Depending on your role, the following support articles will help you identify and mitigate client and server environments that are affected by the Spectre and Meltdown vulnerabilities.

Microsoft Security Advisory: MSRC ADV180002

Intel: Security Advisory

ARM: Security Advisory

AMD: Security Advisory

NVIDIA: Security Advisory

Microsoft Secure blog: Understanding the Performance Impact of Spectre and Meltdown Mitigations on Windows Systems

Consumer Guidance: Protecting your device against chip-related security vulnerabilities

Antivirus Guidance: Windows security updates released January 3, 2018, and antivirus software

Guidance for AMD Windows OS security update block: KB4073707: Windows operating system security update block for some AMD based devices

Surface Guidance: Surface Guidance to protect against speculative execution side-channel vulnerabilities

IT Pro Guidance: Windows Client Guidance for IT Pros to protect against speculative execution side-channel vulnerabilities

Edge Developer Blog: Mitigating speculative execution side-channel attacks in Microsoft Edge and Internet Explorer

Server Guidance: Windows Server guidance to protect against speculative execution side-channel vulnerabilities

Server Hyper-V Guidance

Virtual Machine Resource Controls

Hyper-V Host CPU Resource Management

Azure Blog: Securing Azure customers from CPU vulnerability

Azure KB: KB4073235: Microsoft Cloud Protections Against Speculative Execution Side-Channel Vulnerabilities

Azure Stack guidance: KB4073418: Azure stack guidance to protect against the speculative execution side-channel vulnerabilities

SQL Server guidance: KB4073225: SQL Server Guidance to protect against speculative execution side-channel vulnerabilities

SCCM guidance: Additional guidance to mitigate speculative execution side-channel vulnerabilities

Additional resources

List of OEM /Server device manufacturers

Use the links below to check with your device manufacturer for firmware updates. You will need to install both operating system and hardware/firmware updates for all available protections.

OEM Device Manufacturers

Link to microcode availability

Acer https://us.answers.acer.com/app/answers/detail/a\_id/53104

Asus https://www.asus.com/News/YQ3Cr4OYKdZTwnQK

Dell

https://www.dell.com/support/meltdown-spectre

Fujitsu 

https://www.fujitsu.com/global/support/products/software/security/products-f/jvn-93823979e.html

HP

https://support.hp.com/document/c05869091

Lenovo

https://support.lenovo.com/us/en/solutions/len-18282

LG

https://www.lg.com/us/support

Panasonic

https://pc-dl.panasonic.co.jp/itn/vuln/g18-001.html

Samsung

http://www.samsung.com/uk/support/intel\_update/

Surface

Surface Guidance to protect against speculative execution side-channel vulnerabilities

Toshiba

http://go.toshiba.com/intel-side-channel

Vaio

https://solutions.vaio.com/3316

Server OEM Manufacturers

Link to microcode availability 

Dell

https://www.dell.com/support/meltdown-spectre

Fujitsu http://www.fujitsu.com/global/support/products/software/security/products-f/jvn-93823979e.html

HPE

http://h22208.www2.hpe.com/eginfolib/securityalerts/SCAM/Side\_Channel\_Analysis\_Method.html

Huawei http://www.huawei.com/au/psirt/security-notices/huawei-sn-20180104-01-intel-en

Lenovo

https://support.lenovo.com/us/en/solutions/len-18282

Microsoft provides third-party contact information to help you find technical support. This contact information may change without notice. Microsoft does not guarantee the accuracy of this third-party contact information.

January 2018 Windows operating system update schedule

The security updates released in January 2018 provide mitigations for devices running the following x64-based Windows operating systems. See FAQ for further information.

Product Update Released

Released

Release Date

Release Channel

KB

Windows 10 - Version 1709 / Windows Server 2016 (1709) / IoT Core - Quality Update

Released

January 3

WU, WSUS, Catalog, Azure Image Gallery

KB4056892

Windows Server 2016 (1709) - Server container

Released

January 5

Docker Hub

KB4056892

Windows 10 - Version 1703 / IoT Core - Quality Update

Released

January 3

WU, WSUS, Catalog

KB4056891

Windows 10 - Version 1607 / Windows Server 2016 / IoT Core- Quality Update

Released

January 3

WU, WSUS, Catalog

KB4056890

Windows Server 2016 (1607) - Container Images

Released

January 4

Docker Hub

KB4056890

Windows 10 - Version 1511 / IoT Core - Quality Update

Released

January 3

WU, WSUS, Catalog

KB4056888

Windows 10 - Version RTM - Quality Update

Released

January 3

WU, WSUS, Catalog

KB4056893

Windows 10 Mobile (OS Build 15254.192) - ARM

Released

January 5

WU, Catalog

KB4073117

Windows 10 Mobile (OS Build 15063.850)

Released

January 5

WU, Catalog

KB4056891

Windows 10 Mobile (OS Build 14393.2007)

Released

January 5

WU, Catalog

KB4056890

Windows 10 HoloLens

Released

January 5

WU, Catalog

KB4056890

Windows 8.1 / Windows Server 2012 R2 - Security Only Update

Released

January 3

WSUS, Catalog

KB4056898

Windows Embedded 8.1 Industry Enterprise

Released

January 3

WSUS, Catalog

KB4056898

Windows Embedded 8.1 Industry Pro

Released

January 3

WSUS, Catalog

KB4056898

Windows Embedded 8.1 Pro

Released

January 3

WSUS, Catalog

KB4056898

Windows 8.1 / Windows Server 2012 R2 Monthly Rollup

Released

January 8

WU, WSUS, Catalog

KB4056895

Windows Embedded 8.1 Industry Enterprise

Released

January 8

WU, WSUS, Catalog

KB4056895

Windows Embedded 8.1 Industry Pro

Released

January 8

WU, WSUS, Catalog

KB4056895

Windows Embedded 8.1 Pro

Released

January 8

WU, WSUS, Catalog

KB4056895

Windows Server 2012 Security Only

Coming

WSUS, Catalog

Windows Server 2008 SP2

Coming

WU, WSUS, Catalog

Windows Server 2012 Monthly Rollup

Coming

WU, WSUS, Catalog

Windows Embedded 8 Standard

Coming

Windows 7 SP1 / Windows Server 2008 R2 SP1 - Security Only Update

Released

January 3

WSUS, Catalog

KB4056897

Windows Embedded Standard 7

Released

January 3

WSUS, Catalog

KB4056897

Windows Embedded POSReady 7

Released

January 3

WSUS, Catalog

KB4056897

Windows Thin PC

Released

January 3

WSUS, Catalog

KB4056897

Windows 7 SP1 / Windows Server 2008 R2 SP1 Monthly Rollup

Released

January 4

WU, WSUS, Catalog

KB4056894

Windows Embedded Standard 7

Released

January 4

WU, WSUS, Catalog

KB4056894

Windows Embedded POSReady 7

Released

January 4

WU, WSUS, Catalog

KB4056894

Windows Thin PC

Released

January 4

WU, WSUS, Catalog

KB4056894

Internet Explorer 11-Cumulative Update for Windows 7 SP1 and Windows 8.1

Released

January 3

WU, WSUS, Catalog

KB4056568

Frequently asked questions

Show all