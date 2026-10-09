# 🎯 DISC Pro — Test de personnalité & compatibilité professionnelle

Suite d'outils DISC interactifs, gratuits et open source, conçus pour le monde professionnel : management, coaching, santé au travail, formation.

🌐 **[Accéder aux outils en ligne](https://laurebonnefond.github.io/DISC-Pro/)**

---

## 🧩 Le modèle

| Dimension | Ce qu'elle décrit | Pôles |
|---|---|---|
| **Moteur** (couleur) | Pourquoi la personne agit | 🔴 Raisonnement · 🟡 Idéal · 🟢 Harmonie · 🔵 Pragmatisme |
| Loupe / Satellite | Comment elle recueille l'information | 🔍 Détail, concret, présent · 🛰️ Vision, liens, futur |
| Tête / Cœur | Comment elle décide | 🧠 Logique · ❤️ Valeurs et impact humain |
| Interne / Externe | Comment elle se ressource et échange | 🔋 Réfléchit avant de parler · 💬 Réfléchit en parlant |
| Rond / Carré | Son rapport à la structure | ⭕ Flexibilité · ⬛ Planification |
| **Carrosserie** (ascendant) | Comment le moteur se voit | Pilotage (Rouge) · Aventure (Jaune) · Adaptabilité (Vert) · Prudence (Bleu) |
| Sous stress | Fonctionnement réactionnel, calculé à part | Bascule vers l'opposé : Rouge ↔ Vert, Jaune ↔ Bleu |

Moteur = Loupe/Satellite × Tête/Cœur : Raisonnement = Satellite + Tête, Idéal = Satellite + Cœur, Harmonie = Loupe + Cœur, Pragmatisme = Loupe + Tête.
Carrosserie = Interne/Externe × Rond/Carré. Lecture du profil : « Jaune ascendant Vert » = moteur Idéal + carrosserie Adaptabilité.

## 🛠️ Les outils

### 🎯 Test de profil (`test-disc.html`)
Questionnaire en 7 étapes (59 écrans, ~12 min) : 16 situations moteur, 8 Loupe/Satellite, 8 Tête/Cœur, 8 Interne/Externe, 8 Rond/Carré, intelligences multiples, valeurs, puis 8 situations de stress aigu.

Résultats :
- Schéma de construction du profil et portrait rédigé
- 9 situations de travail : ce qui se joue à l'intérieur (moteur) / ce que l'entourage voit (carrosserie)
- **Profil miroir** : comparaison avec le profil inversé (ex. Jaune ascendant Vert ≠ Vert ascendant Jaune) et clés pour les distinguer
- Fiche personnelle, interactions avec chaque moteur et chaque carrosserie (exemples concrets), bascule sous stress
- Code profil (`Prénom:J-V-In-Ro-B`) et rapport Word

### 🤝 Dynamiques d'équipe (`dynamiques.html`)
- Import du code profil ou saisie manuelle (moteur, carrosserie, couleur sous stress)
- Par binôme : compatibilité / complémentarité / synergie, dynamique des moteurs et des carrosseries, perception mutuelle, réactions comparées dans les mêmes situations, malentendus, dynamique sous stress, stratégie commune
- Détection des profils miroirs et des « ponts naturels »
- Cartographie d'équipe, 7 risques collectifs, synthèse d'expert, export Word

## 📚 Fondements scientifiques

Le modèle DISC repose sur les travaux du psychologue **William Moulton Marston** (*Emotions of Normal People*, 1928), qui identifie quatre dimensions comportementales fondamentales. Les instruments d'évaluation modernes ont été développés par **John G. Geier, Ph.D.** (Université du Minnesota, années 1970).

### Sources de référence

| Auteur | Ouvrage | Année |
|--------|---------|-------|
| Marston, W. M. | *Emotions of Normal People* | 1928 |
| Clarke, W. V. | *Activity Vector Analysis* | 1956 |
| Geier, J. G. | *Personal Profile System* | 1979 |
| Scullard, M. & Baum, D. | *Everything DiSC Manual* (Wiley) | 2015 |
| Sugerman, J. et al. | *The 8 Dimensions of Leadership* | 2011 |
| Bonnstetter, B. J. & Suiter, J. I. | *The Universal Language DISC* (TTI) | 2013 |
| Rohm, R. A. | *Positive Personality Profiles* | 2013 |

### Approche « profil composite »

Le moteur s'appuie sur les fonctions de Jung (1921) et leurs combinaisons ST, SF, NF, NT (Myers & McCaulley, 1985). La correspondance couleurs ↔ Jung et les couleurs opposées viennent d'Insights Discovery. Les couleurs des carrosseries suivent les styles observables du DISC (Marston, 1928 ; Geier, 1979).

---

## ⚠️ Avertissement

**Niveaux de preuve.** DISC : modèle descriptif largement utilisé. Jung : théorie des types ; la correspondance couleurs ↔ Jung et les couleurs opposées proviennent d'Insights Discovery. Intelligences multiples (Gardner) : modèle pédagogique peu étayé empiriquement. Valeurs (inspiré de Demartini), préférences motrices et signatures posturales : sans validation scientifique, affichées à titre réflexif et jamais intégrées au calcul du profil.

Les dimensions Interne/Externe, Rond/Carré et les indices corporels proviennent d'un modèle de formation complémentaire, non validé psychométriquement. Les indices corporels ne modifient jamais les scores.


Ces outils sont des **supports pédagogiques d'auto-évaluation**. Ils ne se substituent pas à un profil DISC certifié administré par un praticien formé (Wiley, Thomas International, TTI Success Insights). Pour un usage en recrutement, bilan de compétences ou diagnostic organisationnel, un questionnaire normatif validé psychométriquement est recommandé.

---

## 🚀 Déploiement

Trois fichiers HTML statiques, aucune dépendance, aucun framework, aucun serveur.

```
DISC-Pro/
├── index.html         ← Page d'accueil
├── test-disc.html     ← Test de profil (moteur, carrosserie, stress)
├── dynamiques.html    ← Dynamiques d'équipe (2-8 personnes)
└── README.md
```

Hébergé via [GitHub Pages](https://pages.github.com/) — fonctionne aussi en local (ouvrir `index.html` dans un navigateur).

---

## 🎯 Cas d'usage

- **Management** — Adapter son leadership au profil de chaque collaborateur
- **Santé au travail** — Comprendre les dynamiques dans les diagnostics RPS
- **Formation** — Adapter la pédagogie au profil des apprenants
- **Coaching** — Identifier forces et axes de développement
- **Team building** — Constituer des équipes complémentaires

---

## 🧰 Stack technique

- HTML / CSS / JavaScript vanilla
- Zéro dépendance, zéro framework, zéro build
- Police : [DM Sans](https://fonts.google.com/specimen/DM+Sans) (Google Fonts)
- Export Word : génération HTML → Blob `.doc` côté client
- Graphe radar : Canvas 2D natif

---

## 👩‍⚕️ Auteur

**Laure Bonnefond** — Infirmière en santé au travail & préventrice des risques professionnels

Projet développé dans le cadre de [PréventIA-LaB](https://laurebonnefond.github.io/PreventIA-LaB/), suite d'outils IA au service de la prévention et de la santé au travail.

---

## 📄 Licence

Usage libre à des fins pédagogiques et professionnelles. Mention de la source appréciée.
