# archlinux-virt-manager

Step1: sudo pacman -S qemu virt-manager ebtables dnsmasq<br>
Step2: sudo usermod -aG libvirt (username)<br>
Step3: sudo systemctl enable --now virtqemud<br>
Step4: sudo systemctl enable --now virtstoraged<br>
Step5: sudo systemctl enable --now virtnetworkd<br><br>

virt-manager ready to go!
