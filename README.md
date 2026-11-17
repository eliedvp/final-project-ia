# VibeTunes - Lecteur Musical

Une application web moderne pour découvrir et écouter de la musique via l'API Deezer.

L'application tient dans un seul fichier `index.html` (HTML, CSS et JavaScript intégrés, sans dépendance à installer).

## 🎵 Fonctionnalités

- **Recherche musicale** : Trouvez des artistes et genres (ex: BOOBA, pop, rock)
- **Lecteur audio** : Interface complète avec contrôles play/pause/suivant
- **Barre de progression** : Navigation interactive avec clic pour avancer/reculer
- **Affichage des pistes** : Galerie des meilleurs titres avec couvertures d'album
- **Mode démo** : Pistes d'exemple intégrées au code (extraits SoundHelix) en cas de problème d'API
- **Contrôles clavier** : 
  - Espace : Play/Pause
  - Flèche droite : Piste suivante
  - Flèche gauche : Piste précédente
- **Interface responsive** : Adapté aux mobiles et desktop

## 🚀 Installation et utilisation

1. **Ouvrir l'application** :
   ```bash
   # Méthode 1 : Double-cliquez simplement sur index.html
   # Méthode 2 : Utilisez un serveur HTTP local :
   # Avec Node.js : npx http-server
   # Avec PHP : php -S localhost:8000
   # Avec Live Server (extension VSCode)
   # Puis ouvrez http://localhost:8000
   ```

2. **Utilisation basique** :
   - Tapez un artiste ou genre dans la barre de recherche
   - Cliquez sur "Rechercher" ou appuyez sur Entrée
   - Utilisez les boutons de contrôle ou les touches clavier

## 🛠️ Technologies utilisées

- **HTML5** : Structure de l'application
- **CSS3** : Design moderne avec variables CSS et dégradés
- **JavaScript ES6+** : Logique applicative et interactions
- **API Deezer** : Source des données musicales
- **Élément HTML `<audio>`** : Lecture des extraits audio

## 🔧 Configuration API

L'application utilise plusieurs stratégies pour contourner les limitations CORS :

1. **Fetch direct** vers l'API Deezer
2. **Proxy AllOrigins** en cas d'échec
3. **JSONP** comme fallback historique
4. **Pistes d'exemple intégrées** en dernier recours

## 🎨 Design

- **Thème sombre** avec dégradés bleu/rose
- **Variables CSS** pour une maintenance facile
- **Design responsive** adaptatif
- **Animations subtiles** pour l'expérience utilisateur

## 🧪 Tests intégrés

L'application inclut des tests automatisés :
- Vérification du filtrage des pistes
- Test des données d'exemple
- Validation des fonctions helper

Cliquez sur "Lancer auto-tests" pour exécuter les tests.

## 📱 Compatibilité

- **Navigateurs modernes** : Chrome, Firefox, Safari, Edge
- **Mobile** : Interface adaptée aux écrans tactiles
- **Desktop** : Contrôles clavier optimisés

## 🐛 Problèmes connus

- **CORS** : L'API Deezer peut bloquer les requêtes directes
- **Prévisualisations** : Certaines pistes peuvent manquer d'extraits audio
- **Connectivité** : Requiert une connexion internet pour l'API Deezer

## 💡 Fonctionnalités futures potentielles

- [ ] Liste de lecture personnalisée
- [ ] Favoris et historiques
- [ ] Mode hors ligne
- [ ] Partage social
- [ ] Égaliseur audio
- [ ] Thèmes personnalisables

## 📄 Licence

Projet éducatif - Utilisation libre pour l'apprentissage

## 🤝 Contribution

Les contributions sont les bienvenues ! N'hésitez pas à :
- Signaler des bugs
- Proposer des améliorations
- Ajouter de nouvelles fonctionnalités

---

**Développé avec ❤️ pour les amateurs de musique**
