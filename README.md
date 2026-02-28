# Commands-to-install-the-Environment-and-programs

This Command Installs the Repos

5: pkg install x11-repo tur-repo root-repo

----------------------------------------------------------------------------------------------------------------------

This Command Installs the File Grabers

6: pkg install curl wget git

----------------------------------------------------------------------------------------------------------------------

This Command Installs the Desktop Environmet

7: pkg install xfce4 xfce4-goodies termux-x11-nightly

----------------------------------------------------------------------------------------------------------------------

These are Needed Programs to install

8: pkg install florence code-oss firefox ark

9: pkg install neofetch xorgproto nano

10: pkg install termux-exec clang inxi

11: pkg install mesa-zink mesa-demos virglrenderer-android htop

----------------------------------------------------------------------------------------------------------------------

These Commands is to Install Audio

12: pkg install pulseaudio

13: pulseaudio --start

----------------------------------------------------------------------------------------------------------------------

Then Finaly the Launch Command

termux-x11 :0 -xstartup "dbus-launch --exit-with-session xfce4-session"

And Thus a Native Termux Desktop Environment

![Screenshot_20260216_152457_TermuxX11](https://github.com/user-attachments/assets/f34eae2a-1ea6-4866-b082-87ddedc9832b)

if you want the wallpaper here it is

https://www.deviantart.com/jesuisnerd/art/Minimalist-Arch-Linux-Wallpaper-1920x1200-297370344

----------------------------------------------------------------------------------------------------------------------

Bonus programs

This Command Installs Dosbox

pkg install dosbox

the config file is in  ~/home/.dosbox

run this command to edit the dosbox config

nano ~/.dosbox/dosbox-0.74-3.conf

In the Config for Dosbox Paste This into the Text File at the Bottom

mount c /data/data/com.termux/files/home/Downloads

C:

Now Dosbox is Install

----------------------------------------------------------------------------------------------------------------------

I Know the Title Does Say no Scripts But This Program is an Exception to Termux

WOW64 is xow64 but wine to run .exe programs in termux

This Commnads is to Install WOW64

1: cd $HOME && rm -rf ~/xow64 && wget https://github.com/ar37-rs/xow64-wine/raw/refs/heads/main/xow64 && chmod +x ~/xow64

2: ~/xow64 install
