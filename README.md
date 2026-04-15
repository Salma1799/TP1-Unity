# TP1 - Simulation Interactive et Collecte de Données
**Module** : Maquette Numérique  
**Filière** : ISIBD (Ingénierie des Systèmes d'Information et Big Data)  
**École** : ENSA Berrechid  

---

## 🎯 Objectif
Créer une simulation 3D interactive dans Unity 6 où un utilisateur 
se déplace dans un environnement, interagit avec des objets, 
et où ses actions sont enregistrées pour analyse.

---

## 🛠️ Technologies utilisées
- Unity 6 (6000.4.1f1)
- C#
- Visual Studio

---

## 📁 Structure du projet
- `PlayerMovement.cs` → Déplacement du joueur (clavier + souris)
- `ClickInteraction.cs` → Interaction avec les objets (clic + changement de couleur)
- `DataLogger.cs` → Enregistrement des données en CSV
- `SuivreJoueur.cs` → IA simple : sphère qui suit le joueur

---

## 🎮 Fonctionnalités
- Déplacement en vue première personne (ZQSD + souris)
- Clic sur les objets → changement de couleur aléatoire
- Enregistrement automatique : clics, positions, durée de session
- Sauvegarde des données dans `session_data.csv`
- Bonus : sphère qui suit automatiquement le joueur

---

## ▶️ Comment lancer
1. Ouvrir le projet dans Unity 6
2. Ouvrir la scène `SampleScene`
3. Appuyer sur **Play**
4. Se déplacer avec **ZQSD** et cliquer sur les objets

---

## 📊 Exemple de données collectées
```
temps,type,details
2.35,POSITION,x=0.50 y=1.00 z=-1.20
5.12,CLIC,Obstacle 1
8.23,CLIC,Obstacle 2
10.50,FIN_SESSION,total_clics=2
```
