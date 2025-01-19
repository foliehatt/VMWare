# VMWare
VMWare tips and tricks

WMVware vCenter password recovery
1. Reboot VVSA.
2. Hit "e" during Photon bootscreen.
3. Append rw init=/bin/bash to the linux line.
4. F10 to continue
5. At the shell, type passwd and set new passowrd for root user.
6. Login as root and enable SSH
7. SSH in and run command /usr/lib/vmware-vmdir/bin/vdcadmintool + 3
All done :)

Source: https://www.kablog.nl/2019/10/07/reset-administratorvsphere-local-and-root-password-vcsa/
