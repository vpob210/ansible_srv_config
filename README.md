.
├── ansible.cfg
├── inventory.ini
├── playbooks
│   └── configure-server.yml
├── README.md
└── roles
    ├── add-user
    │   ├── tasks
    │   │   └── main.yml
    │   └── templates
    │       ├── testuser_ssh_key
    │       └── testuser_ssh_key.pub
    └── deploy-bin
        ├── tasks
        │   └── main.yml
        └── templates
            ├── app.conf
            ├── multisocket.bin
            ├── singlesocket.bin
            └── web.conf
