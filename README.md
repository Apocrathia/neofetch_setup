# neofetch setup scripts

This is a small collection of 3 scripts

* neofetch_install - Installs `neofetch`
* neofetch_update - Updates `neofetch`
* neofetch_motd - Adds `neofetch` to motd

All you do is run `neofetch_install` and it'll take care of the rest.

Default configuration is created at `$HOME/.config/neofetch/config.conf`.

[Customization of the configuration is detailed here.](https://github.com/dylanaraps/neofetch/wiki/Customizing-Info)

**This has only been tested on Ubuntu 18.04.1 LTS. YMMV**

## Usage

1. Run `neofetch_install`
2. (Optional) Run `neofetch_motd`
3. Open a new terminal

(Note: This is a temporary solution, and I will most likely turn this into a simple Ansible playbook at a later date.)
