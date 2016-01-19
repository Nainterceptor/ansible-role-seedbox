Nainterceptor.mariadb
====================

Role used to install a seedbox on Debian with apt

Requirements
------------

CentOS Supported

Role Variables
--------------

Example Playbook
----------------

    - hosts: servers
      vars:
          rpc_username: "seedbox"
          rpc_password: "seedbox"
          user_password: "" #User password, encoded
          home_dir: "/home/torrent"
          download_dir: "/home/torrent/downloads"
          incomplete_dir: "/home/torrent/incomplete"
      roles:
         - { role: Nainterceptor.seedbox }

License
-------

CC-BY
