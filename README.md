# archlinux-keyringupdater

Very simple bash script. Updates archlinux-keyring first then proceeds to update the whole system. 

If you haven't updated your system in a while, when running `<sudo pacman -Syu>` without updating the `<archlinux-keyring>` package, it will throw a lot of errors and generally be a pain in the ass. So, you have to first update `<archlinux-keyring>` then proceed to update the whole system. This very simple bash script does just that.

To install,

1. Clone the repo
2. cd in to the cloned repo
3. Create an alias for the .sh script or just run it as `<sh auto-arch-keyring.sh>`.

Example alias command: `<alias autoupgrade="sh ~/YourFolder/auto-arch-keyring.sh">`
