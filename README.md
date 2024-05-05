<div align="center">

## Puppy's SDDM Theme

![GitHub Repo stars](https://img.shields.io/github/stars/PuppyAnimations/SDDM-Theme?style=for-the-badge&color=cba6f7) ![GitHub last commit](https://img.shields.io/github/last-commit/PuppyAnimations/SDDM-Theme?style=for-the-badge&color=b4befe) ![GitHub repo size](https://img.shields.io/github/repo-size/PuppyAnimations/SDDM-Theme?style=for-the-badge&color=cba6f7)

<br/>
</div>

<h2 align=center>Preview</h2>
<center>
   
<div align="center">
   
A Simple theme variant for the <a href="https://github.com/sddm/sddm">SDDM Login Manager</a>

<img src="./Previews/1.png" alt="preview-1">

</div>

## Install
> _Assumes that you've installed and configured SDDM correctly_ (if not [read more](https://wiki.archlinux.org/title/SDDM))

>  Please make sure you have the following dependencies installed for Arch Linux:
- `qt6-5compat` `qt6-declarative` `qt6-svg` `sddm` 

## Configure

Edit the `/etc/sddm.conf.d/10-theme.conf` (with any text editor with **raised** privileges), so that it looks like this:

```bash
sudo nano /etc/sddm.conf.d/10-theme.conf  # use any text editor with raised privileges
---

[Theme]
Current=simple-sddm-2
   ```

### Language and time format
- By default, it is configured with AM/PM format. You can change to 24H variant by editing the theme.conf
```bash
sudo nano /usr/share/sddm/themes/simple-sddm/theme.conf  # use any text editor with raised privileges
```
- `HourFormat="HH:mm` . Make sure to disable the above of this part
- To change the default wallpaper put desired image in the `simple-sddm/Backgrounds/` folder and add the name of the image followed by its extension (`.jpg` or `.png`) in `theme.conf` file.
- You can also customize it further if you wish in the `theme.conf`
(blur, form position, etc).

## Credits
- Full credit goes to [original autor](https://github.com/Keyitdev/sddm-astronaut-theme) by [Keyitdev](https://github.com/Keyitdev).


