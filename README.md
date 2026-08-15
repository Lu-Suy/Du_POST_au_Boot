# Du POST au Boot

Comprendre le démarrage d’une machine, du PC personnel au serveur en datacenter.

---

## Introduction

Dernièrement, au cours d’un échange technique, un point simple mais fondamental est revenu sur la table : la différence entre **POST** et **Boot**.

Le terme « POST » peut parfois prêter à confusion (y compris sur Wikipédia). Pourtant, en contexte technique — et encore plus en environnement datacenter — cette distinction est essentielle.

→ **[Lire la documentation complète](docs/Le%20D%C3%A9marrage%20D'une%20Machine%20POST%20to%20BOOT.md)**

---

## Contenu

1. [Visualisation ultra-simple](docs/Le%20D%C3%A9marrage%20D'une%20Machine%20POST%20to%20BOOT.md#visualisation-ultra-simple)
2. [Ce qui change en datacenter](docs/Le%20D%C3%A9marrage%20D'une%20Machine%20POST%20to%20BOOT.md#ce-qui-change-en-datacenter)
3. [Les protocoles](docs/Le%20D%C3%A9marrage%20D'une%20Machine%20POST%20to%20BOOT.md#les-protocoles)
4. [Monitoring](docs/Le%20D%C3%A9marrage%20D'une%20Machine%20POST%20to%20BOOT.md#monitoring)
5. [1. POST](docs/Le%20D%C3%A9marrage%20D'une%20Machine%20POST%20to%20BOOT.md#1-post)
6. [2. Peut-on brancher un agent sur le BMC](docs/Le%20D%C3%A9marrage%20D'une%20Machine%20POST%20to%20BOOT.md#2-peut-on-brancher-un-agent-sur-le-bmc)
7. [3. Est-ce que des outils existent déjà](docs/Le%20D%C3%A9marrage%20D'une%20Machine%20POST%20to%20BOOT.md#3-est-ce-que-des-outils-existent-déjà)
8. [4. Comment un technicien utilise iDRAC ou iLO au quotidien](docs/Le%20D%C3%A9marrage%20D'une%20Machine%20POST%20to%20BOOT.md#4-comment-un-technicien-utilise-idrac-ou-ilo-au-quotidien)
9. [5. Est-ce qu'on peut rentrer dans le BIOS ou UEFI](docs/Le%20D%C3%A9marrage%20D'une%20Machine%20POST%20to%20BOOT.md#5-est-ce-quon-peut-rentrer-dans-le-bios-ou-uefi-avec-idrac-ou-ilo)
10. [6. Scénario typique : serveur qui ne boot plus](docs/Le%20D%C3%A9marrage%20D'une%20Machine%20POST%20to%20BOOT.md#6-scénario-typique--serveur-qui-ne-boot-plus)

---

## Points clés

- POST et Boot sont deux phases distinctes et successives
- Le POST est un test hardware réalisé par le firmware (BIOS/UEFI)
- En datacenter, on s’appuie sur les cartes de management (BMC / iDRAC / iLO)
- Redfish est le protocole moderne associé
