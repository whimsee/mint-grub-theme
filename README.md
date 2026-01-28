# Moe moe BOO!
The Ghost Maid Mint Fantôme is coming to haunt your PC!  
Custom Mint Fantôme GRUB theme  
Base elements from [crossgrub](https://github.com/krypciak/crossgrub) with modifications.  
Wallpaper from [Maid Mint Ch. ミント・ファントーム](https://www.youtube.com/post/UgkxPEoUeDnLxONT5q7QUxDnoaMiHFRp90qJ)

<img width="1917" height="1077" alt="mint-grub" src="https://github.com/user-attachments/assets/cc7d73da-f7a6-4a55-b6a9-298dc118f757" />

## Installation

### From source

- Clone the repository or download the source from the release page
```bash
git clone https://github.com/whimsee/mint-grub-theme.git
```
*The following may vary depending on your distro*

- Copy the "mint" folder to `/boot/grub/themes`

- Change/add this line in your `/etc/default/grub`:
```
GRUB_THEME='/boot/grub/themes/mint/theme.txt'
GRUB_GFXMODE='1920x1080'
GRUB_TERMINAL_OUTPUT='gfxterm'
```

- Update your live grub config by running:
```
sudo grub-mkconfig -o /boot/grub/grub.cfg
```

- Done!

- If you want, you can preview the theme using [grub2-theme-preview](https://github.com/hartwork/grub2-theme-preview) (you need to install it first):
```
grub2-theme-preview /boot/grub/themes/mint --resolution 1920x1080
```
