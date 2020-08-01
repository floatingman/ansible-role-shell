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

This works best with my [dotfiles](https://github.com/Allaman/dotfiles) and my [ansible role](https://github.com/Allaman/ansible-role-dotfiles)

Requirements
------------

Git should be installed on the target system.

Role Variables
--------------

No variables

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
