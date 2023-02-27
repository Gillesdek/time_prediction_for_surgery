Schema de données

table h
i	: id intervention
d	: duree en s
specialite : specialite de l'intervention	
sous_specialite	: categorie d'acte prevu
acte_prevu : acte prevu (noté dans le planning avant l'intervention)

table acte 
i	: id intervention
ccam_code : codes des actes réalisés pendant l'intervention

table ccam
hiérarchie de la classification CCAM