---
date_publication: 2026-11-10
heure_publication: 10:00 (Paris)
format: texte
statut: a-valider
sujet: Un courriel parti en votre nom, sans vous
pilier: cyber
canal: linkedin_page
---

Un fournisseur reçoit un courriel de votre comptable. L'adresse est la vôtre, la signature est la vôtre, le ton est juste. Il demande un changement de coordonnées bancaires. Ce courriel n'a pas été écrit chez vous.

Rien n'a été piraté, personne n'est entré dans votre messagerie. Il a suffi que votre domaine laisse faire.

Trois réglages publics décident de ce qui peut partir en votre nom : SPF, DKIM, DMARC. Les deux premiers disent quels serveurs ont le droit d'envoyer pour vous. Le troisième dit à la messagerie du destinataire quoi faire quand le message ne concorde pas : laisser passer, mettre en quarantaine, refuser.

Sans ces réglages, un inconnu écrit à vos clients et à votre banque avec votre nom dans le champ expéditeur. La personne qui reçoit ne consulte pas un enregistrement DNS avant de payer une facture. Elle reconnaît une adresse.

Le dégât ne tombe pas sur vous d'abord, mais sur celui qui a fait confiance à votre nom.

Trois vérifications, une demi-heure, sans rien installer.

1. Regardez votre zone DNS publique. Un enregistrement SPF existe-t-il, et se termine-t-il par une règle stricte ou par un « tout accepter » ?

2. Cherchez un enregistrement DMARC. S'il est absent, aucune consigne n'est donnée aux messageries, et l'usurpation se résume à copier votre adresse.

3. Faites le test à l'envers. Envoyez-vous un courriel depuis une adresse qui imite la vôtre, sans accès à votre messagerie. Ce que votre boîte en fait renseigne sur ce que les autres en font.

Ces réglages se lisent depuis l'extérieur, sans toucher à vos systèmes. C'est le point de départ de notre contrôle d'exposition : ce qu'un inconnu voit de votre domaine. Gratuit, sans engagement : digital-vpartners.com

#Cybersécurité #PME #UsurpationDeDomaine #Phishing #Digital-VPartners

## Visuel
2026-11-10-courriel-parti-en-votre-nom-sans-vous-visuel.png
