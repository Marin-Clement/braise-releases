# Établi — téléchargements

**L'atelier qui compte.** Aide à la décision pour l'artisanat de Dofus 3 : ce qu'il
faut fabriquer, ce qu'il faut ramasser, et ce que ça rapporte vraiment.

👉 **[Télécharger la dernière version](../../releases/latest)**

Ce dépôt ne contient **que les binaires**. Le code source vit ailleurs.

## Quel fichier prendre

| Ton système | Le fichier |
|---|---|
| Windows | `Etabli-<version>-win-x64-setup.exe` — l'installateur |
| Windows, sans installer | `Etabli-<version>-win-x64.zip` — à dézipper, portable |
| macOS (Apple Silicon) | `Etabli-<version>-arm64.dmg` |

## Au premier lancement

Les paquets ne sont **pas signés par un certificat payant** — c'est une app entre
amis, pas un logiciel commercial. Chaque système s'en méfie une fois :

- **Windows** : « Windows a protégé votre ordinateur » → **Informations
  complémentaires** → **Exécuter quand même**.
- **macOS** : au premier lancement, **Réglages Système › Confidentialité et
  sécurité** → **Ouvrir quand même**. Si macOS dit que l'app est « endommagée »,
  c'est la quarantaine : `xattr -cr "/Applications/Établi.app"`.

L'installation Windows se fait dans ton dossier utilisateur : **aucun droit
administrateur** n'est demandé.

## Le mode live

L'app peut se remplir toute seule pendant que tu joues — prix, cours du marché,
niveaux de métier, inventaire, kamas, et l'XP réellement gagnée. Elle **lit
passivement** le trafic que ton client Dofus reçoit déjà : elle ne parle jamais au
jeu, n'injecte rien, ne lit aucune mémoire et n'automatise aucune action.

Pour ça il faut **[Npcap](https://npcap.com/#download)** sur Windows (gratuit,
options par défaut). L'installateur te le rappelle s'il manque. Sur macOS, une
autorisation unique est demandée au premier passage en capture.

Tout fonctionne aussi sans : les prix se saisissent alors à la main.

## Tes données

Elles restent **chez toi**, dans une base locale — rien n'est envoyé nulle part.
Une désinstallation ne les efface pas.
