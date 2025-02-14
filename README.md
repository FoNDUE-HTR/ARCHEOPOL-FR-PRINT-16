# ARCHEOPOL-FR-PRINT-16

![characters badge](badges/characters.svg) ![regions badge](badges/regions.svg) ![lines badge](badges/lines.svg) ![files badge](badges/files.svg)

This repo contains the transcription of 16th c. prints.

## Content

|------------------|----------------------|----------|----------|-----------|--------------|---------------|
| Author           | Title                | Date     | Location | Publisher | Segmentation | Transcription |
|------------------|----------------------|----------|----------|-----------|--------------|---------------|
| Hotman, François | [_La Gaule françoise_](https://doi.org/10.3931/e-rara-14920) | 1574     | Geneva   | Le Preux  | L. Paoli     | L. Paoli      |



## How to cite

Cf. [`htr-united.yml`](https://github.com/FoNDUE-HTR/ARCHEOPOL-FR-PRINT-16/blob/main/htr-united.yml) file.

## Licences
Annotation is CC-BY. Images belong to the digital libraries the come from.

<a rel="license" href="https://creativecommons.org/licenses/by/2.0"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/2.0/88x31.png" /></a><br />


## OLD STUFF to clean
Contributeurs

    Nicolas Champeaux
    Alyzé Bianco
    Lorenzo Paoli

Ce dossier fait partie du projet FNS Archéo-POL de l'IHR et est disponible sur le GitHub officiel.
Présentation

Ce dépôt contient un répertoire appelé dataset_corpus_principal, qui regroupe plusieurs livres anciens numérisés et segmentés en pages. Chaque page est associée à une image (.jpg ou .png) et à un fichier de transcription XML (le cas échéant). Certains livres sont entièrement ou partiellement transcrits, d’autres ne le sont pas.
Contenu du dossier

Le dossier dataset_corpus_principal contient les sous-dossiers suivants :

    de_la_puissance_legitime
        Segmenté en pages.
        Non transcrit.
        Pour chaque page :
            un fichier image (.jpg ou .png),
            un fichier .xml vide ou non complété.

    du_droit_des_magistrats
        Segmenté en pages.
        Non transcrit.
        Pour chaque page :
            un fichier image (.jpg ou .png),
            un fichier .xml vide ou non complété.

    la_gaule_francoise
        Segmenté en pages.
        Transcrit (fichiers XML complets ou partiels).
        Pour chaque page :
            un fichier image (.jpg ou .png),
            un fichier .xml contenant la transcription.

    le_reveille_matin(part.1)
        Segmenté en pages.
        Non transcrit.
        Pour chaque page :
            un fichier image (.jpg ou .png),
            un fichier .xml vide ou non complété.

    le_reveille_matin(part.2)
        Segmenté en pages.
        Non transcrit.
        Pour chaque page :
            un fichier image (.jpg ou .png),
            un fichier .xml vide ou non complété.

    question_politique(berne)
        Segmenté en pages.
        Transcrit (fichiers XML complets ou partiels).
        Pour chaque page :
            un fichier image (.jpg ou .png),
            un fichier .xml contenant la transcription.

    question_politique(s.l.)
        Segmenté en pages.
        Transcrit (fichiers XML complets ou partiels).
        Pour chaque page :
            un fichier image (.jpg ou .png),
            un fichier .xml contenant la transcription.

Structure des dossiers

Chaque sous-dossier (correspondant à un ouvrage) suit à peu près la structure suivante :

dataset_corpus_principal/
└── [nom_du_livre]/
    ├── page_001.jpg (ou .png)
    ├── page_001.xml
    ├── page_002.jpg (ou .png)
    ├── page_002.xml
    ├── ...
    └── page_nnn.jpg (ou .png)
    └── page_nnn.xml

    Les fichiers d’images (.jpg ou .png) correspondent à la numérisation d’une page.
    Les fichiers .xml contiennent (ou devraient contenir) la transcription ou les métadonnées de la page correspondante.

Statut des transcriptions

    Non transcrit : Les fichiers .xml sont vides ou ne contiennent pas de texte transcrit.
    Partiellement ou totalement transcrit : Les fichiers .xml incluent la transcription (totale ou partielle) du texte de la page.

Ainsi :

    de_la_puissance_legitime, du_droit_des_magistrats, le_reveille_matin(part.1) et le_reveille_matin(part.2) sont segmentés en pages mais ne sont pas transcrits.
    la_gaule_francoise, question_politique(berne) et question_politique(s.l.) ont des fichiers XML transcrits, au moins partiellement.

Utilisation

Ces données sont destinées à l’entraînement d’un nouveau modèle de segmentation et servent à :

    Développer, entraîner et évaluer des algorithmes de segmentation des pages et des lignes de texte.
    Expérimenter avec des méthodes d’apprentissage automatique ou d’apprentissage profond pour la segmentation d’images de documents historiques français de la fin du XVIe siècle.

Contribuer

Vous ne pouvez pas contribuer !

Lorsque vous citez ou utilisez ces données dans vos travaux, veuillez inclure :

    Le lien vers le dépôt GitHub : https://github.com/ARCHEO-POL
    Le nom du projet : Archéo-POL
    Les noms des contributeurs : Nicolas Champeaux, Alyzé Bianco, Lorenzo Paoli
    La date d’accès (ou la version du commit si pertinent)

Droits

Licence Creative Commons
This work is licensed under a Creative Commons Attribution 4.0 International Licence.
    
