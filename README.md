# Login App Flutter

Une belle interface de connexion animée construite avec Flutter. Ce projet propose un écran de connexion moderne avec des animations fluides entre les vues de "connexion" et "création de compte", tout en suivant une structure modulaire pour une meilleure lisibilité et maintenance.

## 🌟 Fonctionnalités

- Interface utilisateur moderne et responsive
- Animation entre les écrans "Se connecter" et "S'inscrire"
- Effets de fond visuellement attractifs
- Champs de saisie personnalisés avec élévation et icônes
- Boutons sociaux Facebook et Google (images statiques)

## 📁 Structure du projet

```
lib/
├── App13/
│   ├── screens/
│   │   └── login_screen/
│   │       ├── login_screen.dart
│   │       ├── components/
│   │       │   ├── center_widget/
│   │       │   │   └── center_widget.dart
│   │       │   ├── login_content.dart
│   │       │   ├── top_text.dart
│   │       │   └── bottom_text.dart
│   ├── utils/
│   │   ├── constants.dart
│   │   └── helper_functions.dart
├── main.dart
```

## 🚀 Démarrage rapide

### Prérequis
- Flutter SDK
- Un éditeur comme VS Code ou Android Studio

### Installation
```bash
flutter pub get
flutter run
```

## 🔧 Personnalisation
- Couleurs personnalisées : dans `constants.dart`
- Animations : dans `change_screen_animation.dart`
- Champs : modifiables dans `login_content.dart`

## 📅 TODO
- Intégration Firebase pour authentification réelle
- Implémentation de validation de formulaire
- Gestion des erreurs utilisateur
- Ajout de navigation vers une page d'accueil après connexion

## 👨‍💼 Auteur
- Créé par [MOUTAWASSIT ABDELALI]



