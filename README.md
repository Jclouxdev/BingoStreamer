# 🎲 Bingo Stream

**Générateur de bingo gratuit pour streamers Twitch & YouTube.** 100% statique, sans compte, sans backend — tout tourne dans le navigateur.

👉 **[Essayer en ligne](https://jclouxdev.github.io/BingoStreamer/)**

![License](https://img.shields.io/badge/license-MIT-7c5cff)
![No build](https://img.shields.io/badge/build-none-22c55e)
![Static site](https://img.shields.io/badge/hosting-GitHub%20Pages-171a23)

Plein d'outils de bingo pour streamers sont payants ou verrouillés derrière un abonnement pour une fonctionnalité aussi simple qu'une grille qu'on coche en live. Celui-ci est gratuit, le restera, et fonctionne entièrement en local (aucune donnée envoyée à un serveur).

## Fonctionnalités

- **Grilles personnalisables** de 4x4 à 7x7, texte libre par case avec police qui s'auto-ajuste
- **Multi-grilles** : gère plusieurs bingos en parallèle depuis la même sidebar
- **Mode "je coche"** : une fois la grille terminée, clique (ou navigue au clavier) pour cocher en live — ligne/colonne/diagonale complète se surligne automatiquement
- **Case Joker** optionnelle (case centrale offerte, façon bingo classique)
- **Thème couleur** par grille (accent personnalisable)
- **Intégration OBS** : lien Embed dédié par grille, fond transparent, synchronisé en direct avec le panneau de contrôle
- **FR / EN** intégré
- **Persistance locale** via `localStorage`, aucune inscription

## Utilisation

1. Ouvre la page, choisis une taille de grille.
2. Remplis chaque case en cliquant dessus.
3. Clique **« Terminer le bingo »** pour verrouiller la grille.
4. Coche les cases en live pendant le stream.
5. Copie le lien **Embed** d'une grille et colle-le dans une source *Navigateur* OBS (coche *Fond transparent*) pour l'afficher en overlay, synchronisé en direct.

Guide détaillé : [Qu'est-ce qu'un Bingo Stream ?](https://jclouxdev.github.io/BingoStreamer/guide.html)

## Développement local

Aucune dépendance, aucun build. Sers le dossier avec n'importe quel serveur statique :

```bash
python3 -m http.server 8080
```

Puis ouvre `http://localhost:8080`.

## Déploiement

Le site est servi tel quel par GitHub Pages depuis la branche `main` (racine du repo) — aucune étape de build.

## Licence

[MIT](LICENSE) — libre d'utilisation, modification et redistribution, à condition de garder la mention de licence.

---

Si cet outil t'a servi, une ⭐ sur le repo aide d'autres streamers à le trouver.
