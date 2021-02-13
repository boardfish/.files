# boardfish's dotfiles

Configure linux workstation using Ansible.

Most of this runs on the assumption that you're on an Arch Linux-based distro
like Manjaro. It might not install some essentials under the assumption that
they're part of your distro. For best results, run on Manjaro with GNOME.

Based on [@kespinola](https://github.com/kespinola)'s dotfiles, as explained by
their [blog
post](https://medium.com/espinola-designs/manage-your-dotfiles-with-ansible-6dbedd5532bb).

### Languages

Languages are managed with [asdf](https://asdf-vm.com/#/). Investigate their
Ansible roles for more insight into what gets done for each one.

### Packages

Check out the `pacman` and `aur` roles to see which packages the playbook will
attempt to install.

## Bootstrap

Clone this repository into the `.files` folder.

Run the dot-bootstrap command.

```
$ ~/.files/bin/dot-bootstrap
```

This'll be added to your PATH so that you can run any scripts defined in 
`$DOTFILES_PATH/bin`.

```
$ dot-bootstrap
```
