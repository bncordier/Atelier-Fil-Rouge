# Atelier-Fil-Rouge / Challenge

![](https://media.giphy.com/media/ukMiDlCmdv2og/giphy.gif)

Développement d'une API Rest

Voici les fonctionnalités auxquelles ton API devra répondre :

    GET - Récupération de l'ensemble des données de ta table
    GET (light) - Récupération de quelques champs spécifiques (id, names, dates, etc...)

    GET - Récupération d'un ensemble de données en fonction de certains filtres :
        Un filtre "contient ..." (ex: nom contenant la chaîne de caractère 'wcs')
        Un filtre "commence par ..." (ex: nom commençant par 'campus')
        Un filtre "supérieur à ..." (ex: date supérieure à 18/10/2010)

        Une route par type de filtre

    GET - Récupération de données ordonnées (ascendant, descendant)

        L'ordre sera passé en tant que paramètre de la route

    POST - Sauvegarde d'une nouvelle entité
    PUT - Modification d'une entité
    PUT - Toggle du booléen
    DELETE - Suppression d'une entité
    DELETE - Suppression de toutes les entités dont le booléen est false
