## Patches and Updates

### Firmware

Intel has [confirmed a higher amounts of reboots affecting Broadwell and Haswell processors](https://newsroom.intel.com/news/intel-security-issue-update-addressing-reboot-issues/) after applying firmware updates. As of January 22, Intel has [identified](https://security-center.intel.com/advisory.aspx?intelid=INTEL-SA-00088&languageid=en-fr) the root cause of the reboot issue impacting [Broadwell and Haswell platforms](https://newsroom.intel.com/wp-content/uploads/sites/11/2018/01/microcode-update-guidance.pdf) and is working with OEMs on testing a new update. Only apply firmware updates on production systems after new firmware updates have been published by the affected vendors and the updates have been tested on non-production systems.

Dell and HPi have updated their advisories and recommend that customers do not install firmware updates until after new updates have been issued.

[HPi statemment](https://support.hp.com/us-en/document/c05869091):
*In response to Intel's recommendation, HP is taking the following actions:*
* *HP is removing HP BIOS softpaqs with Intel microcode patches from hp.com.*
* *HP will be reissuing HP BIOS softpaqs with previous Intel microcode starting January 25, 2018.*
* *Once Intel reissues microcode updates, HP will issue revised Softpaqs.*
*HP is working closely with our partners, and updates will be made as soon as possible. Check this Security Bulletin frequently for updates.*

[Dell EMC statement](https://www.dell.com/support/article/us/en/19/sln308588):
*Intel has communicated new guidance regarding "reboot issues and unpredictable system behavior" with the microcode included in the BIOS updates released to address Spectre (Variant 2), CVE-2017-5715. Dell is advising that all customers should not deploy the BIOS update for the Spectre (Variant 2) vulnerability at this time. We have removed the impacted BIOS updates from our support pages and are working with Intel on a new BIOS update that will include new microcode from Intel.*

*If you have already deployed the BIOS update, in order to avoid unpredictable system behavior, you can revert back to a previous BIOS version.*

[Dell statement](http://www.dell.com/support/article/us/en/19/sln308587):
*Intel has communicated new guidance regarding the "reboot issues" with the microcode included in the BIOS updates released to address Spectre (Variant 2), CVE-2017-5715. Dell is advising that all customers should not deploy the BIOS update for the Spectre (Variant 2) vulnerability at this time. We are removing the impacted BIOS updates from the web and suspending further BIOS updates for affected platforms.*

*If you have already applied the BIOS update, please wait for further information and an updated BIOS release, no other action is recommended at this point. Please continue to check back for updates.*

| OEM | Type | Link |
| --- | ---- | ---- |
| Acer | Client | [1](https://us.answers.acer.com/app/answers/detail/a_id/53104) |
| Asus| Client | [1](https://www.asus.com/News/YQ3Cr4OYKdZTwnQK) |
| Dell | Client | [1](http://www.dell.com/support/article/sln308587/),[2](https://www.dell.com/support/meltdown-spectre) |
| Dell EMC | Server | [1](http://www.dell.com/support/article/sln308588/),[2](https://www.dell.com/support/meltdown-spectre) |
| Fujitsu | Client / Server | [1](https://www.fujitsu.com/global/support/products/software/security/products-f/jvn-93823979e.html) | 
| HPi | Client | [1](https://support.hp.com/document/c05869091) |
| HPe | Server | [1](http://h22208.www2.hpe.com/eginfolib/securityalerts/SCAM/Side_Channel_Analysis_Method.html),[2](https://support.hpe.com/hpsc/doc/public/display?sp4ts.oid=null&docLocale=en_US&docId=emr_na-a00039267en_us),[3](https://support.hpe.com/hpsc/doc/public/display?docId=emr_na-hpesbhf03805en_us) | 
| Huawei | Server | [1](http://www.huawei.com/au/psirt/security-notices/huawei-sn-20180104-01-intel-en) |
| Lenovo | Client / Server | [1](https://support.lenovo.com/us/en/solutions/len-18282) |
| IBM | Server | [1](https://www.ibm.com/blogs/psirt/ibm-security-bulletin-power-firmware-update-released-address-common-vulnerabilities-exposures-issue-numbers-cve-2017-5715-cve-2017-5753-cve-2017-5754-known-spectre-m/),[2](http://www-01.ibm.com/support/docview.wss?uid=isg3T1026811),[3](https://www.ibm.com/blogs/psirt/potential-impact-processors-power-family/) |
| LG | Client | [1](https://www.lg.com/us/support) |
| Panasonic | Client | [1](https://pc-dl.panasonic.co.jp/itn/vuln/g18-001.html) |
| Samsung | Client | [1](http://www.samsung.com/uk/support/intel_update/) |
| Microsoft | Client | [1](https://support.microsoft.com/en-us/help/4073065) |
| Toshiba | Client | [1](http://go.toshiba.com/intel-side-channel) |
| Vaio | Client | [1](https://solutions.vaio.com/3316) |

### Operating Systems



| Product | Patch / Version | Release Date | Links |
| --- | --- | --- | --- |
| Aix | | ~01/26/2018 | [1](https://www.ibm.com/blogs/psirt/potential-impact-processors-power-family/) |
| Android | 2018-01-05 | 01/02/2018 | [1](https://support.google.com/faqs/answer/7622138#android),[2](https://source.android.com/security/bulletin/2018-01-01) |
| Chrome OS | 63 | 12/25/2017 | [1](https://support.google.com/faqs/answer/7622138#chromeos),[2](https://www.chromium.org/a/chromium.org/dev/chrome-os-devices-and-kernel-versions) |
| IBM i 7.1 | MF64553 | 01/13/2018 | [1](http://www-01.ibm.com/support/docview.wss?uid=nas3MF64553),[2](http://www-01.ibm.com/support/docview.wss?uid=nas8N1022433),[3](https://www.ibm.com/blogs/psirt/ibm-security-bulletin-ibm-released-ptfs-response-vulnerabilities-known-spectre-meltdown/),[4](https://www.ibm.com/blogs/psirt/potential-impact-processors-power-family/) |
| IBM i 7.2 | MF64552 | 01/13/2018 | [1](http://www-01.ibm.com/support/docview.wss?uid=nas3MF64552),[2](http://www-01.ibm.com/support/docview.wss?uid=nas8N1022433),[3](https://www.ibm.com/blogs/psirt/ibm-security-bulletin-ibm-released-ptfs-response-vulnerabilities-known-spectre-meltdown/),[4](https://www.ibm.com/blogs/psirt/potential-impact-processors-power-family/) |
| IBM i 7.3 | MF64551 | 01/13/2018 | [1](http://www-01.ibm.com/support/docview.wss?uid=nas3MF64551),[2](http://www-01.ibm.com/support/docview.wss?uid=nas8N1022433),[3](https://www.ibm.com/blogs/psirt/ibm-security-bulletin-ibm-released-ptfs-response-vulnerabilities-known-spectre-meltdown/),[4](https://www.ibm.com/blogs/psirt/potential-impact-processors-power-family/) |
| iOS | 11.2.2 | 01/08/2018 | [1](https://support.apple.com/en-us/HT208401) |
| Linux kernel | 4.15.0 | ~01/21/2018| |
| Linux kernel | 4.14.11 | 01/03/2018 | [1](https://cdn.kernel.org/pub/linux/kernel/v4.x/ChangeLog-4.14.11) |
| Linux kernel | 4.9.75 | 01/05/2018 | [1](https://cdn.kernel.org/pub/linux/kernel/v4.x/ChangeLog-4.9.75) |
| Linux kernel | 4.4.110 | 01/05/2018 | [1](https://cdn.kernel.org/pub/linux/kernel/v4.x/ChangeLog-4.4.110)|
| macOS High Sierra | 10.13.2 | 12/06/2017 | [1](https://support.apple.com/en-us/HT208331) |
| macOS Sierra Security Update 2018-001 | 10.12.7 | 01/23/2018 | [1](https://support.apple.com/en-us/HT208465) |
| OS X El Capitan Security Update 2018-001 | 10.11.7 | 01/23/2018 | [1](https://support.apple.com/en-us/HT208465) |
| Windows 10 1709 (32-bit only) | KB4073291 | 01/18/2017 | [l](https://support.microsoft.com/en-us/help/4073291) |
| Windows 10 1709 / Windows Server 1709 | KB4056892 | 01/03/2018 | [1](https://support.microsoft.com/en-us/help/4056892),[2](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV180002),[3](https://support.microsoft.com/en-us/help/4073757) |
| Windows 10 1703 | KB4056891 | 01/03/2018 | [1](https://support.microsoft.com/en-us/help/4056891),[2](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV180002),[3](https://support.microsoft.com/en-us/help/4073757) |
| Windows 10 1607 / Windows Server 2016 | KB4056890 | 01/03/2018 | [1](https://support.microsoft.com/en-us/help/4056890),[2](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV180002),[3](https://support.microsoft.com/en-us/help/4073757) |
| Windows 10 1511 | KB4056888 | 01/03/2018 | [1](https://support.microsoft.com/en-us/help/4056888),[2](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV180002),[3](https://support.microsoft.com/en-us/help/4073757) |
| Windows 10 1507 | KB4056893 | 01/03/2018 | [1](https://support.microsoft.com/en-us/help/4056893),[2](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV180002),[3](https://support.microsoft.com/en-us/help/4073757) |
| Windows 8.1 / Windows Server 2012 R2 | KB4056898 | 01/03/2018 | [1][3](https://support.microsoft.com/en-us/help/4056898), [2](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV180002),[3](https://support.microsoft.com/en-us/help/4073757) |
| Windows 7 SP1 / Windows Server 2008 R2 SP1 (Monthly Rollup) | KB4056894 | 01/04/2018 | [1](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV180002),[2](https://support.microsoft.com/en-us/help/4073757/),[3](https://support.microsoft.com/en-us/help/4056894) |
| Windows 7 SP1 /Windows Server 2008 R2 SP1 (Security Update Only) | KB4056897 | 01/03/2018 | [1](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV180002),[2](https://support.microsoft.com/en-us/help/4073757/),[3](https://support.microsoft.com/en-us/help/4056897) |
| Windows Server 2012 | TBD | TBD | |
| Windows Server 2008 SP2 | TBD | TBD | |

### Application Software

#### Browsers

| Product | Version | Release Date | Links |
| --- | --- | --- | --- |
| Chrome 63 | 63.0.3239.132 | 01/05/2018 | [1](https://www.chromium.org/Home/chromium-security/ssca),[2](https://chromereleases.googleblog.com/2018/01/stable-channel-update-for-desktop.html) |
| Chrome 64 | 64.0.3282.119 | 01/24/2018 | [1](https://support.google.com/faqs/answer/7622138#chrome),[2](https://github.com/v8/v8/wiki/Untrusted-code-mitigations),[3](https://chromereleases.googleblog.com/2018/01/stable-channel-update-for-desktop_24.html) |
| Edge | Windows 10 OS patch | 01/03/2018 | [1](https://blogs.windows.com/msedgedev/2018/01/03/speculative-execution-mitigations-microsoft-edge-internet-explorer/) |
| Firefox | 57.0.4 | 01/04/2018 | [1](https://www.mozilla.org/en-US/security/advisories/mfsa2018-01/),[2](https://blog.mozilla.org/security/2018/01/03/mitigations-landing-new-class-timing-attack/) |
| Firefox ESR | 52.6 | 01/23/2018 | [1](https://www.mozilla.org/en-US/security/advisories/mfsa2018-01/),[2](https://blog.mozilla.org/security/2018/01/03/mitigations-landing-new-class-timing-attack/) |
| Internet Explorer 11 | January 2018 patches | 01/03/2018 | [1](https://blogs.windows.com/msedgedev/2018/01/03/speculative-execution-mitigations-microsoft-edge-internet-explorer/) |
| Internet Explorer 10 on Windows Server 2012 | TBD | | |
| Internet Explorer 9 on Windows Server 2008 SP2 | TBD | | |
| Opera | 50.0.2762.67 | 01/22/2018| [1](https://blogs.opera.com/desktop/2018/01/opera-50-0-2762-67-stable-update/) |
| Safari on macOS High Sierra 10.13.2 | 11.0.2 / 11.0.2 (13604.4.7.1.6) or 11.0.2 (13604.4.7.10.6)| 01/08/2018 | [1](https://support.apple.com/en-us/HT208397) |
| Safari on macOS Sierra 10.12.6  |  11.0.2 (12604.4.7.1.6) | 01/08/2018| [1](https://support.apple.com/en-us/HT208403) |
| Safari on OS X El Capitan 10.11.6 | 11.0.2 (11604.4.7.1.6) | 01/08/2018| [1](https://support.apple.com/en-us/HT208403) |

#### Virtualization

| Product | Version | Release Date | Links |
| --- | --- | --- | --- |
| Citrix XenServer 7.3 | XS73E002 | 01/22/2018 | [1](https://support.citrix.com/article/CTX231721),[2](https://support.citrix.com/article/CTX231390) |
| Citrix XenServer 7.2 | XS72E015 | 01/22/2018 | [1](https://support.citrix.com/article/CTX231720),[2](https://support.citrix.com/article/CTX231390) |
| Citrix XenServer 7.1 | XS71ECU1010 | 01/22/2018 | [1](https://support.citrix.com/article/CTX231719),[2](https://support.citrix.com/article/CTX231390) |
| Citrix XenServer 7.0 | XS70E050 | 01/19/2018 | [1](https://support.citrix.com/article/CTX230787),[2](https://support.citrix.com/article/CTX231390) |
| Citrix XenServer 6.5 SP1 | None | Never | [1](https://support.citrix.com/article/CTX231390) |
| Citrix XenServer 6.2 SP1 | None | Never | [1](https://support.citrix.com/article/CTX231390) |
| Citrix XenServer 6.0.2 Common Criteria | None | Never | [1](https://support.citrix.com/article/CTX231390) |
| QEMU | 2.11.1 | TBD | [1](https://www.qemu.org/2018/01/04/spectre/) |
| VMware ESXi 6.5 | ESXi650-201712101-SG | 12/19/2017 | [1](https://kb.vmware.com/s/article/2151099), [2](https://kb.vmware.com/s/article/2151102),[3](https://kb.vmware.com/s/article/52345),[4](https://www.vmware.com/us/security/advisories/VMSA-2018-0002.html) |
| VMware ESXi 6.0 | ESXi600-201711101-SG | 11/09/2017 | [1](https://kb.vmware.com/kb/2151132),[2](https://kb.vmware.com/s/article/2151126),[3](https://kb.vmware.com/s/article/52345),[4](https://www.vmware.com/us/security/advisories/VMSA-2018-0002.html) |
| VMware ESXi 5.5 | ESXi550-201801301-BG | 01/22/2018 | [1](https://kb.vmware.com/s/article/52406),[2](https://kb.vmware.com/s/article/52345),[2](https://www.vmware.com/us/security/advisories/VMSA-2018-0002.html) |
| VMware Fusion 10 / Fusion Pro 10 | 10.1.1 | 01/09/2018 | [1](https://www.vmware.com/us/security/advisories/VMSA-2018-0004.html) |
| VMware Fusion 8 / Fusion Pro 8 | 8.5.10 | 01/09/2018 | [1](https://www.vmware.com/us/security/advisories/VMSA-2018-0004.html),[2](https://www.vmware.com/us/security/advisories/VMSA-2018-0002.html) |
| VMware Workstation Pro 14 / Workstation Player 14 | 14.1.1 | 01/09/2018 | [1](https://www.vmware.com/us/security/advisories/VMSA-2018-0004.html) |
| VMware Workstation Pro 12 / Workstation Player 12 | 12.5.9 | 01/09/2018 | [1](https://www.vmware.com/us/security/advisories/VMSA-2018-0004.html),[2](https://www.vmware.com/us/security/advisories/VMSA-2018-0002.html) |
| Xen Project | | TBD| [1](https://xenbits.xen.org/xsa/advisory-254.html) |

#### Other
| Product | Version | Release Date | Links |
| --- | --- | --- | --- |
| VMware VCenter 6.5 | 6.5 U1e | 01/09/2018 | [1](https://www.vmware.com/us/security/advisories/VMSA-2018-0004.html),[2](https://kb.vmware.com/s/article/52085) |
| VMware VCenter 6.0 | 6.0 U3d | 01/09/2018 | [1](https://www.vmware.com/us/security/advisories/VMSA-2018-0004.html),[2](https://kb.vmware.com/s/article/52085)|
| VMware VCenter 5.5 | 5.5 U3g | 01/09/2018 | [1](https://www.vmware.com/us/security/advisories/VMSA-2018-0004.html),[2](https://kb.vmware.com/s/article/52085)|

### Devices