# 🎙️ Retranscription Automatique d'Audio avec Google Colab

## ⚠️ Important : Créez votre copie du script !

Pour utiliser le script, il faut cliquer sur le lien google colab.

**ATTENTION** : Avant de lancer le code, il faut créer une copie ! Si vous lancez directement sur la version de github, ça peut m'envoyer des données (vos adresses mails). Si vous faites une copie et que vous utilisez la copie, je n'aurai rien. DONC FAITES UNE COPIE DU SCRIPT (la méthode pour le faire directement sur le google colab). Après vous avez juste à retourner sur google drive et reprendre votre copie pour retranscrire d'autres entretiens.

## 📝 Guide étape par étape

### 1️⃣ Accéder et copier le script
1. Cliquez sur le lien Google Colab ci-dessus
2. Une fois sur Google Colab, cliquez sur `Fichier` en haut à gauche
3. Sélectionnez `Enregistrer une copie dans Drive`
4. Le script est maintenant copié dans votre Google Drive

### 2️⃣ Préparer l'environnement
1. Ouvrez votre copie du script depuis Google Drive
2. En haut à droite, vérifiez que le type d'exécution est sur "GPU" :
   - Cliquez sur `Runtime` (ou `Exécution`)
   - Sélectionnez `Change runtime type` (ou `Modifier le type d'environnement d'exécution`)
   - Choisissez `GPU` dans le menu déroulant
   - Cliquez sur `Save`

### 3️⃣ Utiliser le script
1. Exécutez les cellules dans l'ordre (cliquez sur le bouton ▶️ à gauche de chaque cellule)
2. Attendez que chaque cellule finisse de s'exécuter avant de passer à la suivante
3. Une interface apparaîtra avec :
   - Un menu pour choisir la qualité de transcription
   - Un bouton pour charger votre fichier audio
   - Une zone où la transcription apparaîtra en temps réel

### 4️⃣ Transcription
1. Choisissez la qualité de transcription :
   - `Rapide` : Pour des tests rapides
   - `Standard` : Bon pour la plupart des cas
   - `Haute qualité` : Meilleure précision
   - `Très haute qualité` : Excellente précision
   - `Qualité maximale` : La meilleure qualité possible (mais plus lent)

2. Cliquez sur `Choisir un fichier audio` et sélectionnez votre fichier


https://github.com/user-attachments/assets/7ace09cf-c49b-46bf-a10f-4899db49eea0


   
3. La transcription commencera automatiquement :
   - Vous verrez le texte apparaître progressivement
   - À la fin, le fichier texte sera automatiquement téléchargé

## 📌 Conseils
- Pour de meilleurs résultats, utilisez des enregistrements clairs avec peu de bruit de fond
- Pour les fichiers importants, utilisez la qualité "Très haute qualité" ou "Qualité maximale"
- Le fichier texte final sera automatiquement téléchargé sur votre ordinateur
- Vous pouvez transcrire plusieurs fichiers à la suite sans avoir à recharger la page

## ❓ Problèmes fréquents

1. **"GPU non détecté"** :
   - Retournez dans `Runtime` > `Change runtime type`
   - Vérifiez que `GPU` est bien sélectionné
   - Cliquez sur `Save` et réessayez

2. **"Erreur lors de l'installation"** :
   - Réexécutez la cellule d'installation
   - Si l'erreur persiste, actualisez la page et recommencez

3. **"Le fichier n'est pas supporté"** :
   - Vérifiez que votre fichier est bien au format audio (MP3, WAV, M4A...)
   - Essayez de le convertir en MP3 avant l'upload

## 💾 Réutiliser le script
Pour retranscrire d'autres fichiers plus tard :
1. Allez dans votre Google Drive
2. Retrouvez votre copie du script
3. Ouvrez-la et recommencez à l'étape 2
ATTENTION : Google limite l'utilisation à 4h / jour. Après 4h, cela va continuer mais en prenant les perfomances de votre ordiateur (ce qui va prendre beaucoup plus de temps).

## 🔒 Confidentialité
- En utilisant votre propre copie, vos données restent privées


THOMAS Louis 
M2 Sociologie recherche
Université de Tours

Avec l'aide de THOMAS Guylain (pas mon frère même si même nom de famille).
Master ingénieur logiciel
Epitech Nantes
