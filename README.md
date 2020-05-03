ansible-role-shell
=========

This roles configures my prefered settings for working with the shell on Linux based systems.

- Install kubectx
- Install kubectx
- Install kubectl-aliases
- Install fzf
- Install fzf-tab
- Install fzf-autosuggestions
- Install zsh-syntax-highlightning
- Install zsh-history-substring-search
- Install zsh-completions
- Install bash-my-aws
- Install Powerlevel10k
- Install diff-so-facy
- Install multi-git-status
- Install SDKMAN
- Setup NeoVim 

This works best with my [dotfiles](https://github.com/Allaman/dotfiles) and 

Requirements
------------

Git should be installed on the target system.

Role Variables
--------------

| Variable| Description | default |
|---------|-------------|---------|
| local_bin_dir | path of folder for user only executables | ~/.local/bin |

Dependencies
------------

No dependencies

Example Playbook
----------------

```
---
- name: Playbook
  hosts: localhost
  connection: local
  roles:
    - ansible-role-shell
```

License
-------

MIT
