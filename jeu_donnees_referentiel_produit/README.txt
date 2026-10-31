JEU DE DONNEES SYNTHETIQUE — REFERENTIEL PRODUIT

Les trois premières sources simulent des applications distinctes :
1. PIM : catalogue et identité produit.
2. ERP : articles et informations commerciales.
3. Marketplace : offres publiées par les vendeurs.

Le quatrième fichier contient des correspondances de référence (vérité terrain indicative)
pour évaluer le matching PIM/ERP. Gardez-le de côté pendant la détection.

Données fictives, non issues d'Amazon.
Anomalies incluses : valeurs manquantes, doublons, variations de casse et d'espaces,
catégories divergentes, codes-barres incorrects/manquants, dates impossibles,
prix et stocks négatifs. Les GTIN sont fictifs et non garantis conformes GS1.

Pistes : profiling, filtres LIKE/ILIKE, normalisation, matching exact et fuzzy,
complétude, unicité, validité, cohérence inter-sources, intégrité référentielle,
construction d'un produit maître et d'une table de correspondance des identifiants.
