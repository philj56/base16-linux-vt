# Base16 Linux VT
[Base16](https://github.com/chriskempson/base16) themes for the Linux Virtual Terminal.

![Base16 linux_vt](https://raw.github.com/philj56/base16-linux-vt/master/base16-vt.png)

### Installation:
1. Install the setcolors utility from https://github.com/EvanPurkhiser/linux-vt-setcolors 
(Arch users: [setcolors-git](https://aur.archlinux.org/packages/setcolors-git/)<sup>AUR</sup>)
2. To try out a theme, run `setcolors colors/base16-{theme}`
3. To make the change permanent, add the setcolors command to your startup.
Arch users can install [mkinitcpio-colors](https://aur.archlinux.org/packages/mkinitcpio-colors-git/)<sup>AUR</sup>,
add the `colors` hook to `/etc/mkinitcpio.conf`, copy the `/etc/vconsole.conf`
section from any theme into `/etc/vconsole.conf`, and run `mkinitcpio -p linux`.

To return to the defaults, just remove the relevant startup commands.
