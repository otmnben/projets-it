# Projets IT — Ottmane Benamer

Technicien support · Systèmes & Réseaux

Je documente ici mes projets pratiques en **systèmes**, **réseaux** et **support IT**.
Chaque projet est une fiche PDF détaillée : le contexte, la mise en place étape par étape,
le problème rencontré, et la vérification.

---

## Windows Server & Active Directory

- **[Installation d'Active Directory & création du domaine](projet-installation-ad-domaine.pdf)**
  Promotion d'un serveur vierge en contrôleur de domaine, création de la forêt `RoseLingerie.fr`.

- **[Création automatisée de comptes AD en PowerShell](projet-script-creation-utilisateurs-ad.pdf)**
  Un script qui lit un CSV et crée 22 comptes d'un coup, avec changement de mot de passe imposé.

- **[Installation du rôle DHCP & création de l'étendue](projet-installation-dhcp.pdf)**
  Distribution automatique des adresses IP : étendue, exclusions, options, autorisation dans l'annuaire.

## Réseau & Cisco

- **[Routage statique entre deux sites distants](projet-routage-statique.pdf)**
  Routes statiques configurées dans les deux sens, vérifiées au `tracert`.

## Linux & services

- **[Wiki interne avec Wiki.js sur Debian](projet-wikijs-linux.pdf)**
  Pile applicative complète — Node.js, PostgreSQL, Wiki.js — montée en ligne de commande.

- **[Filtrage DNS réseau avec Pi-hole](projet-pihole.pdf)**
  Blocage des pubs et traceurs, avec diagnostic des contournements (DNS box, DoH, IPv6).

- **[Sauvegarde automatique d'une base MariaDB](projet-mariadb.pdf)**
  Sauvegarde quotidienne automatisée sous Linux, avec correction d'une tâche `cron`

