#  Main Obsidian Config
Since I'm on Arch, this will be my main config which will include all the plugins, themes, Icon Packs, Images, Banners and everything I could possibly gather to  maintain my vault

If you're using Arch like me, you could simply install it from arch repository 

	sudo pacman -S Obsidian

Or even better, use Snap Installer to make sure you don't have to go through dependency hell. First, make sure you have snap installed. you can install it via

	git clone https://aur.archlinux.org/snapd.git
	cd snapd
	makepkg -si

Once installed, the *systemd* unit that manages the main snap communication socket needs to be enabled:

	sudo systemctl enable --now snapd.socket

Then install obsidian		
	
	sudo snap install obsidian --classic

:LiHeadphones:

