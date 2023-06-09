## Install HCPP
After installing HestiaCP the system will reboot. Once again, the QEMU virtual machine instance should still be running and at the login prompt; leave this running. Now we can install HCPP (Hestia Control Panel Plugins) that furnish us with Code Garden's (Core Open Developer Elements) support for NodeJS, Open VSCode Server, line-by-line debugging in both PHP and NodeJS, Node-RED, psuedo mail server and with client side preview, etc. Within the terminal you used to install HestiaCP you can type the following to install HCPP:

```
./install-hcpp.sh
```

### About HCPP
The HCPP installation process will automatically install each of the repos listed below. You can learn more about each repo at their respective links:

* [HCPP-NodeApp](https://github.com/virtuosoft-dev/hcpp-nodeapp)
* [HCPP-MailCatcher](https://github.com/virtuosoft-dev/hcpp-mailcatcher)
* [HCPP-VSCode](https://github.com/virtuosoft-dev/hcpp-vscode)
* [HCPP-NodeRED](https://github.com/virtuosoft-dev/hcpp-nodered)
* [HCPP-NodeBB](https://github.com/virtuosoft-dev/hcpp-nodebb)
* [HCPP-Ghost](https://github.com/virtuosoft-dev/hcpp-ghost)

After the aforementioned HCPP plugins are installed the VM will automatically shutdown.

The main install-hcpp.sh script will continue with compressing the resulting pws-amd64.img (or pws-arm64.img for ARM processors), along with their required EFI images into a compact, redistributable archive for use with the Code Garden PWS edition application; [cg-pws-app](https://github.com/virtuosoft-dev/cg-pws-app). The resulting filename will be either pws-amd64.tar.xz and/or pws-arm64.tar.xz.


&nbsp;

-----
&nbsp;

Return to the **[README.md](README.md)** for additional instructions and up-to-date information.
