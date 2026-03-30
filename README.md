# Drosophila-Dev
Site e-learning sur le développement embryonnaire de Drosophila melanogaster

## Description
Ce site présente le module "Aspects Génétiques du Développement Embryonnaire" pour les étudiants de L3 Biotechnologie à l'Université d'Oran 1.
Il est structuré pour ressembler à une plateforme LMS (type Moodle) afin de faciliter l'accès aux ressources.

## Structure du Site
- **index.html** : Page d'accueil et tableau de bord du cours.
- **courses.html** : Contenu pédagogique (Chapitres, PDF, Vidéos).
- **instructor.html** : Profile de l'enseignant (Dr Abdelkader ALLOUCHE).
- **contact.html** : Coordonnées et formulaire de contact.

## Instructions pour l'ajout de fichiers (PDF & MP4)

1.  **Créer un dossier `documents`** à la racine du projet pour y placer vos fichiers PDF.
2.  **Créer un dossier `videos`** à la racine du projet pour y placer vos fichiers MP4.
3.  **Mettre à jour les liens** dans `courses.html` et `index.html` pour pointer vers vos fichiers.

### Exemple d'intégration Vidéo (HTML5)
Dans `index.html` ou `courses.html`, remplacez le placeholder par :
```html
<video controls width="100%">
    <source src="videos/votre_fichier.mp4" type="video/mp4">
    Votre navigateur ne supporte pas la balise vidéo.
</video>
