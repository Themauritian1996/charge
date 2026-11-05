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

## Nouveautés 1.2

- **Pause pendant une séance** : le chrono, les rappels horaires, le repos et la mise en veille de l'écran sont suspendus ; la durée enregistrée exclut les pauses.
- **Calories estimées** (méthode MET, poids du profil) : par séance, sur 7 et 30 jours. La course, le vélo et la marche utilisent la vitesse réelle.
- **Difficulté de l'exercice** (1 à 5) après la dernière série : la prochaine fois, Charge propose d'augmenter ou d'alléger la charge, les reps ou le temps, et le coach IA en tient compte.
- **Onglet Progrès > Santé et repères** : IMC, masse grasse estimée, poids santé, rapport taille/tour de taille, métabolisme de base et besoin quotidien, FC max et zones cardio, VO2max estimé comparé à la moyenne de ton âge et de ton sexe, force relative comparée à des repères usuels, recommandations de l'OMS, suivi du poids.
- **Équilibre musculaire**, **trophées**, **calculateur de disques**.
