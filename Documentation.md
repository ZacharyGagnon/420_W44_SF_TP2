# Documantation 
## Question theorique :

- Les outil DevOpps sont très utile pour faciliter la compréhension entre les différentes équipe d'un même projet puisque tout est visuel et facile a comprendre. Les outils permettent aussi de créer plusieurs instances d'une même application pour permettre au développeurs d'ajouter des nouvelle fonction sans risque de détruire les programes de production. De plus même si ont voulais pousser des changements il faut l'approbation de quelqu'un d'autre. Donc tout le monde est capable de comprendre ou ont est rendu et qu'es qui faut faire et si tout est bien fait la plupart des chose ce font tout automatiquement. Ce qui reduit le risuqe des erreurs humaines.
- nous utilison le modele PaaS pour notre situation puisque le cout du service IaaS sera plus cher vue que notre entreprise n'a aucune ressource physique il faudrait avoir beaucoup de VM ce qui coute plus cher que d'avoir qu'un service de BD et d'application web. De plus, gere des VM serait plus compliquer ce qui augmenterais le cout en terme de main d'oeuvre.

## Utilisation pipeline (facon manuel) :

1. aller sur l'onglet pipeline et clicquer
2. dans l'onglet piepline aller sur l'onglet release
3. clicquer sur le pipeline Developpement
4. clicquer sur "Create release" en bleu
5. ensuite mettre un commentaire et clicquer sur create
6. recliquer sur l'onglet release pour voir votre release en cours 
8. si vous etes un approbateur attendre que le premier stage finnisse et approuver le deuxieme

*noter que le pipeline "Release 1 Developpement" ce declanche automatiquement lorsque la branche develop change et meme chose pour "Release 2 Production" mais pour la branche main

## Repartition des Tache :
- Toute le travaille -> Zachary Gagnon
