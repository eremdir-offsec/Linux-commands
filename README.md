## Ce que contient le manuel

- Des explications simples sur le rôle de chaque commande.
- Une syntaxe réutilisable et **trois exemples par fiche** : débutant, intermédiaire et avancé.
- Une rubrique dédiée **« Options les plus utiles »**, qui explique leur effet et leur utilisation.
- Des résultats attendus et des cas d’utilisation en pentest.
- Des bonnes pratiques, des erreurs fréquentes et des encadrés « Conseil » et « Attention ».
- Des tableaux de synthèse, un glossaire, des exercices progressifs et des références officielles.

Le guide couvre les environnements **Kali Linux, Ubuntu, Debian et Parrot OS**. Les outils installés, leurs options et les droits nécessaires peuvent varier selon la distribution et la version utilisée.

## Choisir son parcours

| Niveau | Public | Objectif | Sections |
| --- | --- | --- | --- |
| **1 — Débutant cybersécurité** | Peu ou pas d’expérience sous Linux | Prendre en main le terminal, les fichiers, les permissions, les processus et le réseau | 1 à 5 |
| **2 — Débutant Pentest** | Bases Linux acquises | Découvrir les services et réaliser une première énumération structurée | 6 à 9 |
| **3 — Intermédiaire** | Pratique régulière en laboratoire ou en audit interne | Croiser les informations d’annuaire, les captures réseau et les transferts | 10 à 12 |
| **4 — Avancé** | Pratique confirmée du pentest | Comprendre les sessions de laboratoire, analyser les privilèges et assurer la traçabilité | 13 à 16 |

Les mentions « débutant », « intermédiaire » et « avancé » dans une fiche indiquent une progression **à l’intérieur de l’outil**. Elles ne remplacent pas le niveau du chapitre.

## Sommaire

| Section | Thème |
| --- | --- |
| 01 | Commandes Linux de base |
| 02 | Navigation et recherche |
| 03 | Gestion des permissions |
| 04 | Gestion des processus |
| 05 | Réseau Linux |
| 06 | Scanner de ports |
| 07 | Énumération web |
| 08 | Énumération réseau |
| 09 | Énumération SMB — Server Message Block |
| 10 | Énumération Active Directory |
| 11 | Capture réseau |
| 12 | Transfert de fichiers |
| 13 | Reverse shells et bind shells |
| 14 | Escalade de privilèges Linux |
| 15 | Journalisation et logs |
| 16 | Astuces Linux pour pentesters |

Des compléments présentent notamment les options de Nmap, les mauvaises configurations, un aide-mémoire quotidien et des exercices pour chaque niveau.

## Des options expliquées clairement

Chaque fiche place les explications des options juste après la syntaxe, afin de comprendre une commande avant de reprendre ses exemples.

Par exemple :

```bash
ls -lah ~/lab
```

| Élément | Explication |
| --- | --- |
| `ls` | Liste les entrées du dossier indiqué |
| `-l` | Affiche les informations détaillées, notamment les droits, le propriétaire et la taille |
| `-a` | Inclut les noms cachés commençant par un point, ainsi que `.` et `..` |
| `-h` | Rend les tailles plus faciles à lire avec l’affichage détaillé |
| `~/lab` | Désigne le dossier `lab` du répertoire personnel ; c’est un argument, pas une option |

Une page d’introduction explique aussi les options courtes et longues, les valeurs à fournir, le regroupement d’options et l’importance des majuscules et minuscules.

## Utiliser le guide

1. Choisir le niveau correspondant à ses connaissances ou retrouver une commande dans l’index.
2. Lire la description, la syntaxe et les options utiles.
3. Préparer les fichiers, comptes et machines nécessaires à l’exemple.
4. Adapter les chemins, interfaces et adresses à son propre laboratoire.
5. Observer le résultat et le comparer à l’explication du manuel.
6. Consulter les bonnes pratiques et les erreurs fréquentes avant d’intégrer la commande à une procédure.

Pour consulter les documents, aucune installation d’outil de pentest n’est nécessaire. La pratique demande un environnement Linux et les programmes du chapitre concerné. Vérifier leur aide et leur version avant de reprendre une option.

## Cadre de pratique

Les exemples sont destinés aux machines personnelles, aux plateformes de formation et aux environnements faisant l’objet d’une autorisation explicite. Définir le périmètre avant toute action active et utiliser un laboratoire isolé pour les exercices de shells ou de privilèges.

Les adresses et identités illustratives du manuel doivent être adaptées à l’environnement autorisé. Un résultat attendu décrit une observation possible ; il ne garantit pas le comportement d’une cible ni la présence d’une vulnérabilité.

## Version du document

**Version 1.1 — Mise à jour du 1er novembre 2026**

Cette révision ajoute une rubrique « Options les plus utiles » dans les 96 fiches ainsi qu’une introduction pour apprendre à lire et à choisir les options. Le sommaire et l’index accompagnent la pagination révisée.

## Signaler une correction

Pour proposer une amélioration, ouvrir une *issue* dans ce dépôt en indiquant :

- la section, la page et la commande concernées ;
- la distribution et la version de l’outil, si pertinentes ;
- l’erreur observée et la correction proposée ;
- un lien vers la documentation officielle, si disponible.

Retirer les mots de passe, les clés, les données personnelles et les informations confidentielles de tout exemple partagé.

