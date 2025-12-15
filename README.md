сбор логов с посмощью rsyslog.

схема:
C:\vagrant_logs\
├── Vagrantfile
└── ansible\
    ├── playbook.yml
    ├── inventory.ini
    ├── ansible.cfg
    └── templates\
        ├── nginx.conf.j2
        ├── rsyslog-web.conf.j2
        └── rsyslog-log.conf.j2

файлы во вложени в архиве.
