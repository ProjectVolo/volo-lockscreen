## Project Volo Material Design LightDM Theme

This is a theme for LightDM's Webkit2 theme engine (`lightdm-webkit2-greeter`).

### Screenshots
TODO

### Features
Currently the same as the abandoned project it was forked from:

- Selecting an available user from a dropdown box
- Entering their password
- Seeing their profile picture
- Restarting the computer
- Shutting the computer down
- Suspending the computer
- Hibernate
- Select session (GNOME, KDE, Xfce or other installed DE)
- Select your language
- 3 different types of background (trianglify, particleground, and image)
- Option to select keyboard layout (eq. pl_PL for Polish keyboard, en_US for English)
- HiDpi screen support (2000px in width or more)
- A clock with seconds

### How to install

See Wiki (Link Soon)

### Updating
1. In the terminal, `cd` to `/usr/share/lightdm-webkit/themes/lightdm-webkit-material/`
2. Pull changes from repository, `git pull`
*Part of system update soon*

### Setting your own user picture
Add `Icon=/var/lib/AccountsService/icons/<youraccountname>` to the bottom of `/var/lib/AccountsService/users/<youraccountname>` and place a profile image at `/var/lib/AccountsService/icons/<youraccountname>`
*Make this simple*

### Setting a custom background image

- Put a `jpg` at `/var/lib/AccountsService/wallpapers/lightdm-webkit.jpg` (*You may need to create the wallpapers directory*) and set background engine to image in the settings
*This too*

### Setting multiple custom background images to pick from

- Put a `jpg` or a `png` in `/var/lib/AccountsService/wallpapers` or in a directory specified by the `background_images` variable in your `/etc/lightdm/lightdm-webkit2-greeter.conf` (either the `greeter` or the `branding` section) and set the background engine to random image in the settings.
*Yet again*

### Other
Fallback image background: No Man's Sky
*Change this*
