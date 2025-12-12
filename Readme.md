![Obsidian](/assets/banners/ObsidianBanner.jpg)
#  Obsidian Workspace 
This will be my main config file which will include all the Notes I work on. This will also includes all the plugins, themes, Icon Packs, Images, Banners and literally everything I could possibly get my hands on to  boost my note taking experience & manage all my Obsidian vaults in my .obsidian file.

> [!IMPORTANT]
If you're using [**Arch**](https://archlinux.org/) like me, you could simply install it from arch repository 

	sudo pacman -S Obsidian

Or build from source using their official AppImage Installer from their [**GitHub repo**](https://github.com/obsidianmd/obsidian-releases/releases/tag/v1.10.6)  


> [!Note]
> version 1.10.6 is the latest right now 

```
mkdir -p ~/applications
cd ~/applications
wget https://github.com/obsidianmd/obsidian-releases/releases/download/v1.10.6/Obsidian-1.10.6-arm64.AppImage -O Obsidian.AppImage
chmod +x Obsidian.AppImage
./Obsidian.AppImage
```

Check the version to ensure it's installed:

	obsidian --version

### Integrate it into your system menu/Rofi launcher

> [!Warning]
>only if you are using a tiling/scrolling manager and manually setting up your app launcher 


```
mkdir -p ~/.local/share/applications
nvim ~/.local/share/applications/obsidian.desktop
```

Paste the following:
```
[Desktop Entry]
Name=Obsidian
Exec=/home/<your username>/applications/Obsidian.AppImage
Icon=obsidian
Type=applications
Categories=Utility;Office;
StartupNotify=true
Comment=Markdown knowledge base

```

Then
```
update-desktop-database ~/.local/share/applications
```

Symlink to PATH
```
sudo ln -s ~/applications/Obsidian.AppImage /usr/local/bin/obsidian
```
Now you're good to go! Open it via menu or simply run obsidian in terminal, install plugins, apply custom or built in themes, sync with GitHub to automate your workflow whilst also enhancing your Note taking experience 
