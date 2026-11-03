# Charge

Carnet d'entraînement : séances, plans, calendrier, progression et partage.

Le fichier `Charge.apk` est construit automatiquement par GitHub Actions à chaque mise à jour,
puis publié dans l'onglet **Releases** du dépôt.

- `www/` : l'application (HTML autonome, fonctionne hors ligne)
- `assets/` : icône et écran de démarrage
- `signing/debug.keystore` : clé de signature fixe, pour que les mises à jour s'installent par-dessus l'app sans perdre les données

## Nouveautés 1.1

- **Notification chaque heure de séance** : après 1 h d'entraînement, puis toutes les heures (réglable dans Réglages).
- **Coach IA (Gemini)** : onglet « Coach IA » depuis l'accueil. La clé Gemini (gratuite sur aistudio.google.com/apikey) est saisie dans l'app et reste sur l'appareil, jamais dans ce dépôt.
  - Briefing avant chaque plan : check-in (énergie, sommeil, courbatures, temps), cibles du jour ajustées, échauffement, conseils.
  - Workout sur mesure : type (musculation, HIIT, mixte, circuit, course, intervalles, Tabata, EMOM/AMRAP…), difficulté, durée, zone ciblée, matériel.
  - Profil et objectifs, bilan de progression, programme de la semaine, analyse d'une séance, questions libres.
- **Minuteur d'intervalles** avec bips et vibrations (Tabata, HIIT, EMOM, sprints).
