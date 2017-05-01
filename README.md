## Project Volo Material Design LightDM Theme

This is a theme for LightDM's Webkit2 theme engine (`lightdm-webkit2-greeter`).
Based on https://github.com/artur9010/lightdm-webkit-material by artur9010

### Screenshots
TODO

### Features
You can:
- Select a user from a dropdown box
- Enter the password
- Seeing a profile picture
- Restart the computer
- Shut the computer down
- Suspend the computer
- Hibernate the computer
- Select session (GNOME, Budgie, KDE, Xfce or other installed DE)
- Select your language
- Option to select keyboard layout (eq. pl_PL for Polish keyboard, en_US for English)
- HiDpi screen support (2000px in width or more)
- A clock with seconds

### How to install

See Wiki (Link Soon)

### Code only gets here by being tested in both Upcoming and Dev

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
