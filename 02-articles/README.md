# 02 Articles

Articles de blog et contenus éditoriaux.

- [[02-articles/article-bitcoin-linkedin-blog.md]]
- [[02-articles/cybersecurite-reflexes-apres-piratage-dgfip.md]]
- [[02-articles/ia-generative-pme-par-ou-commencer.md]]
- [[02-articles/seo-2026-moteurs-reponse-ia.md]]
- [[02-articles/zero-click-2026-le-clic-n-est-plus-la-mesure.md]]
- [[02-articles/automatiser-prospection-sans-perdre-humain.md]] : article blog Digital-V proposé à El Jeffe le 16/09/2026, texte à valider (statut `brouillon`), mécanique de prospection automatique séparant les tâches déléguables de la relation, sans chiffre non sourcé.

## Role
Brouillons et articles edites du blog Digital-V, avant ou apres publication.

## Conventions
- Frontmatter obligatoire : `date`, `url`, `statut` (`brouillon`, `valide`, `publie`). Le champ `statut` est lu par `pub_sync.py` : sans lui, l'article n'entre jamais dans la table Publications NocoDB.
- Un article par fichier, nomme par son slug (`<slug>.md`). Le slug sert d'identifiant de publication et de deduplication.
- Regles de redaction : zero tiret cadratin, zero chiffre non source, aucune coordonnee en clair, meta description de 80 a 160 caracteres.
- La decision de publication se lit dans NocoDB, pas dans le chat : la note porte l'etat, pas la decision.

## Ce qui ne va PAS dans ce dossier
- Un post LinkedIn : `15-Digital/posts-linkedin` (profil) ou `15-Digital/posts-linkedin-page` (page)
- Un article d'une autre marque : le dossier de la marque
- De la matiere brute de recherche : [[01-recherches/README]]
- Un article d'un autre blog ou site client : dossier du client
