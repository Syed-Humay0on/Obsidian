![Obsidian](/image)
#  My Personal Obsidian Workspace 
This will be my main config which will include all the plugins, themes, Icon Packs, Images, Banners and everything I could possibly gather to  maintain all my Obsidian vault

If you're using [**Arch**](https://archlinux.org/) like me, you could simply install it from arch repository 

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

Now you're good to go! install plugins, apply custom or built in themes, sync with GitHub to automate your workflow whilst also enhancing your Note taking experience 