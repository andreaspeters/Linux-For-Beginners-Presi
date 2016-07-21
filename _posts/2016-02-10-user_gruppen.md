---
title: User, Gruppen und deren Rechte
layout: slide
---

## User, Gruppen und deren Rechte

Ersteinmal ein paar Befehle:

- ```useradd -m -s /bin/false yoda```
- ```groupadd jedi```
- ```usermod -s /bin/bash -aG jedi yoda```
- ```id yoda```
- ```userdel -r yoda```

Bitte den User Yoda neuerstellen und sofort der Gruppe jedi und die Shell bash zuweisen.

- ```chown yoda: Verzeichnis```
- ```chmod 600 Verzeichnis```
