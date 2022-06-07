# base-de-donnee
Voici les differentes requêtes

INSERT INTO locations.Films(titre,durée, datesortie,realisateur) values('titre_Film','durée_Films','datesortie_Films',Réalisateur_Films)

UPDATE locations.Films SET=nom_de_la_column_concerne='valeur_de_modification' WHERE id=id_de_la column_concerne

DROP locations.Films 'letitre_film'@'localhost'

INSERT INTO locations.client(first_name,last_name,email) values('Prénom_Client','Nom_Client','Email_Client')

UPDATE locations.Client SET=nom_de_la_column_concerne='valeur_de_modification' WHERE id=id_de_la_column_concerne

DROP LOCATIONS.Client 'Nom_Client'@'localhost'

SELECT*FROM locations.Films ORDER BY id DESC LIMIT 3
