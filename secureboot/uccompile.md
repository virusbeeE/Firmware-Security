# Custom Live Media, Driver, and Kernel Support
Commercial operating systems (OS) that feature Secure Boot compatibility feature a Microsoft signature on the bootloader. The bootloader may -- particularly in the case of
Linux and Hypervisors -- contain a Machine Owner Key (MOK) used to add an OS vendor's certificate and extend the number of trusted Secure Boot certificates. Any change to
the bootloader, kernel, or driver would invalidate the Microsoft signature or the MOK signature thus resulting in Secure Boot policy violations.

Custom-compiled bootloaders, kernels, and drivers must have signatures added to them to enable Secure Boot support. The quickest and most cost-effective way to add Secure
Boot support involves creating a developer, organization, infrastructure, company, and/or agency certificate associated with a key used for signing binaries checked by Secure
Boot. If the first bootloader is changed, then place the custom certificate in firmware at the Secure Boot DB allow list. If the first bootloader is not changed and continues
to feature a valid Microsoft signature, then consider adding the custom certificate as the first bootloader's MOK.
