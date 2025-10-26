![Obsidian](/assets/banners/ObsidianBanner.jpg)
#  Obsidian Workspace 
This will be my main config file which will include all the Notes I work on. This will also includes all the plugins, themes, Icon Packs, Images, Banners and literally everything I could possibly get my hands on to  boost my note taking experience & manage all my Obsidian vaults in my .obsidian file.

> [!IMPORTANT]
If you're using [**Arch**](https://archlinux.org/) like me, you could simply install it from arch repository 

	sudo pacman -S Obsidian

Even better, use Official App Image from their [**GitHub repo**](https://github.com/obsidianmd/obsidian-releases/releases/tag/v1.9.14)  

> [!Note]
> version 1.9.14 is the latest as of right now 

```
wget https://github.com/obsidianmd/obsidian-releases/releases/download/v1.9.14/Obsidian-1.9.14.AppImage -O Obsidian.AppImage
chmod +x Obsidian.AppImage
./Obsidian.AppImage
```

Symlink to Path:
```
sudo ln -s ~/Applications/Obsidian.AppImage /usr/local/bin/obsidian
```
Check the version to ensure it's installed:

	obsidian --version
	
Now you're good to go! install plugins, apply custom or built in themes, sync with GitHub to automate your workflow whilst also enhancing your Note taking experience 
