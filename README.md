# archlinux-virt-manager

Step1: sudo pacman -S qemu virt-manager ebtables dnsmasq
Step2: sudo usermod -aG libvirt (username)
Step3: sudo systemctl enable --now virtqemud
Step4: sudo systemctl enable --now virtstoraged
Step5: sudo systemctl enable --now virtnetworkd

virt-manager ready to go!
