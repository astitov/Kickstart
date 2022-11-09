# Kickstart
Kickstart auto-install scripts for the RHEL-based. Burn the ISO on a USB stick and plug it in before installation starts.

> To load your Kickstart file automatically without having to specify the inst.ks= boot option, name the file ks.cfg and place it on a storage volume labeled OEMDRV. 
(from [Documentation](https://docs.centos.org/en-US/centos/install-guide/Kickstart2/#sect-kickstart-installation-starting))

The workflow action builds an "OEMDRV" ISO artifact with `ks/ks.cfg` inside.

- **alma8-min-1** -- минимальная Alma 8.6 для виртуалок под ansible, с python и IP-адресом на морде.
