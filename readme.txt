=== pixelsbretzels ===

Contributors: automattic
Tags: custom-background, custom-logo, custom-menu, featured-images, threaded-comments, translation-ready

Requires at least: 4.5
Tested up to: 4.8
Stable tag: 1.0.0
License: GNU General Public License v2 or later
License URI: LICENSE

A starter theme called pixelsbretzels.

== Workflow Git ==

- je me positionne sur develop (git checkout develop)
- Je créer une branch basée sur develop (git branch feature/project-init)
- Je me positionne sur cette nouvelle branch (git checkout feature/project-init)
- Je fais les modifications, concernant l’initialisation technique (ajout des fichiers de base, ajout de la structure de fichier scss, ajout des dossiers d’aoutput des styles et de js)
- Je commit et pousse sur le repo (git commit -m"J'ai cassé internet" && push)
- Une fois que j’ai poussé toutes mes modifs, je récupère le lien de PR que retourne la console et je complète le descriptif de cette PR (je fais attention à la branch de destination qui doit rester develop pour l’instant), puis j’ajoute toute l’équipe en reviewer pour obtenir au moins une à deux validations des co-équipiers.
Une fois les malidations obtenues, je merge la branch dans develop :
- Je me positionne sur develop: git checkout develop
- Je merge la branche : git merge feature/project-init
- Je supprime la branche git branch -d feature/project (on oublie pas de vérifier avant si les changements sont visibles sur le site :clin_d'œil: )
- On pousse sur le repo la version à jour de develop (git push)
- J’ouvre une :bière: et je fête ce nouvel ajout de qualité
----
Une bonne resource : https://www.atlassian.com/git/tutorials/syncing (modifié) 


== Credits ==

* Based on Underscores https://underscores.me/, (C) 2012-2017 Automattic, Inc., [GPLv2 or later](https://www.gnu.org/licenses/gpl-2.0.html)
* normalize.css https://necolas.github.io/normalize.css/, (C) 2012-2016 Nicolas Gallagher and Jonathan Neal, [MIT](https://opensource.org/licenses/MIT)
