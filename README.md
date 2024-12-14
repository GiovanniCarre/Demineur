# 🎮 Jeu de Démineur - Giovanni CARRÉ

## 🎯 Objectif  
Reproduire le jeu du **Démineur** de manière simple dans le cadre d'une **Game-Jam**.  

---

## 🚀 Technologies Utilisées  
- **Java 8**  
- **Swing** (pour l'interface graphique)  

---

## 📝 Résumé du Projet  

Le projet **"Jeu de Démineur"** est une implémentation du célèbre jeu de démineur, utilisant le langage de programmation **Java** et la bibliothèque graphique **Swing**.  
Ce jeu permet aux joueurs de tester leur logique en **évitant les mines** tout en découvrant les cases de la grille.

---

## 🛠️ Fonctionnalités Implémentées  

1. **Interface Graphique Swing**  
   - Une interface utilisateur simple et efficace grâce à la bibliothèque **Swing**.  

2. **Génération Aléatoire des Mines**  
   - Les mines sont placées **aléatoirement** sur la grille.  
   - La première case cliquée est toujours **sécurisée** (aucune mine).  

3. **Découverte des Cases**  
   - En cliquant sur une case :  
     - Si c'est une **mine**, la partie se termine.  
     - Sinon, le nombre de **mines adjacentes** est révélé.  

4. **Gestion de la Fin de Jeu**  
   - Le jeu se termine lorsque :  
     - Le joueur clique sur une **mine**.  
     - Toutes les cases **non minées** ont été découvertes.  
   - Une **fenêtre de dialogue** annonce le résultat et propose de rejouer.  

---

## 🔮 Prochaines Étapes  

Des améliorations possibles pour étendre et améliorer le projet :  

1. **Amélioration de l'Interface Utilisateur**  
   - Rendre l'interface plus conviviale et moderne.  

2. **Mode Difficile**  
   - Ajouter un mode de jeu avec une **densité plus élevée** de mines.  

3. **Multijoueur**  
   - Permettre de jouer en **réseau** contre d'autres joueurs.  

4. **Système de Classement**  
   - Ajouter un classement en ligne pour **comparer les scores**.  

---

## 📂 Structure du Projet  

```plaintext
Démineur/
│
├── src/                        # Code source du projet
├── config.txt                  # Fichier de configuration (paramètres)
├── présentation.pdf            # Présentation détaillée du projet
├── README.md                   # Documentation (ce fichier)
└── demineur.jar                # Exécutable du projet

▶️ Lancement du Projet
✅ Prérequis

    Java 8 (ou version supérieure) doit être installé sur votre machine.
    Vérifiez l'installation avec :

java -version

🚀 Exécution du Programme

    Exécuter le fichier JAR :
    Ouvrez un terminal ou invite de commandes et lancez :

    java -jar demineur.jar

    Contrôles du Jeu :
        🖱️ Clic gauche : Mettre un mur.
        🖱️ Clic droit : Enlever un mur.
        Z : Dessiner le tracé du chemin le plus court.
        E : Enlever le tracé.

📄 Présentation

Pour plus d'informations sur le projet et son implémentation, consultez le fichier présentation.pdf.
🎉 Conclusion

Le projet "Jeu de Démineur en Java avec Swing" est une implémentation réussie qui offre une expérience utilisateur agréable.
Il répond aux objectifs de la Game-Jam tout en laissant la porte ouverte à des améliorations futures pour le rendre encore plus captivant.

👨‍💻 Auteur : Giovanni CARRÉ
📅 Projet Game-Jam
