# ansible-role-docker-prep

Prep a RH7 Server for Docker

## Example Playbook

Pretty straight-forward. Install your role anyway you like. Then create a simple playbook with your inventory in a 'servers' (for example):

    - hosts: servers
      become: yes
      become_user: root
      roles:
        - role: staylorx.docker-prep

## License

MIT
