You may find my ansible playbooks here. Although have a long distance to ansible galaxy, I've begun to build my rocket. As it grows up, I will try to update explanations.

Here we begin.

- `test` role creates a file under {{ directory }}/{{ file }} specified in vars/main.yml, adds a sample line and hostname to the file. Then file content is shown.

- `web` role creates users listed in vars/main.yml, changes users passwords, modify pam.d/sshd file to allow users to ssh, install sudo package and gives users sudo permissions.
