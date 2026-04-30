# Standards des Badges de Certification | Lorein Labs

Ce document définit les standards visuels utilisés pour certifier la qualité, la conformité et l'état des simulations au sein de l'écosystème Lorein Labs.

## 🎯 Objectifs des Badges
Les badges servent de **sceaux de validation**. Ils permettent aux partenaires et experts métiers de vérifier en un coup d'œil :
1. La **méthodologie** appliquée.
2. L'**état de succès** des simulations automatisées.
3. La **disponibilité** de la documentation de preuve.

## 🛠️ Bibliothèque des Badges Officiels

### 1. Label de Gouvernance
Indique que le dépôt respecte les standards définis dans `Lorein-Labs/.github`.
- **Code :**
```markdown
![Standard](https://shields.io)
```

### 2. État de la Simulation (Dynamique)
Reflète le résultat en temps réel des derniers workflows d'exécution.
- **Code :** *(Remplacez les variables par le nom de l'organisation et du dépôt)*
```markdown
![Simulation](https://github.com)
```

### 3. Certification de Qualité
Atteste que les tests de sécurité et de robustesse ont été validés.
- **Code :**
```markdown
![Quality](https://shields.io)
```

### 4. Documentation Technique
Lien direct vers les spécifications et rapports de preuves.
- **Code :**
```markdown
![Docs](https://shields.io)
```

## 📋 Règles d'Usage et Insertion

### Où les placer ?
Les badges doivent être insérés **immédiatement sous le titre principal (#)** du fichier `README.md` de chaque dépôt, séparés par un espace.

### Alignement
Pour une présentation professionnelle, ils doivent rester sur une seule ligne.

### Exemple de structure de README :
```markdown
# Projet de Simulation de Flux Bancaire
![Standard](...) ![Simulation](...) ![Quality](...)

## Description
Ce projet valide les hypothèses de...
```

## 🎨 Guide des Couleurs
- **Bleu (#007bff) :** Gouvernance et Standards.
- **Vert (#28a745) :** Succès, Certification, Validation.
- **Orange (#fd7e14) :** Documentation, Livrables, Information.
- **Rouge (#dc3545) :** Alerte, Échec de simulation (géré automatiquement par GitHub Actions).

---
*Lorein Labs - L'image de la rigueur par la standardisation visuelle.*
