# ansible-gamification

## Portal:

Opret login / Login

Login skal være på baggrund af en aktiveringsnøgle (PSK for et firma)

Portalen skal indeholde en playbook til at opsætte et lokalt miljø, så det matcher det på backend.

Portal skal indeholde en list af opgaver, mulighed for at download inventory + prereq data og mulighed for at uploade løsninger

Portal skal kunne vise om den løsning man har uploadet enten er: OK, under behandling eller Forkert

Teknologier:


## Portal Admin del:

Opret nye opgaver, med følgende options: antal af maskiner, prereq data, Inventory mm.

Samtidig skal man for nye opgaver kunne definere forventet resultat, defineret med en playbook

Teknologier:


## Backend:

Backend skal kunne samle en uploadet løsning fra portalen op og teste. Evt ved at køre det i en eller flere containere.

Skal melde svar tilbage til portal/database

Teknologier: Ansible / Molekule

https://www.ansible.com/blog/developing-and-testing-ansible-roles-with-molecule-and-podman-part-1

## Design Metode:

Ops-programmering: Quick and dirty does it.. vi skal ikke bruge uger på det her projekt..
