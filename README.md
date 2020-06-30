# Ansible Role for Peek - A Simple animated GIF screen recorder

This is an Ansible role to setup Peek - A Simple animated GIF screen recorder - on an Arch Linux desktop system.

## Usage

I assume you are already setup [Ansible](https://ansible.com) and your [Ansible playbook](https://docs.ansible.com/ansible/latest/user_guide/playbooks.html) with the [Best Practices](https://docs.ansible.com/ansible/latest/user_guide/playbooks_best_practices.html#directory-layout) in mind.

Go to your playbook root directory and run

```bash
git submodule add https://github.com/ansible-roles-group/ansible-role-peek role/peek
```

This will add the role to your playbook. You now have to add it to your playbook files role section (checkout the [official docs](https://docs.ansible.com/ansible/latest/user_guide/playbooks_reuse_roles.html) if you don't know what I'm talking about). It will look something like this:

```yaml
---

- name: Setup basic stuff for all devices
  hosts: all
  roles:
    - peek
```

# Buy me a cup of tea 🍵

If you like my work feel free to bring some love back. 

- Give this repo a ⭐
- Follow me on [GitHub](https://github.com/BennyLi) or [Twitter](https://twitter.com/BennyLindemann)
- Drop some 💰 via [PayPal](