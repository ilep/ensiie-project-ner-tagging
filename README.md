# nlp-ner-tagging


Code en python

- Objectif 1: Lire les données
- Objectif 2: Essayer d'extraire le loyer, par règles simples(regex, ...)
- Objectif 3: Construire un classifieur qui predit pour chaque mot sa category ( LOYER HC (hors charges), LOYER CC (charges comprises), CHARGES_COPROPRIETE, SURFACE, VILLE, LOCALISATION (quartier, rue,...), NOMBRE_PIECES, NOMBRE_CHAMBRES, ANNEE_CONSTRUCTION, TYPE_LOCATION (nue/meublée), TYPE_CHAUFFAGE, AVEC_PARKINg, AVEC_CAVE)



ENTITIES
--------

* M2: surface en m2 
* N_PIECES : nombre de pièces 
* N_CHAMBRES: nombre de chambres
* VILLE:    
* QUARTIER: nom du quartier
* ADRESSE: nom du la rue (avec le numero si indiqué)
* TRANSPORTS_PROXIMITE: transports à proximité
* ANNEE_CONSTRUCTION: annee de construction de l'immeuble
* CODE_POSTAL: code postal (92130) 
* LOYER_CC: montant du loyer charges comprises
* LOYER_HC: montant du loyer hors charges
* CHARGES_LOCATAIRE_MOIS: montant des charges mensuelles
* DEPOT_GARANTIE: montant du depot de garantie
* N_ETAGE:numero etage
* AVEC_ASCENSEUR: 
* DATE_DISPO:
* TYPE_CHAUFFAGE: individuel /collectif
* TYPE_LOCATION: meublé ou non meublé
* PARKING :
* EXTERIEUR : présence d'un jardin/balcon/terrasse
* COPROPRIETE :
* HONORAIRE : montant des honoraires de l'agence
* STOCKAGE : présence d'une cave/box ou autre élément de stockage



Articles NER tagging
------

https://towardsdatascience.com/named-entity-recognition-and-classification-with-scikit-learn-f05372f07ba2

Bi-LSTM + CRF <br/>
https://medium.com/@rohit.sharma_7010/a-complete-tutorial-for-named-entity-recognition-and-extraction-in-natural-language-processing-71322b6fb090

CRF
-------

http://pages.cs.wisc.edu/~jerryzhu/cs838/CRF.pdf

https://homepages.inf.ed.ac.uk/csutton/publications/crftut-fnt.pdf

https://www.seas.upenn.edu/~strctlrn/bib/PDF/crf.pdf

https://people.cs.umass.edu/~mccallum/papers/crf-tutorial.pdf


Liens intéressants
------

https://allennlp.org/

https://github.com/EthicalML/awesome-production-machine-learning/blob/master/README.md#function-as-a-service-frameworks

https://github.com/keon/awesome-nlp
