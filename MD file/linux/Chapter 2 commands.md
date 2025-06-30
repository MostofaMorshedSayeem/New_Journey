# Chapter 1

**Update Ubuntu Linux**

```bash
sudo apt update
sudo apt full-upgrade
```

**Install additional software** (which will allow the installation of useful drivers)

```bash
sudo apt install build-essential linux-headers-generic dkms
```

**Install the Guest Additions**

In VirtualBox menu bar: Devices > *Insert Guest Additions CD Image…*

Execute VBoxLinuxAdditions.run