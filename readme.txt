#QuickSwap Editor Pro

**QuickSwap Editor Pro** est une extension Chrome puissante conçue pour les designers, copywriters et développeurs. Elle permet de transformer n'importe quel site web en un éditeur visuel instantané. D'un simple clic droit, vous pouvez modifier l'intégralité d'un bloc de contenu (Image, Titre, Description et Bouton) via une interface élégante.



## ✨ Fonctionnalités
- **Édition de bloc intelligente** : Identifie automatiquement les images, les titres (`.title-wrapper`), les descriptions (`.content-wrapper`) et les boutons dans un même composant.
- **Interface Moderne (UI)** : Un panneau d'édition élégant avec flou d'arrière-plan (backdrop-filter) injecté directement sur la page.
- **Support complet** : Fonctionne sur les balises `<img>`, les textes, les boutons et même les fonds CSS.
- **Zéro Latence** : Les modifications sont appliquées instantanément au DOM sans rechargement.

## 🚀 Installation (Mode Développeur)

1. **Téléchargez** ce dépôt en tant que fichier ZIP.
2. **Extrayez** les fichiers dans un dossier.
3. Ouvrez Google Chrome et accédez à `chrome://extensions/`.
4. Activez le **Mode développeur** (en haut à droite).
5. Cliquez sur **Charger l'extension décompressée** et sélectionnez votre dossier.

## 🛠️ Utilisation
1. Faites un **clic droit** sur n'importe quel élément d'un bloc (ex: une image de produit ou un bouton).
2. Sélectionnez **⚡ Modifier ce bloc (QuickSwap)**.
3. Modifiez les champs souhaités dans la fenêtre qui apparaît au centre de l'écran.
4. Cliquez sur **Appliquer les changements**.

## 📂 Structure du projet
- `manifest.json` : Configuration et permissions (v2.0).
- `background.js` : Gestion du menu contextuel.
- `content.js` : Logique d'injection de l'interface et manipulation du DOM.
- `icon.png` : Icône officielle de l'extension.

## 🔒 Confidentialité
QuickSwap Editor Pro respecte votre vie privée. L'extension ne collecte, ne stocke et ne transmet aucune donnée. Toutes les modifications sont effectuées localement dans votre navigateur et disparaissent au rafraîchissement de la page.

---
*Développé pour simplifier les tests de contenu et de design en temps réel.*