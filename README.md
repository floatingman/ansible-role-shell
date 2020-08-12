ansible-role-shell
=========

This roles configures my prefered settings for working with the shell on Linux based systems.

- Install kubectl-aliases
- Install fzf
- Install fzf-tab
- Install fzf-autosuggestions
- Install zsh-syntax-highlightning
- Install zsh-history-substring-search
- Install zsh-completions
- Install bash-my-aws
- Install Powerlevel10k
- Setup NeoVim
- Setup oh-my-tmux

This works best with my [dotfiles](https://github.com/Allaman/dotfiles) and my [ansible role](https://github.com/Allaman/ansible-role-dotfiles)

Requirements
------------

Role Variables
--------------

No variables

Dependencies
------------

- ansible-role-basic

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
