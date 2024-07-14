# Ubuntu Server to Desktop

I started with a base server ISO of Ubuntu 24.04 and used Ansible to configure it into a usable desktop environment. 

## What's it do?

It runs through the updating of cache, updating base packages, then installs the following:

    - GNOME 3 Desktop
    - GNOME Extensions
    - git
    - nano
    - tmux
    - rsync
    - htop
    - python3
    - python3-pip
    - build-essential
    - fail2ban
    - terminator
    - flatpak
    - gimp
    - snapd
    - openconnect
    - network-manager-openconnect
    - network-manager-openconnect-gnome
    - calibre

Once those are installed, I also place Steam and Spotify from ``snap`` and ``flatpak``.

## Adding dotfiles

TODO
