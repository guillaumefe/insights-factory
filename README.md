# !nsight-Factory (Draft)

## Description
!nsight-Factory est un outil autonome (HTML/JS/CSS) permettant de construire, organiser et exporter des modèles structurés en JSON.  
Il sert à définir des processus, leurs sections, et les champs associés, puis à générer un modèle propre, réutilisable et partageable.

L’application fonctionne entièrement en local, sans serveur.

---

## Fonctionnalités
- Création, duplication, édition et suppression de processus
- Gestion des sections : ajout, suppression, réorganisation (drag & drop)
- Gestion des champs : texte, textarea, nombre, date, checkbox, radio, select, fichier
- Groupes de champs imbriqués (avec répétabilité et options avancées)
- Champs obligatoires / répétables
- Icône + astuce (tips) avec liens cliquables
- Réorganisation des éléments par glisser-déposer (section, champ, groupe)
- Aperçu JSON en temps réel
- Export du modèle en **JSON chiffré (AES-GCM)**
- Copie du JSON en clair (avec avertissement explicite)
- Import d’un JSON (clair ou chiffré)
- Génération d’un mini-schéma UML (ZIP)
- Sauvegarde automatique locale (localStorage)
- Interface responsive

---

## Utilisation
1. Ouvrir `insight-factory.html` dans un navigateur moderne (Chrome/Edge recommandés)
2. Créer un processus et ses sections
3. Ajouter et organiser les champs (ou groupes de champs)
4. Prévisualiser le modèle JSON
5. Exporter (ou importer) selon les besoins
---

## Stockage & sécurité
- Stockage local automatique dans `localStorage`
- Export sécurisé possible via **AES-GCM (WebCrypto)**
- Le JSON en clair peut être copié, mais l’application avertit l’utilisateur
- Aucune donnée n’est transmise en ligne

---

Code à refactorer complètement.
