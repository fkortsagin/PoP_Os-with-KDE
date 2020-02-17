# PoP_Os-with-KDE
PoP_Os with KDE
# 1. Install Deepin/Gnome/XFCE/KDE/Cinnamon/LXDE/LXQt desktop environments for PoP_OS(choose one):

* sudo apt install pop-desktop
* sudo systemctl restart gdm 


* sudo apt install kde-standard

* Select gdm3 session

* sudo apt install mate-desktop-environment mate-desktop-environment-extras ubuntu-mate-themes


* Select gdm3 session

* sudo apt install cinnamon-desktop-environment

* Select gdm3 session

* sudo apt install gnome-session

* Select gdm3 session

# 2. NVIDIA driver install:
* sudo apt install system76-driver-nvidia

# 3. NVIDIA Cuda Toolkit:
* sudo apt install system76-cuda-latest

# To install the cuDNN library, please run this command:

* sudo apt install system76-cudnn-10.1

Switch to another card using non-default DE:


* sudo system76-power graphics nvidia



# 4. Distro upgrade:
* sudo apt update
* sudo apt full-upgrade
# Optional
* pop-upgrade release upgrade systemd

# 5. Automount second HDD:
* nosuid,nodev,nofail,x-gvfs-show,auto


# 6. Fixing package manager issues:
* sudo apt clean
* sudo apt update -m
* sudo dpkg --configure -a
* sudo apt install -f
* sudo apt dist-upgrade
* sudo apt autoremove --purge
# 7. Installing proper OBS-Studio
sudo apt install obs-studio
