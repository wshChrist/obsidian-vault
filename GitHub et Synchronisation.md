# GitHub & Synchronisation

Mon setup de synchronisation pour l'Obsidian et mes projets.

---

## Repository Obsidian

**URL :** https://github.com/wshChrist/obsidian-vault  
**Compte :** wshChrist  
**Branche principale :** main

### Contenu synchronisé
- Tout mon vault Obsidian (D:\Obsidian)
- Notes personnelles
- Dossiers : Projets, Journal, Échecs et Leçons, Ressources, Rêves
- Calendrier `.ics`
- Configuration Obsidian

### Git configuré
- **Nom :** Christ (206)
- **Email :** wshChrist@users.noreply.github.com
- `.gitignore` configuré pour exclure les fichiers temporaires

---

## Calendrier iPhone

**Lien d'abonnement :** https://raw.githubusercontent.com/wshChrist/obsidian-vault/main/206-calendar.ics

### Comment l'ajouter sur iPhone

**Méthode 1 — Safari :**
1. Ouvrir le lien dans Safari sur iPhone
2. Appuyer sur "S'abonner"

**Méthode 2 — Réglages :**
1. Réglages → Calendrier → Comptes
2. Ajouter un compte → Autre
3. Ajouter un abonnement à un calendrier
4. Coller le lien

### Contenu du calendrier
- Weekly Reviews (chaque dimanche 20h)
- Milestones [[Rendr]]
- Monthly Reviews (1er de chaque mois)

Le calendrier se met à jour automatiquement quand je modifie le fichier sur GitHub.

---

## Commandes Git utiles

### Synchroniser depuis PC portable
```bash
git clone https://github.com/wshChrist/obsidian-vault.git
```

### Pousser des modifications
```bash
cd D:/Obsidian
git add .
git commit -m "Description"
git push
```

### Récupérer les mises à jour
```bash
cd D:/Obsidian
git pull
```

---

**Retour :** [[Organisation et Productivité]]
