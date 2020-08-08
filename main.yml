---
- hosts: web
  become: yes
  tasks:
  - name: Patching on redhat and Amazone instances
    yum:
      name: "*"
      state: latest
  - name: Reboot OS after patching
    command: shutdown -r +1 “Rebooting System After Patching”

