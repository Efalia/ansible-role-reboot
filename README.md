# Reboot

Redémarre la machine si le rôle détecte qu'elle en a besoin : 
- La machine contient un fichier `/run/reboot-required` (standard debian)
- La machine contient un fichier `/tmp/need-reboot` (script migration debian12)
- La version du kernel executée est différente du dernier kernel installé

Requirements
------------

Aucun

Role Variables
--------------

Aucune

Dependencies
------------

Aucune

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
        - ../roles/reboot


License
-------

MIT
