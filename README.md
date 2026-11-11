# XDK Clips — téléchargements

Logiciel Windows (10 et 11) de **XDK TEAM DEV** qui **enregistre tes parties et tes meilleurs moments**, comme Medal,
mais tout reste sur ton PC.

- **F8** en jeu : les **30 dernières secondes** sont enregistrées (le clip est prêt en moins d'une seconde).
- **F9** : enregistre **toute la partie**, jusqu'au prochain appui.
- La capture **démarre toute seule quand tu lances un jeu** et filme l'écran du jeu.

## Télécharger

1. Ouvre la [dernière version](https://github.com/XDTEAMDev/XDK-Clips-releases/releases/latest).
2. Télécharge **`XDKClips.exe`** (le fichier `.sig` à côté sert seulement à vérifier les mises à jour).
3. Lance-le. Au premier lancement, il télécharge FFmpeg (le moteur vidéo, environ 110 Mo), une seule fois.

Il faut le **.NET 8 Desktop Runtime** (x64), gratuit chez Microsoft : https://dotnet.microsoft.com/download/dotnet/8.0
(« .NET Desktop Runtime »).

## Ce qu'il fait

- **Clips instantanés** : l'image et le son des dernières secondes sont gardés en mémoire, un appui sur la touche et
  c'est enregistré, sans perte de qualité.
- **Détection automatique des jeux** (Steam, Epic, Riot, Battle.net, Xbox, Ubisoft, EA, Rockstar, GOG… ou tout jeu en
  plein écran) : les clips sont rangés dans `Vidéos\XDK Clips\<nom du jeu>`.
- **Carte graphique** AMD, NVIDIA ou Intel pour encoder : presque aucun effet sur tes FPS.
- **Son du PC et micro**, calés sur l'image.
- **Bibliothèque** avec miniatures, filtres par jeu, recherche et lecteur.
- **Découpe** précise, **export Discord** (10, 50 ou 500 Mo) copié prêt à coller, renommer, supprimer.
- Bulle « Clip enregistré » en jeu (invisible dans les vidéos) et petit son de confirmation.
- Raccourcis au clavier ou aux **boutons de souris**, qui marchent en plein jeu.
- Reste à côté de l'horloge, peut se lancer avec Windows.

## Gratuit et Premium

XDK Clips est **gratuit** (petit filigrane « XDK Clips », clips jusqu'à 1 min, 60 i/s, 1080p).

**XDK Clips Premium** débloque tout : **sans filigrane**, clips de **2 et 5 min**, qualité **Max**, **120 / 144 i/s**,
HEVC, **1440p et 4K**, **ton son de clip** et **ton logo** sur tes vidéos, badge Premium.

1. Dans XDK Clips, ouvre **Réglages › Premium** et copie le **code de ton PC**.
2. Rejoins le **Discord XDK TEAM DEV** : https://discord.gg/zEC35KSuxt, catégorie 🎬 XDK CLIPS, salon
   🔑・demande-de-clé.
3. **Essai gratuit de 24 h** avec le bouton du salon, ou achat (2,99 € pour 1 mois, 9,99 € à vie) :
   https://xdkvito.gumroad.com/l/xdkclips puis « J'ai acheté ».
4. Le bot t'envoie ta clé en message privé : colle-la dans **Réglages › Premium**.

Une clé ne marche que sur le PC de son code.

## Mises à jour

Automatiques : le logiciel regarde ici s'il existe une nouvelle version, la télécharge, vérifie sa **signature** et
redémarre dessus. Un fichier qui n'est pas signé par XDK TEAM DEV est refusé.

## Ce dépôt

Il ne contient que les versions à télécharger de XDK Clips. Les autres logiciels de XDK TEAM DEV ont leurs propres
pages.
