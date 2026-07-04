
#  TaskFlow - Landing Page

Application de gestion de tâches collaborative conçue pour aider les équipes à planifier, suivre et livrer leurs projets avec simplicité et efficacité.

## 📌 Description

TaskFlow est une landing page professionnelle pour une application web de gestion de tâches. Ce projet a été réalisé dans le cadre d'un exercice académique visant à maîtriser les concepts avancés de CSS3. La page présente un produit SaaS avec toutes les sections classiques d'une landing page moderne : présentation du produit, fonctionnalités, témoignages, plans tarifaires et appel à l'action. Le design est construit avec des variables CSS, des pseudo-classes et des sélecteurs combinateurs avancés.

## 🎯 Objectifs du projet

Maîtrise de la spécificité CSS et résolution des conflits de styles. Utilisation des sélecteurs combinateurs : adjacent, frères suivants, enfant direct. Application des pseudo-classes : nth-child, first-of-type, last-of-type, not, hover. Implémentation des pseudo-éléments : before, placeholder. Création et utilisation de variables CSS avec :root et var(). Compréhension de la cascade et de l'héritage en CSS. Mise en place d'un reset CSS personnalisé. Organisation et commentaires du code CSS par sections. Design professionnel cohérent sur l'ensemble de la page. Respect des normes d'accessibilité pour le contraste des couleurs. Utilisation de Flexbox et CSS Grid pour la mise en page. Gestion de projet avec Git et publication sur GitHub.

## 🛠️ Technologies utilisées

HTML5 pour la structure sémantique de la page. CSS3 pour les styles avancés, variables, animations, flexbox et grid. Google Fonts avec la police Poppins en graisses 300, 400, 600 et 700. Placehold.co pour les images de placeholder. Git pour la gestion de version. GitHub pour l'hébergement du code source.

##  Fonctionnalités

Barre de navigation fixe en haut de la page qui reste visible au scroll avec logo TaskFlow et liens vers les sections. Bouton Essai gratuit stylisé avec dégradé violet. Hero section avec grand titre accrocheur, texte descriptif, deux boutons d'action et image d'aperçu de l'application avec ombre et bords arrondis sur fond gris clair avec dégradé subtil. Section fonctionnalités en grille de 3 cartes avec icônes emoji, chaque carte ayant une bordure supérieure de couleur différente grâce à nth-child : violet pour la première, corail pour la deuxième, vert pour la troisième. Le titre de la première carte est violet via first-of-type. Effet de soulèvement au survol avec ombre. Section témoignages avec 3 cartes d'avis clients, photos rondes des auteurs, guillemet décoratif violet transparent avant chaque texte avec before, bordures gauches de couleurs différentes au survol via nth-child et hover, la dernière carte ayant une ombre plus prononcée grâce à last-of-type. Section pricing avec 3 plans tarifaires en FCFA : Starter gratuit, Pro à 9 900 FCFA par mois, Enterprise à 29 900 FCFA par mois. Le plan Pro est mis en avant visuellement avec une taille légèrement plus grande, une bordure violette, un badge Populaire au-dessus et un prix en couleur corail. Listes de fonctionnalités avec séparateurs entre chaque ligne. Effets de survol personnalisés par carte. Section CTA avec fond en dégradé violet, formulaire avec champ email et bouton blanc, texte blanc avec différentes opacités pour la hiérarchie visuelle et note rassurante sous le formulaire. Footer avec 4 colonnes en grille, la première étant plus large. Titres de colonnes en couleurs différentes : Produit en violet, Ressources en corail, Légal en vert. Liens avec alternance de clarté via nth-child odd et even, premier lien de chaque colonne en gras via first-of-type. Barre de copyright centrée en bas.

## 📂 Structure du projet

Le projet contient deux fichiers principaux. Le fichier index.html contient la structure HTML complète avec les 6 sections : navigation, hero, fonctionnalités, témoignages, pricing, CTA et footer. Le fichier style.css contient la feuille de styles CSS organisée en 17 sections commentées : reset CSS personnalisé, variables CSS avec :root, styles de base du body, container pour le centrage et la largeur max, titres de section communs, boutons en 3 variantes (primary, secondary, outline), navbar en position fixe, hero section, section fonctionnalités en grille CSS, pseudo-classes et combinateurs pour les features, section témoignages, pseudo-classes pour les témoignages, section pricing, pseudo-classes pour le pricing, section CTA, footer en grille de 4 colonnes, pseudo-classes pour le footer.

## ⚙️ Installation et utilisation

Le projet ne nécessite aucune dépendance, c'est un projet 100% statique. Il suffit d'un navigateur web comme Chrome, Firefox, Safari ou Edge. Pour utiliser le projet, cloner le repository avec git clone, naviguer dans le dossier avec cd taskflow-landing, puis ouvrir le fichier index.html en double-cliquant dessus ou via clic droit puis Ouvrir avec et choisir le navigateur. Le projet fonctionne directement sans aucune installation.

## 🚀 Commandes Git utilisées

git init pour initialiser Git dans le dossier. git add . pour ajouter tous les fichiers. git commit -m "Premier commit : Landing page TaskFlow complète" pour créer un commit. git remote add origin https://github.com/thomas-issoko/landing.git pour lier au repo GitHub distant. git push -u origin main pour envoyer le code sur GitHub.

## 👀 Aperçu du design

La palette de couleurs utilise un violet principal 6C63FF pour les boutons, le logo et les accents, un violet foncé 5A52D5 pour le survol des boutons, un corail FF6B6B pour les accents, le prix Pro et les titres du footer, un vert 4ECB71 pour les accents de succès, un gris clair F8F9FA pour les fonds de sections et un gris foncé 212529 pour le footer. La typographie utilise la police Poppins de Google Fonts en graisses 300 light, 400 regular, 600 semi-bold et 700 bold, avec des tailles allant de 0.75rem à 3rem via les variables CSS. La disposition est centrée avec une largeur maximale de 1100px, utilise CSS Grid en 3 colonnes pour les fonctionnalités, témoignages et pricing, et Flexbox pour la navbar, le hero et le footer. Le système d'espacements est cohérent grâce aux variables CSS allant de 0.5rem à 6rem. Les effets visuels incluent des ombres à 3 niveaux small, medium et large, des transitions fluides de 0.3s sur tous les éléments interactifs, des effets de soulèvement translateY au survol, des bordures arrondies cohérentes de 8px à 50px et un dégradé violet pour les éléments principaux.

## 🔧 Améliorations possibles

À court terme : ajouter un menu hamburger pour la navigation mobile, remplacer les images placeholder par de vraies captures d'écran, ajouter des animations au scroll avec AOS, implémenter un mode sombre avec les variables CSS, ajouter une favicon personnalisée. À moyen terme : rendre le formulaire CTA fonctionnel avec JavaScript, ajouter une section FAQ avec accordéon, créer des pages internes comme Blog et Documentation, optimiser pour le SEO avec les meta tags et Open Graph, ajouter un cookie banner pour la conformité RGPD. À long terme : intégrer un système de paiement comme Stripe ou PayPal, développer le back-end avec authentification, créer un dashboard utilisateur, mettre en place des tests automatisés, déployer sur Vercel ou Netlify.

## 👨‍💻 Auteur

Projet réalisé dans le cadre de la formation Akieni Academy Full Stack par ISSOKO Thomas.

## 📝 
Si ce projet t'a été utile, n'hésite pas à lui donner une étoile sur GitHub.
