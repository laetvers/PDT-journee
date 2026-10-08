# Générateur de plans — V1

Application statique destinée à Cloudflare Pages.

Elle analyse un plan collé, détecte Leçon / Modelage / Entraînement / Tâche complexe, récupère les fichiers `.md` correspondants dans `Sephi-Chan/progression`, puis génère PDF enseignant, PDF élèves et PowerPoint.

Les évaluations et corrections sont exclues du PDF élèves.

Important : si un fichier ne possède pas de section dédiée `## Tâche complexe` (comme le COMP2 fourni), l'application le signale et ne remplace pas arbitrairement cette section par `À toi de jouer`.

Déploiement Cloudflare Pages : build command `exit 0`, output directory `/`.
