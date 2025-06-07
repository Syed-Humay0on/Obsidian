---
banner: "https://images.unsplash.com/photo-1510519138101-570d1dca3d66?q=80&w=1447&auto=format&fit=crop&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D"
---

#  Main Obsidian Config
Since I'm on Arch, this will be my main config which will include all the plugins, themes, Icon Packs, Images, Banners and everything I could possibly gather to  maintain my vault

If you're using **Arch** like me, you could simply install it from arch repository 

	sudo pacman -S Obsidian

Or even better, use Snap Installer to make sure you don't have to go through dependency hell. First, make sure you have snap installed. you can install it via:

	git clone https://aur.archlinux.org/snapd.git
	cd snapd
	makepkg -si

Check the version to ensure it's installed:

	snap --version
	
Once installed, the *systemd* unit that manages the main snap communication socket needs to be enabled:

	sudo systemctl enable --now snapd.socket

Then install obsidian and check the version (latest 1.8.10)	
	
	sudo snap install obsidian --classic

Once Installed, check the version:

	obsidian --version 

