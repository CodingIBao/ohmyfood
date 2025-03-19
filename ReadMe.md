OhMyFood 🍽️

OhMyFood est un site web mobile-first qui permet aux utilisateurs de découvrir des restaurants gastronomiques et de précommander leurs repas avant leur arrivée au restaurant.

🚀 Technologies utilisées :
HTML5
SASS (SCSS)
CSS3
Git & GitHub

🎯 Objectifs du projet :
✔️ Développer un site mobile-first
✔️ Intégrer les maquettes fournies en HTML & SASS
✔️ Ajouter des animations CSS pour enrichir l’expérience utilisateur
✔️ Proposer une navigation fluide entre les restaurants

📌 Fonctionnalités :
Affichage des menus de 4 restaurants partenaires
Possibilité de composer son menu à l’avance
Design responsive pour une adaptation sur tous les écrans
Animations CSS pour un rendu dynamique

📜 Licence :
Projet réalisé dans le cadre de la formation OpenClassrooms.

--------------- 📥 Installation du projet --------------

1️⃣ Cloner le dépôt :

- Pour récupérer le projet, ouvrez un terminal et exécutez :
  git clone https://github.com/CodingIBao/ohmyfood.git

- Ensuite, placez-vous dans le dossier du projet :
  cd ohmyfood

2️⃣ Installer les dépendances :
Avant de lancer le projet, installez les dépendances nécessaires avec :

npm install
💡 Cette commande installe Sass et toutes les bibliothèques définies dans package.json.

🎨 Utilisation de Sass :

- Le projet utilise Sass pour générer les styles CSS.
- Un script est disponible pour compiler Sass automatiquement.

🔄 Lancer la compilation automatique de Sass

- Pour surveiller les fichiers .scss et générer le CSS en temps réel, utilisez :

npm run sass
✅ Cette commande garde Sass actif et met à jour le CSS à chaque modification.

🔥 Commandes utiles

Commande Description :

npm install Installe les dépendances du projet
npm run sass Compile Sass et surveille les modifications en continu

---

🛠️ Prérequis techniques
Node.js version >=18.0.0 est recommandé.

Vérifiez votre version avec :
node -v

npm (inclus avec Node.js) est requis pour installer les dépendances.
Vérifiez votre version avec :

npm -v

---

📌 Structure du projet
perl

ohmyfood/
├── assets/
│ ├── css/ # Fichiers CSS générés par Sass
│ ├── images/ # Images du projet
│ ├── fonts/ # Polices du projet
│
├── sass/ # Fichiers Sass (.scss)
│ ├──
| ├── base
| | ├── \_reset.scss
| | ├── \_variables.scss
| | ├── \_mixins.scss
│ ├── layout
| | ├── \_header.scss
| | ├── \_footer.scss
│ ├── pages
| | ├── \_a_la_francaise.scss
| | ├── \_le_delice_des_sens.scss
│ ├── main.scss # Fichier principal
│
├── .gitignore # Fichiers à ignorer (node_modules, etc.)
├── package.json # Configuration du projet + scripts npm
├── package-lock.json # Verrouille les versions des dépendances
├── index.html # Page principale

📝 Auteur
👤 CodingIBao

✅ Tout est prêt ! 🎉
Vous pouvez maintenant modifier et améliorer OhMyFood ! 🚀
