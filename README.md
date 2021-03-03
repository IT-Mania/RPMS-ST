Mesa 20.3.4 for Fedora 32 Tron Edition 

cd /etc/yum.repos.d/

sudo wget https://raw.githubusercontent.com/IT-mania/RPMS-ST/master/ps4_.repo

sudo dnf update --refresh --repo ps4_

sudo dnf install mesa-dri-drivers-20.3.4-2.fc32.i686 mesa-libEGL-20.3.4-2.fc32.i686 mesa-libGL-20.3.4-2.fc32.i686 mesa-libd3d-20.3.4-2.fc32.i686 mesa-libgbm-20.3.4-2.fc32.i686 mesa-vulkan-drivers-20.3.4-2.fc32.i686 --repo ps4_
