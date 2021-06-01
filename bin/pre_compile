#!/usr/bin/env bash
curl "https://annuaire.sante.fr/web/site-pro/extractions-publiques?p_p_id=abonnementportlet_WAR_Inscriptionportlet_INSTANCE_gGMT6fhOPMYV&p_p_lifecycle=2&p_p_state=normal&p_p_mode=view&p_p_cacheability=cacheLevelPage&_abonnementportlet_WAR_Inscriptionportlet_INSTANCE_gGMT6fhOPMYV_nomFichier=PS_LibreAcces_202105311652.zip" -o temp.zip
unzip temp.zip
mv PS_LibreAcces_Personne_activite_* annuaire.csv
rm PS_LibreAcces_*
rm temp.zip
