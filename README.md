# Souffle Zen

Application web de cohérence cardiaque, pensée pour le téléphone.

## Fonctionnalités

- **Séance guidée** : une orbe qui gonfle à l'inspiration et dégonfle à l'expiration. La durée est réglable de 1 à 30 min (5 min par défaut). Trois rythmes au choix : 5 s / 5 s, 4 s / 6 s et 5,5 s / 5,5 s.
- **Musique zen** générée en direct (Web Audio), avec un volume réglable.
- **Vibrations** à chaque changement : 1 pour inspirer, 2 pour expirer.
- **Signal sonore** optionnel, pour faire la séance les yeux fermés quand la vibration n'est pas disponible.
- **Série quotidienne** remise à zéro si un jour est manqué, avec calendrier du mois et paliers à débloquer.
- **Rappel** affiché dans l'app à partir de l'heure choisie.
- **8 thèmes** : Lagon (défaut), Nuit, Printemps, Été, Automne, Halloween, Hiver et Noël.

## Utilisation

Tout tient dans `index.html`, sans dépendance ni compilation. Pour l'utiliser sur le téléphone :

1. Activez GitHub Pages sur ce dépôt (Settings → Pages → branche `main`, dossier racine).
2. Ouvrez l'adresse obtenue sur le téléphone.
3. Ajoutez la page à l'écran d'accueil : elle s'ouvre alors comme une application, avec son icône.

Les données (série, réglages) sont enregistrées localement dans le navigateur du téléphone.

## Limites

- Safari sur iPhone ne permet pas la vibration depuis une page web. Le signal sonore prend le relais.
- Sur iPhone, le mode silencieux coupe le son.
