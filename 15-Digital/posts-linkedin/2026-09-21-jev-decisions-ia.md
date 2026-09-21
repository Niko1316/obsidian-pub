---
linkedin_id: urn:li:share:7507772503608475648
format: texte
date_publication:
statut: publie
sujet: JEV, ou pourquoi on ne réveille plus un employé numérique pour un oui ou un non
canal: linkedin
---

8 160 exécutions. C'est le nombre de fois où nos outils ont réveillé un employé numérique complet, en 2026, pour répondre à une question qui n'avait que deux réponses possibles : oui ou non.

Un employé numérique, ça sert à raisonner, rédiger, décider. Pas à trancher un oui ou un non toutes les deux minutes.

C'est exactement pour ça qu'on a installé JEV.

Ce que c'est : un service de décisions typées. On lui donne un état (un message, une fiche, un journal d'exécution) et des questions courtes. Il rend des réponses typées et des probabilités, que le code lit directement.

Trois primitives, mélangeables dans un seul appel et évaluées en parallèle :

1. Noul : une question fermée, avec la probabilité du oui. « Ce message est-il un refus ? »
2. Choice : un choix entre plusieurs options, classées avec leur probabilité.
3. Score : une note sur une échelle, avec sa légende.

Mesuré ce matin, sur un vrai message client, trois questions dans la même requête : 655 ms, 414 jetons, refus à 0,82, objection budget à 0,83, demande de rappel à 0,97.

Et voilà le point que je trouve le plus important.

Le chiffre n'est pas la décision. 0,82 ne veut pas dire « plutôt oui ». C'est le code qui fixe le seuil, noir sur blanc : au-dessus de 0,8 c'est oui, en dessous c'est non. Une probabilité n'est pas un verdict, c'est une mesure.

Deuxième règle : une question floue donne une réponse floue. Quand une décision demande de peser plusieurs critères, on la découpe en questions séparées et on combine les résultats dans le code. Le jour où une priorité change, on modifie un coefficient, pas un prompt.

Ce qu'on lui confie aujourd'hui :

- trier les messages entrants : refus, objection sur le prix, demande de rappel
- classer un millier de fiches prospects en quelques familles
- répondre à « une commande attend-elle d'être déployée ? » sans lever un employé numérique pour ça

Ce que JEV ne fait pas : il n'écrit rien. Il ne remplace pas le modèle principal. C'est un aiguillage, pas un rédacteur.

La règle qu'on s'est donnée : une question qui revient des milliers de fois ne mérite pas un run de modèle complet. L'intelligence, on la garde là où elle se voit. Le reste, c'est du seuil.

Combien de décisions, dans votre entreprise, sont des seuils déguisés en réflexion ?

#IA #Automatisation #Productivite #EmployeNumerique #PME #Digital-VPartners
