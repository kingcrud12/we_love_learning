# 🎨 Design System : LearnHub (Plateforme de Formation)

## 1. Vision & Principes
Le design system doit être **clair, accessible et engageant**, centré sur l'expérience d'apprentissage. Fini les thèmes foncés omniprésents, on s'oriente vers une interface lumineuse, aérée et motivante.
- **Clarté avant tout :** L'interface met en valeur le contenu pédagogique grâce à des espaces blancs généreux.
- **Moderne et Professionnel :** Utilisation de couleurs vibrantes pour contraster avec une base neutre et sérieuse.
- **Lisibilité :** Des typographies fortes et des contrastes optimisés pour une lecture prolongée.
- **Identité de marque :** Un logo sous forme de livre ouvert avec la typographie "LearnHub", associé à une couleur violette identifiable et mémorable.

## 2. Palette de Couleurs
Une palette dominée par un violet dynamique, équilibré par des tons neutres sombres et clairs.

* **Couleur Primaire (Marque & Accentuation) :** Violet Vibrant (`#7C3AED` ou similaire) — Utilisé pour le logo, les text-links actifs, et les bannières d'en-tête monumentales (ex: Accueil, Tableau de bord).
* **Couleur d'Action (Interactions Principales) :** Noir profond / Bleu Nuit (`#0F172A`) — Utilisé pour les boutons d'appel à l'action principaux (ex: "Continuer", "Détails du cours"). Cela crée un contraste très élégant avec la légèreté du reste de la page.
* **Neutres (Texte & Fonds) :**
  - Fond de base principal : Blanc (`#FFFFFF`) pour maximiser la clarté.
  - Fond secondaire (champs de recherche, fond de page derrière les cartes, blocs modaux) : Gris très clair (`#F9FAFB` ou `#F3F4F6`).
  - Texte principal et gros titres : Noir / Gris très foncé (`#111827`).
  - Texte secondaire (descriptions, durées, paragraphes explicatifs) : Gris moyen (`#6B7280`).
  - Bordures discrètes des cartes : Gris clair (`#E5E7EB`).
* **Sémantique (Badges & Tags) :**
  - Succès / Cours Terminé / Tendance : Vert menthe/émeraude (`#10B981`) pour le badge ou l'icône de validation.
  - Attention / Information / Bestseller : Jaune ambre (`#F59E0B`).
  - Catégories de cours (Développement, Design) : Violet ou Bleu pastel (ex : fond `#E0E7FF` avec texte `#4338CA`) pour une intégration très douce.

## 3. Typographie
Une typographie structurée avec des graisses très marquées pour la hiérarchie.

* **Titres (Headings) :** Typographie sans-serif propre et percutante (ex: `Inter` ou `Roboto`).
  - *Weights:* Bold (700) ou Extra-Bold (800) pour les gros titres de bannières Hero et les titres de sections (ex: "Tableau de bord").
* **Corps de texte (Body) :** `Inter` ou similaire.
  - *Weights:* Regular (400), Medium (500) pour les boutons, labels de menus, et badges.
  - Très bonne lisibilité sans empattement.

## 4. Grille & Espacements
Design espacé, avec une structure en cartes "flottantes".

* **Border Radiuses :**
  - Boutons et Champs de recherche : Faiblement arrondis (`6px` ou `8px`), pour une pointe de sérieux.
  - Cartes de cours, blocs statistiques de progression : Coins plus arrondis (`12px` ou `16px`).
  - Badges de catégorie et tags ("En cours", "Bestseller") : Arrondis intégraux en forme de pilule (`9999px`).

## 5. Composants UI (Core Components)

### 5.1 Boutons
- **Primary :** Fond Noir/Bleu Nuit avec texte en blanc. Utilisé pour les actions franches sur les cartes de cours ("Continuer", "Détails du cours").
- **Secondary (Outline) :** Fond transparent, fine bordure de la couleur principale de texte (Noir ou Violet), texte foncé. Utilisé pour les actions contextuelles ("Devenir instructeur").
- **Onglets (Tabs) / Pill Buttons :** Des boutons ronds avec fond Gris très clair (texte noir) devenant fond blanc au survol, très subtils (ex: les filtres "Tous", "Plus populaire").

### 5.2 Cartes de Cours & Blocs Stats
- **Fond :** Blanc ou très subtilement texturé.
- **Bordure :** Liseré gris très clair (1px solid `#E5E7EB`), sans ombre lourde, ou `box-shadow` ultra-douce (`0 1px 3px rgba(0,0,0,0.05)`).
- **Structure de Carte de Cours :**
  - Section supérieure : Image de couverture / Thumbnail avec coins arrondis en haut. Badges superposés dans les coins (ex: "Bestseller", "Tendance").
  - Corps : Tags de catégorie / niveau d'abord, puis Titre imposant, Auteur en gris, puis icône + info "Dernière leçon".
  - Pied de carte : Pourcentage de cours terminé, barre de progression visuelle (fond gris pâle, jauge Noire/Bleue Nuit), et estimation du temps restant, ou alors les boutons d'action d'affilée.

### 5.3 En-têtes, Navbar et Bannières "Hero"
- **Navbar :** Fond blanc, logo à gauche (Bleu/Violet pour l'icône, typographie noire), liens de navigation discrets en bleu secondaire/violet s'ils sont actifs, champ de recherche large et gris très clair au centre, et actions utilisateur à droite (Panier, Profil).
- **Hero Banners (Bannières hautes) :** S'affichant en pleine largeur. Soit un Violet éclatant en bloc opaque (ex: page Tableau de bord) contrastant magnifiquement avec les cartes blanches superposées, soit un design divisé (texte à gauche, image d'ambiance de l'apprentissage à droite).

## 6. Iconographie
- Ligne fine, simple, et non remplie (`outline`) pour les menus et métadonnées (Livre ouvert, coche de validation, chronomètre, trophée, graphique de progression).
- Taille constante et alignement parfait avec le texte environnant.

## 7. Recherche et Filtrage
- Champs de recherche textuelle combinés avec des sélecteurs (Select boxes) très propres : fond gris (`#F9FAFB`), bordure discrète, flèche `chevron-down`. Séparation nette des critères de tri.
