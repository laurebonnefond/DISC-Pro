# 🎯 DISC Pro — Test de personnalité & compatibilité professionnelle

Suite d'outils DISC interactifs, gratuits et open source, conçus pour le monde professionnel : management, coaching, santé au travail, formation.

🌐 **[Accéder aux outils en ligne](https://laurebonnefond.github.io/DISC-Pro/)**

---

## 🛠️ Les outils

### 🎯 Test de profil DISC
Questionnaire de 24 mises en situation comportementales pour identifier ton profil dominant et secondaire.

- 24 questions, 4 options par question (une par dimension D-I-S-C)
- Options présentées en ordre aléatoire pour réduire les biais
- Graphe radar interactif
- Analyse détaillée : forces, limites, environnement idéal, style de communication, comportement sous stress
- **Export Word personnalisé** (prénom + date)

### 🤝 Dynamiques d'équipe
Analyse des interactions entre 2 à 8 personnes en tenant compte du profil composite (dominant + secondaire).

- Saisie du profil dominant **et** secondaire pour chaque personne
- 10 combinaisons de binômes analysées (D↔D, D↔I, D↔S, D↔C, I↔I, I↔S, I↔C, S↔S, S↔C, C↔C)
- Nuances liées aux couleurs secondaires (impact sur la dynamique de base)
- Vue d'ensemble de l'équipe avec diagnostic (profils manquants, surreprésentés, compensés)
- Jauge de compatibilité, forces, risques, conseils concrets par binôme
- **Export Word complet** avec grille de communication

---

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

La prise en compte de la couleur secondaire s'appuie sur la méthodologie des *8 dimensions du leadership* (Sugerman et al., 2011) qui positionne chaque individu entre deux dimensions adjacentes du modèle DISC.

---

## ⚠️ Avertissement

Ces outils sont des **supports pédagogiques d'auto-évaluation**. Ils ne se substituent pas à un profil DISC certifié administré par un praticien formé (Wiley, Thomas International, TTI Success Insights). Pour un usage en recrutement, bilan de compétences ou diagnostic organisationnel, un questionnaire normatif validé psychométriquement est recommandé.

---

## 🚀 Déploiement

Trois fichiers HTML statiques, aucune dépendance, aucun framework, aucun serveur.

```
DISC-Pro/
├── index.html         ← Page d'accueil
├── test-disc.html     ← Test de profil DISC (24 questions)
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
