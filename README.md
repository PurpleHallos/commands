# Commands that I need but keep forgetting their syntax

<p align="center">
  <img src="bruh.png" alt="Bruh" width="20%">
</p>

## Git
### Submodules
#### Clone repo + submodules
```bash
git clone --recurse-submodules <repository-url>
```
#### Clone submodules in a cloned repo
```bash
git submodule update --init --recursive
```
## Pacman
### Refrech Keyring
```bash
sudo pacman -Sy archlinux-keyring
```
## VirtualBox
### USB device
```bash
sudo usermod -aG vboxusers $USER
```
## Yt-dlp
```bash
yt-dlp -f "bestvideo[height=1080][ext=mp4]+bestaudio[ext=m4a]/best[height=1080][ext=mp4]" -o "%(title)s.%(ext)s" <url>
```
