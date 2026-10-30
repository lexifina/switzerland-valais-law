# Valais: law history in git

The law of the canton of Valais (Canton du Valais, Switzerland) as a git history: one file per article, one commit per amending act on the day it took effect, and the amending act as the commit's author. `git blame` names the act behind every paragraph; `git log` lists every change to an article; checking out a date gives the text in force that day.

It follows the shared design of [lexifina/global-law](https://github.com/lexifina/global-law), which places it at `ch-vs/`. The federal law is in [lexifina/switzerland-law](https://github.com/lexifina/switzerland-law).

The text is in French, the canton's first official language in the collection, exactly as the canton publishes it.

## What this repository holds

506 acts with 1085 versions so far: the cantonal constitution, the cantonal laws (Gesetze) in force and 339 ordonnances and règlements in force, in the order of the systematic collection, added in parts. Other decrees and decisions, intercantonal agreements and repealed acts are not included yet.

| Folder | Act | Versions | History |
| --- | --- | ---: | --- |
| `101-1-cst-cant/` | Constitution du canton du Valais (RS 101.1) | 4 | oldest version available, then each consolidated version: 1 April 2008 to 1 May 2023 |
| `111-1/` | Loi sur le sceau de la République (RS 111.1) | 1 | one version (the oldest available), 4 September 1802 |
| `111-010/` | Loi concernant la mise en œuvre de la réforme de la péréquation financière et de la répartition des tâches entre la Confédération, le canton et les communes (RS 111.010) | 1 | one version (the oldest available), 1 January 2012 |
| `112-1/` | Loi concernant les prestations à faire par la ville de Sion comme chef-lieu du canton (RS 112.1) | 1 | one version (the oldest available), 1 December 1882 |
| `141-1/` | Loi sur le droit de cité valaisan (RS 141.1) | 1 | one version (the oldest available), 1 January 2013 |
| `142-1-laletr/` | Loi d'application de la loi fédérale sur les étrangers (RS 142.1) | 1 | one version (the oldest available), 1 January 2016 |
| `142-3/` | Loi sur l'hébergement collectif des personnes relevant du droit d'asile (RS 142.3) | 1 | one version (the oldest available), 1 January 2016 |
| `151-1/` | Loi concernant l'application du principe d'égalité entre femmes et hommes (RS 151.1) | 1 | one version (the oldest available), 1 January 2011 |
| `160-1-lcdp/` | Loi sur les droits politiques (RS 160.1) | 4 | oldest version available, then each consolidated version: 9 April 2017 to 1 April 2023 |
| `160-3-laldp/` | Loi d'application de la loi fédérale sur les droits politiques (RS 160.3) | 2 | oldest version available, then each consolidated version: 1 March 2011 to 1 July 2018 |
| `160-5-li/` | Loi sur les incompatibilités (RS 160.5) | 4 | oldest version available, then each consolidated version: 1 July 2016 to 1 July 2023 |
| `170-1/` | Loi sur la responsabilité des collectivités publiques et de leurs agents (RS 170.1) | 1 | one version (the oldest available), 1 January 2011 |
| `170-2-lipda/` | Loi sur l'information du public, la protection des données et l'archivage (RS 170.2) | 2 | oldest version available, then each consolidated version: 1 September 2011 to 1 January 2024 |
| `170-3-lpartet/` | Loi sur les participations de l'Etat à des personnes morales et autres entités (RS 170.3) | 3 | oldest version available, then each consolidated version: 1 January 2012 to 1 January 2025 |
| `170-6-lma/` | Loi sur la médiation administrative (RS 170.6) | 1 | one version (the oldest available), 1 January 2024 |
| `170-7/` | Loi sur l'organisation de la cour chargée de statuer sur les conflits de compétence entre le pouvoir administratif et le pouvoir judiciaire (RS 170.7) | 1 | one version (the oldest available), 1 January 1992 |
| `170-8-lsna/` | Loi sur les services numériques des autorités (RS 170.8) | 1 | one version (the oldest available), 1 January 2025 |
| `171-1-locrp/` | Loi sur l'organisation des Conseils et les rapports entre les pouvoirs (RS 171.1) | 11 | oldest version available, then each consolidated version: 1 January 2015 to 1 September 2024 |
| `172-2-lcpers/` | Loi sur le personnel de l'Etat du Valais (RS 172.2) | 3 | oldest version available, then each consolidated version: 17 March 2017 to 1 May 2026 |
| `172-4/` | Loi fixant le traitement des employés de l'Etat du Valais (RS 172.4) | 3 | oldest version available, then each consolidated version: 1 July 2011 to 1 May 2026 |
| `172-6-lpja/` | Loi sur la procédure et la juridiction administratives (RS 172.6) | 4 | oldest version available, then each consolidated version: 1 April 2016 to 1 January 2025 |
| `172-8-lbdr/` | Loi sur les bases de données référentielles et sur l'harmonisation des registres des personnes, des entreprises et établissements ainsi que des bâtiments et logements (RS 172.8) | 1 | one version (the oldest available), 1 May 2020 |
| `172-10-lstat/` | Loi sur la statistique publique cantonale (RS 172.10) | 1 | one version (the oldest available), 1 January 2023 |
| `172-12/` | Loi concernant les traitements des magistrats de l'ordre exécutif (RS 172.12) | 2 | oldest version available, then each consolidated version: 1 January 2015 to 1 July 2020 |
| `172-13/` | Loi sur la prévoyance professionnelle des magistrats (RS 172.13) | 3 | oldest version available, then each consolidated version: 1 January 2015 to 1 January 2024 |
| `172-15/` | Loi sur l'organisation et les attributions des conseils de districts (RS 172.15) | 1 | one version (the oldest available), 23 December 1855 |
| `172-16/` | Loi sur les attributions des préfets (RS 172.16) | 1 | one version (the oldest available), 24 May 1850 |
| `172-51-lcpval/` | Loi régissant la Caisse de prévoyance du Canton du Valais (CPVAL) (RS 172.51) | 1 | one version (the oldest available), 1 January 2020 |
| `172-61/` | Loi supprimant une instance de recours administratif (RS 172.61) | 1 | one version (the oldest available), 15 March 1996 |
| `173-1-loj/` | Loi sur l'organisation de la Justice (RS 173.1) | 7 | oldest version available, then each consolidated version: 1 January 2013 to 1 January 2024 |
| `173-7-lcdm/` | Loi sur le Conseil de la magistrature (RS 173.7) | 4 | oldest version available, then each consolidated version: 1 September 2020 to 1 March 2026 |
| `173-8-ltar/` | Loi fixant le tarif des frais et dépens devant les autorités judiciaires ou administratives (RS 173.8) | 4 | oldest version available, then each consolidated version: 1 January 2018 to 1 January 2025 |
| `173-12/` | Loi concernant le traitement des autorités judiciaires et des représentants du ministère public (RS 173.12) | 2 | oldest version available, then each consolidated version: 1 January 2013 to 1 January 2024 |
| `175-1-lco/` | Loi sur les communes (RS 175.1) | 3 | oldest version available, then each consolidated version: 1 January 2012 to 1 January 2023 |
| `175-2/` | Loi sur les bourgeoisies (RS 175.2) | 1 | one version (the oldest available), 1 January 2008 |
| `175-101/` | Loi sur la fusion des communes municipales et bourgeoisiales de Sion et des Agettes (RS 175.101) | 1 | one version (the oldest available), 1 July 2016 |
| `175-102/` | Loi concernant la fusion des communes municipales de Baltschieder, Eggerberg et Viège (RS 175.102) | 1 | one version (the oldest available), 1 May 2026 |
| `176-1/` | Loi sur le contrôle de l'habitant (RS 176.1) | 2 | oldest version available, then each consolidated version: 1 March 2009 to 21 July 2023 |
| `177-1-loi-sur-la-profession-d-avocat-lpav/` | Loi sur la profession d'avocat pratiquant la représentation en justice (RS 177.1) | 5 | oldest version available, then each consolidated version: 1 March 2014 to 1 June 2024 |
| `177-7-laj/` | Loi sur l'assistance judiciaire (RS 177.7) | 1 | one version (the oldest available), 1 January 2011 |
| `178-1-ln/` | Loi sur le notariat (RS 178.1) | 3 | oldest version available, then each consolidated version: 1 March 2014 to 1 January 2024 |
| `180-1-lree/` | Loi sur les rapports entre les Eglises et l'Etat dans le canton du Valais (RS 180.1) | 1 | one version (the oldest available), 1 May 1996 |
| `211-1-lacc/` | Loi d'application du code civil suisse (RS 211.1) | 6 | oldest version available, then each consolidated version: 1 October 2016 to 1 January 2027 |
| `211-6/` | Loi sur la mensuration officielle (RS 211.6) | 1 | one version (the oldest available), 1 July 2016 |
| `211-7-lcgeo/` | Loi d'application de la loi fédérale sur la géoinformation (RS 211.7) | 1 | one version (the oldest available), 1 July 2016 |
| `211-15-lalpart/` | Loi d'application de la loi fédérale sur le partenariat enregistré (RS 211.15) | 1 | one version (the oldest available), 1 January 2007 |
| `211-41-lalfaie/` | Loi réglant l'application de la loi fédérale sur l'acquisition d'immeubles par des personnes à l'étranger (RS 211.41) | 1 | one version (the oldest available), 1 January 2011 |
| `211-412-laldfr/` | Loi concernant l'application du droit foncier rural (RS 211.412) | 1 | one version (the oldest available), 1 January 1996 |
| `221-21/` | Loi d'application de la loi fédérale sur le crédit à la consommation (RS 221.21) | 1 | one version (the oldest available), 1 July 2004 |
| `270-1-lacpc/` | Loi d'application du code de procédure civile suisse (RS 270.1) | 3 | oldest version available, then each consolidated version: 1 June 2014 to 1 January 2025 |
| `281-1-lalp/` | Loi d'application de la loi fédérale sur la poursuite pour dettes et la faillite (RS 281.1) | 3 | oldest version available, then each consolidated version: 1 September 2015 to 1 May 2020 |
| `311-1-lacp/` | Loi d'application du code pénal (RS 311.1) | 9 | oldest version available, then each consolidated version: 1 October 2016 to 1 October 2026 |
| `312-0-lacpp/` | Loi d'application du code de procédure pénale suisse (RS 312.0) | 6 | oldest version available, then each consolidated version: 1 January 2013 to 1 February 2026 |
| `312-1-ldpolj/` | Loi concernant les dossiers de police judiciaire (RS 312.1) | 3 | oldest version available, then each consolidated version: 1 January 2017 to 1 January 2024 |
| `312-2-lalao/` | Loi d'application de la loi sur les amendes d'ordre (RS 312.2) | 3 | oldest version available, then each consolidated version: 1 January 2020 to 1 November 2025 |
| `312-5-lalavi/` | Loi d'application de la loi fédérale sur l'aide aux victimes d'infractions (RS 312.5) | 2 | oldest version available, then each consolidated version: 1 January 2009 to 1 January 2024 |
| `314-1-ladpmin/` | Loi d'application de la loi fédérale régissant la condition pénale des mineurs (RS 314.1) | 3 | oldest version available, then each consolidated version: 1 January 2011 to 1 February 2026 |
| `314-2-lappmin/` | Loi d'application de la loi fédérale sur la procédure pénale applicable aux mineurs (RS 314.2) | 3 | oldest version available, then each consolidated version: 1 June 2014 to 1 February 2026 |
| `400-1-lip/` | Loi sur l'instruction publique (RS 400.1) | 3 | oldest version available, then each consolidated version: 1 August 2015 to 1 January 2026 |
| `400-2-lpso/` | Loi sur le personnel de la scolarité obligatoire et de l'enseignement secondaire du deuxième degré général et professionnel (RS 400.2) | 2 | oldest version available, then each consolidated version: 1 December 2016 to 1 January 2020 |
| `400-90/` | Loi sur la coordination scolaire (RS 400.90) | 1 | one version (the oldest available), 1 August 2015 |
| `405-1/` | Loi sur la contribution des communes au traitement du personnel de la scolarité obligatoire et aux charges d'exploitation des institutions spécialisées (RS 405.1) | 1 | one version (the oldest available), 1 January 2012 |
| `405-3-ltso/` | Loi sur le traitement du personnel de la scolarité obligatoire et de l'enseignement secondaire du deuxième degré général et professionnel (RS 405.3) | 4 | oldest version available, then each consolidated version: 1 January 2018 to 1 September 2024 |
| `411-0-lep/` | Loi sur l'enseignement primaire (RS 411.0) | 2 | oldest version available, then each consolidated version: 1 December 2016 to 1 August 2021 |
| `411-2-lco/` | Loi sur le cycle d'orientation (RS 411.2) | 2 | oldest version available, then each consolidated version: 1 December 2016 to 1 August 2021 |
| `411-3-les/` | Loi sur l'enseignement spécialisé (RS 411.3) | 1 | one version (the oldest available), 1 December 2016 |
| `412-1-lalfpr/` | Loi d'application de la loi fédérale sur la formation professionnelle (RS 412.1) | 2 | oldest version available, then each consolidated version: 1 January 2012 to 22 April 2022 |
| `412-5-lffp/` | Loi sur le fonds cantonal en faveur de la formation professionnelle (RS 412.5) | 2 | oldest version available, then each consolidated version: 1 January 2013 to 1 January 2021 |
| `413-10/` | Loi fixant la contribution des communes du siège des collèges et établissements cantonaux (RS 413.10) | 1 | one version (the oldest available), 1 January 2012 |
| `414-70/` | Loi sur la Haute Ecole Spécialisée de Suisse occidentale Valais/Wallis (RS 414.70) | 2 | oldest version available, then each consolidated version: 1 January 2015 to 1 January 2026 |
| `415-1/` | Loi sur le sport (RS 415.1) | 2 | oldest version available, then each consolidated version: 1 January 2018 to 1 January 2025 |
| `415-2/` | Loi réglant l'octroi de subventions cantonales pour la construction et l'agrandissement d'aménagements destinés à la gymnastique et au sport (RS 415.2) | 1 | one version (the oldest available), 1 May 1996 |
| `416-1-lbpe/` | Loi sur les bourses et prêts d'études (RS 416.1) | 2 | oldest version available, then each consolidated version: 8 June 2011 to 1 July 2021 |
| `417-03/` | Loi fixant le traitement du personnel des écoles de formation professionnelle supérieure (RS 417.03) | 2 | oldest version available, then each consolidated version: 1 January 2015 to 1 January 2020 |
| `417-4-lfca/` | Loi sur la formation continue des adultes (RS 417.4) | 3 | oldest version available, then each consolidated version: 1 July 2001 to 22 April 2022 |
| `417-10-lccs/` | Loi fixant la contribution des communes sièges aux institutions de formation et de recherche du degré tertiaire (RS 417.10) | 3 | oldest version available, then each consolidated version: 1 January 2015 to 1 January 2026 |
| `419-1-lhep/` | Loi concernant la Haute école pédagogique du Valais (RS 419.1) | 3 | oldest version available, then each consolidated version: 1 September 2012 to 1 January 2026 |
| `420-1-leher/` | Loi sur l’encouragement des hautes écoles et de la recherche (RS 420.1) | 2 | oldest version available, then each consolidated version: 1 July 2001 to 1 January 2026 |
| `440-1-lprc/` | Loi sur la promotion de la culture (RS 440.1) | 5 | oldest version available, then each consolidated version: 1 July 2018 to 1 September 2026 |
| `451-1-lcpn/` | Loi sur la protection de la nature, du paysage et des sites (RS 451.1) | 2 | oldest version available, then each consolidated version: 1 January 2016 to 1 January 2018 |
| `455-1-lalpa/` | Loi d'application de la loi fédérale sur la protection des animaux (RS 455.1) | 2 | oldest version available, then each consolidated version: 1 September 2015 to 1 January 2020 |
| `501-1-lppex/` | Loi sur la protection de la population et la gestion des situations particulières et extraordinaires (RS 501.1) | 2 | oldest version available, then each consolidated version: 1 January 2014 to 1 September 2019 |
| `502-1-lalarm/` | Loi d'application de la loi fédérale sur les armes, les accessoires d'armes et les munitions (RS 502.1) | 1 | one version (the oldest available), 1 November 1999 |
| `504-1-lalaam/` | Loi d'application de la loi fédérale sur l'armée et l'administration militaire (RS 504.1) | 1 | one version (the oldest available), 1 January 2011 |
| `520-1-lalpci/` | Loi d'application de la législation fédérale sur la protection civile (RS 520.1) | 3 | oldest version available, then each consolidated version: 1 January 2014 to 1 January 2025 |
| `520-3/` | Loi d'application de la loi fédérale sur la protection des biens culturels en cas de conflit armé (RS 520.3) | 1 | one version (the oldest available), 1 January 2006 |
| `540-1-lpien/` | Loi sur la protection contre l'incendie et les éléments naturels (RS 540.1) | 3 | oldest version available, then each consolidated version: 1 January 2018 to 1 January 2025 |
| `550-1-lpol/` | Loi sur la police cantonale (RS 550.1) | 8 | oldest version available, then each consolidated version: 1 January 2017 to 1 May 2026 |
| `550-6-lvd/` | Loi sur les violences domestiques (RS 550.6) | 3 | oldest version available, then each consolidated version: 1 January 2017 to 1 May 2026 |
| `611-1-lgcaf/` | Loi sur la gestion et le contrôle administratifs et financiers du canton (RS 611.1) | 7 | oldest version available, then each consolidated version: 1 January 2015 to 1 January 2024 |
| `612-1/` | Loi sur le frein aux dépenses et à l'endettement (RS 612.1) | 1 | one version (the oldest available), 1 January 2005 |
| `612-3-fonds-figi/` | Loi sur le Fonds de financement de l'investissement et de la gestion des immeubles de l'Etat (RS 612.3) | 1 | one version (the oldest available), 1 November 2018 |
| `612-5/` | Loi concernant le financement des grands projets d'infrastructures du 21e siècle (RS 612.5) | 1 | one version (the oldest available), 1 February 2012 |
| `612-7-lfinr3/` | Loi sur le financement de la 3e correction du Rhône (RS 612.7) | 1 | one version (the oldest available), 1 May 2019 |
| `613-1-lpfi/` | Loi sur la péréquation financière intercommunale (RS 613.1) | 1 | one version (the oldest available), 1 January 2012 |
| `616-1-lsub/` | Loi sur les subventions (RS 616.1) | 1 | one version (the oldest available), 1 January 2011 |
| `620-1-lbcvs/` | Loi sur la Banque cantonale du Valais (RS 620.1) | 1 | one version (the oldest available), 1 January 2018 |
| `641-5/` | Loi sur l'imposition des véhicules automobiles (RS 641.5) | 3 | oldest version available, then each consolidated version: 1 January 2018 to 1 January 2025 |
| `641-52/` | Loi sur l'imposition des bateaux (RS 641.52) | 1 | one version (the oldest available), 1 January 1996 |
| `642-1-lf/` | Loi fiscale (RS 642.1) | 8 | oldest version available, then each consolidated version: 1 January 2018 to 1 January 2028 |
| `643-1-ldm/` | Loi sur les droits de mutations (RS 643.1) | 1 | one version (the oldest available), 1 January 2013 |
| `658-1-lalifd/` | Loi d'application de la loi fédérale sur l'impôt fédéral direct (RS 658.1) | 2 | oldest version available, then each consolidated version: 12 October 2012 to 1 January 2024 |
| `660-1-lalteo/` | Loi d'application de la loi fédérale sur la taxe d'exemption de l'obligation de servir (RS 660.1) | 4 | oldest version available, then each consolidated version: 1 January 2004 to 1 July 2026 |
| `701-1-lcat/` | Loi d'application de la loi fédérale sur l'aménagement du territoire (RS 701.1) | 4 | oldest version available, then each consolidated version: 1 January 2015 to 10 September 2026 |
| `701-2/` | Loi concernant le remembrement et la rectification de limites (RS 701.2) | 1 | one version (the oldest available), 1 July 2007 |
| `701-6-loi-sur-les-contributions-des-propietaires-fonciers/` | Loi concernant la perception des contributions de propriétaires fonciers aux frais d'équipements et aux frais d'autres ouvrages publics (RS 701.6) | 2 | oldest version available, then each consolidated version: 1 January 1989 to 1 May 2019 |
| `702-1-lalrs/` | Loi d'application de la loi fédérale sur les résidences secondaires (RS 702.1) | 1 | one version (the oldest available), 1 February 2021 |
| `704-1-liml/` | Loi sur les itinéraires de mobilité de loisirs (RS 704.1) | 2 | oldest version available, then each consolidated version: 1 January 2012 to 1 January 2023 |
| `705-1-lc/` | Loi sur les constructions (RS 705.1) | 6 | oldest version available, then each consolidated version: 9 October 2015 to 1 January 2026 |
| `710-1-lcex/` | Loi sur les expropriations (RS 710.1) | 1 | one version (the oldest available), 1 January 2010 |
| `721-1-ldnace/` | Loi sur les dangers naturels et l'aménagement des cours d'eau (RS 721.1) | 4 | oldest version available, then each consolidated version: 3 October 2014 to 1 November 2026 |
| `721-8-lcfh/` | Loi sur l'utilisation des forces hydrauliques (RS 721.8) | 4 | oldest version available, then each consolidated version: 15 March 2017 to 1 January 2025 |
| `725-1-lr/` | Loi sur les routes (RS 725.1) | 3 | oldest version available, then each consolidated version: 1 January 2014 to 1 January 2025 |
| `726-1-lcaimp/` | Loi concernant l'adhésion du canton du Valais à l'accord intercantonal sur les marchés publics du 15 novembre 2019 (RS 726.1) | 2 | oldest version available, then each consolidated version: 1 January 2012 to 1 January 2024 |
| `730-1-lcene/` | Loi sur l'énergie (RS 730.1) | 4 | oldest version available, then each consolidated version: 1 July 2004 to 1 January 2026 |
| `731-1-lfmv/` | Loi sur les Forces Motrices Valaisannes (RS 731.1) | 1 | one version (the oldest available), 15 March 2017 |
| `734-1-lcapel/` | Loi cantonale sur l'approvisionnement en électricité (RS 734.1) | 1 | one version (the oldest available), 1 June 2015 |
| `740-1-ltpmdquot/` | Loi sur les transports publics et la mobilité douce quotidienne (RS 740.1) | 2 | oldest version available, then each consolidated version: 1 January 2012 to 1 January 2023 |
| `741-1-lalcr/` | Loi d'application de la législation fédérale sur la circulation routière (RS 741.1) | 3 | oldest version available, then each consolidated version: 1 January 2013 to 1 November 2025 |
| `747-2/` | Loi d'application de la loi fédérale sur la navigation intérieure et de l'accord franco-suisse concernant la navigation sur le Léman (RS 747.2) | 1 | one version (the oldest available), 17 September 1982 |
| `800-1-ls/` | Loi sur la santé (RS 800.1) | 3 | oldest version available, then each consolidated version: 1 January 2018 to 1 May 2025 |
| `800-10-leis/` | Loi sur les établissements et institutions sanitaires (RS 800.10) | 2 | oldest version available, then each consolidated version: 1 January 2017 to 15 April 2023 |
| `805-1-lsld/` | Loi sur les soins de longue durée (RS 805.1) | 1 | one version (the oldest available), 1 January 2015 |
| `805-2-lspasi/` | Loi sur les soins palliatifs et l'encadrement de la pratique de l'assistance au suicide en institution (RS 805.2) | 1 | one version (the oldest available), 1 March 2023 |
| `810-8-loss/` | Loi sur l'organisation des secours sanitaires (RS 810.8) | 3 | oldest version available, then each consolidated version: 1 January 2015 to 1 January 2018 |
| `811-3/` | Loi sur la mise à disposition des places de stage et d’apprentissage pour les professions non universitaires de la santé (RS 811.3) | 1 | one version (the oldest available), 1 April 2021 |
| `813-5/` | Loi vétérinaire (RS 813.5) | 1 | one version (the oldest available), 1 July 2012 |
| `813-10-loi-sur-les-produits-chimiques-lachim/` | Loi d'application de la loi fédérale sur la protection contre les substances et les préparations dangereuses (RS 813.10) | 1 | one version (the oldest available), 1 January 2015 |
| `814-1-lcpe/` | Loi sur la protection de l'environnement (RS 814.1) | 3 | oldest version available, then each consolidated version: 1 January 2014 to 1 December 2022 |
| `814-3-lceaux/` | Loi cantonale sur la protection des eaux (RS 814.3) | 1 | one version (the oldest available), 1 January 2014 |
| `814-7-lalrnis/` | Loi d'application de la loi fédérale sur la protection contre les dangers liés au rayonnement non ionisant et au son (RS 814.7) | 1 | one version (the oldest available), 1 December 2022 |
| `817-1/` | Loi concernant l'application de la loi fédérale sur les denrées alimentaires et les objets usuels (RS 817.1) | 2 | oldest version available, then each consolidated version: 1 June 2016 to 1 September 2022 |
| `822-1-lctr/` | Loi cantonale sur le travail (RS 822.1) | 3 | oldest version available, then each consolidated version: 1 October 2016 to 1 January 2025 |
| `822-2/` | Loi sur le repos du dimanche et des jours de fête (RS 822.2) | 1 | one version (the oldest available), 1 March 2013 |
| `822-20/` | Loi concernant l'ouverture des magasins (RS 822.20) | 2 | oldest version available, then each consolidated version: 1 November 2002 to 1 December 2018 |
| `823-1-laldetltn/` | Loi d'application de la loi fédérale sur les travailleurs détachés et de la loi fédérale sur le travail au noir (RS 823.1) | 3 | oldest version available, then each consolidated version: 1 October 2016 to 1 March 2023 |
| `831-1-lalavs/` | Loi d'application de la loi fédérale sur l'assurance-vieillesse et survivants (RS 831.1) | 1 | one version (the oldest available), 1 January 2011 |
| `831-2/` | Loi d'application de la loi fédérale sur l'assurance invalidité (RS 831.2) | 1 | one version (the oldest available), 1 January 2011 |
| `831-3-lalpc/` | Loi d'application de la loi fédérale sur les prestations complémentaires à l'AVS/AI (RS 831.3) | 2 | oldest version available, then each consolidated version: 1 January 2011 to 1 January 2021 |
| `832-1/` | Loi sur l'assurance maladie (RS 832.1) | 2 | oldest version available, then each consolidated version: 1 January 1996 to 1 January 2020 |
| `836-1-lalafam/` | Loi d'application de la loi fédérale sur les allocations familiales (RS 836.1) | 5 | oldest version available, then each consolidated version: 1 January 2013 to 1 January 2025 |
| `837-1-lemc/` | Loi sur l'emploi et les mesures en faveur des chômeurs (RS 837.1) | 1 | one version (the oldest available), 14 February 2014 |
| `841-1/` | Loi sur le logement (RS 841.1) | 1 | one version (the oldest available), 1 May 1996 |
| `850-1-lias/` | Loi sur l'intégration et l'aide sociale (RS 850.1) | 5 | oldest version available, then each consolidated version: 1 January 2012 to 1 January 2022 |
| `850-2-lharm/` | Loi sur l'harmonisation du financement des régimes sociaux et d'insertion socio-professionnelle (RS 850.2) | 2 | oldest version available, then each consolidated version: 1 January 2015 to 1 January 2025 |
| `850-3-lrace/` | Loi sur le recouvrement et les avances de contributions d'entretien (RS 850.3) | 2 | oldest version available, then each consolidated version: 1 January 2005 to 1 January 2022 |
| `850-4-lje/` | Loi en faveur de la jeunesse (RS 850.4) | 4 | oldest version available, then each consolidated version: 1 October 2014 to 1 October 2025 |
| `850-6-ldiph/` | Loi sur les droits et l'inclusion des personnes en situation de handicap (RS 850.6) | 4 | oldest version available, then each consolidated version: 1 January 2012 to 1 January 2022 |
| `857-1/` | Loi d'application de la loi fédérale sur les centres de consultation en matière de grossesse (RS 857.1) | 1 | one version (the oldest available), 1 May 1996 |
| `900-1-lpoleco/` | Loi sur la politique économique cantonale (RS 900.1) | 1 | one version (the oldest available), 1 January 2013 |
| `900-2-lpi/` | Loi sur la société de gestion et d’exploitation du parc de l’innovation du Campus Energypolis (RS 900.2) | 1 | one version (the oldest available), 1 February 2023 |
| `901-1/` | Loi sur la politique régionale (RS 901.1) | 1 | one version (the oldest available), 1 January 2010 |
| `902-1-lerm/` | Loi sur l'encouragement des remontées mécaniques (RS 902.1) | 2 | oldest version available, then each consolidated version: 1 March 2019 to 1 January 2025 |
| `910-1-loi-sur-l-agriculture-lcagr/` | Loi sur l'agriculture et le développement rural (RS 910.1) | 4 | oldest version available, then each consolidated version: 1 June 2016 to 1 January 2025 |
| `916-4/` | Loi d'application de la loi fédérale sur les épizooties (RS 916.4) | 2 | oldest version available, then each consolidated version: 1 January 2009 to 1 January 2025 |
| `921-1-lcfo/` | Loi sur les forêts (RS 921.1) | 6 | oldest version available, then each consolidated version: 1 January 2014 to 1 January 2023 |
| `922-1-loi-sur-la-chasse-lcchp/` | Loi sur la chasse et la protection des mammifères et oiseaux sauvages (RS 922.1) | 3 | oldest version available, then each consolidated version: 1 May 1996 to 1 November 2026 |
| `923-1-lcsp/` | Loi cantonale sur la pêche (RS 923.1) | 2 | oldest version available, then each consolidated version: 1 January 2018 to 1 January 2025 |
| `930-1/` | Loi sur la police du commerce (RS 930.1) | 3 | oldest version available, then each consolidated version: 1 January 2010 to 1 September 2022 |
| `931-1/` | Loi sur les mines et carrières (RS 931.1) | 1 | one version (the oldest available), 1 January 1997 |
| `932-1-lprost/` | Loi sur la prostitution (RS 932.1) | 1 | one version (the oldest available), 1 January 2016 |
| `935-1/` | Loi sur le tourisme (RS 935.1) | 2 | oldest version available, then each consolidated version: 1 January 2015 to 1 September 2022 |
| `935-2-lgar/` | Loi sur les guides de montagne et les organisateurs d'autres activités à risque (RS 935.2) | 2 | oldest version available, then each consolidated version: 1 January 2014 to 1 May 2018 |
| `935-3-lhr/` | Loi sur l'hébergement, la restauration et le commerce de détail de boissons alcoolisées (RS 935.3) | 3 | oldest version available, then each consolidated version: 1 January 2018 to 1 January 2025 |
| `935-55-laljar/` | Loi d'application de la loi fédérale sur les jeux d'argent (RS 935.55) | 1 | one version (the oldest available), 1 January 2021 |
| `941-2/` | Loi d'application de la loi fédérale sur la métrologie (RS 941.2) | 1 | one version (the oldest available), 1 January 2006 |
| `946-2/` | Loi concernant la reconnaissance des formations professionnelles des ressortissants des Etats membres de la Communauté européenne (RS 946.2) | 1 | one version (the oldest available), 1 June 2003 |
| `141-100/` | Règlement concernant l'exécution de la loi sur le droit de cité valaisan (RS 141.100) | 1 | one version (the oldest available), 1 January 2008 |
| `142-100-olaletr/` | Ordonnance de la loi d'application de la loi fédérale sur les étrangers (RS 142.100) | 1 | one version (the oldest available), 1 January 2013 |
| `142-104/` | Règlement fixant les taxes de police des étrangers et leur mode de répartition entre l'Etat et les communes (RS 142.104) | 3 | oldest version available, then each consolidated version: 1 September 2015 to 1 October 2021 |
| `142-400-olalmc/` | Ordonnance d'exécution de la loi d'application de la loi fédérale sur les mesures de contrainte en matière de droit des étrangers (RS 142.400) | 1 | one version (the oldest available), 15 July 1997 |
| `143-300/` | Ordonnance d'application sur les documents d'identité (RS 143.300) | 1 | one version (the oldest available), 1 March 2010 |
| `151-100/` | Règlement fixant les tâches et compétences de l'Office cantonal de l'égalité et de la famille et du Conseil de l'égalité et de la famille (RS 151.100) | 2 | oldest version available, then each consolidated version: 11 March 1998 to 1 May 2017 |
| `160-102/` | Ordonnance sur le vote par correspondance (RS 160.102) | 3 | oldest version available, then each consolidated version: 1 January 2012 to 1 February 2024 |
| `160-500/` | Ordonnance sur les incompatibilités (RS 160.500) | 1 | one version (the oldest available), 1 July 2016 |
| `170-5-rbo/` | Règlement sur le Bulletin officiel (RS 170.5) | 3 | oldest version available, then each consolidated version: 1 January 2000 to 1 March 2023 |
| `170-30-rpartet/` | Règlement concernant les participations de l'Etat à des personnes morales et autres entités (RS 170.30) | 2 | oldest version available, then each consolidated version: 1 January 2012 to 1 May 2021 |
| `170-202-relipda/` | Règlement d'exécution de la loi sur l'information du public, la protection des données et l'archivage (RS 170.202) | 3 | oldest version available, then each consolidated version: 1 October 2015 to 1 January 2024 |
| `170-206-reccpdt/` | Règlement de la Commission cantonale de protection des données et de transparence (RS 170.206) | 1 | one version (the oldest available), 1 October 2024 |
| `170-510/` | Règlement sur la publication en ligne des recueils cantonaux (RS 170.510) | 1 | one version (the oldest available), 1 August 2018 |
| `170-800-osna/` | Ordonnance sur les services numériques des autorités (RS 170.800) | 1 | one version (the oldest available), 1 January 2025 |
| `171-100-rgc/` | Règlement du Grand Conseil (RS 171.100) | 5 | oldest version available, then each consolidated version: 1 March 2017 to 12 September 2025 |
| `172-010/` | Ordonnance sur les attributions de la présidence et des départements (RS 172.010) | 5 | oldest version available, then each consolidated version: 1 May 2013 to 1 May 2025 |
| `172-011/` | Règlement sur le Conseil d'Etat (RS 172.011) | 1 | one version (the oldest available), 9 September 2016 |
| `172-050/` | Règlement sur l'organisation de l'Administration cantonale (RS 172.050) | 2 | oldest version available, then each consolidated version: 24 October 2014 to 1 August 2018 |
| `172-130/` | Ordonnance sur la prévoyance professionnelle des magistrats (RS 172.130) | 1 | one version (the oldest available), 1 January 2015 |
| `172-132/` | Règlement concernant le régime de pensions des magistrats (RS 172.132) | 1 | one version (the oldest available), 1 January 2015 |
| `172-200-ocpers/` | Ordonnance sur le personnel de l'Etat du Valais (RS 172.200) | 8 | oldest version available, then each consolidated version: 1 July 2011 to 1 May 2026 |
| `172-211-rttr/` | Règlement sur le temps de travail dans l'administration cantonale (RS 172.211) | 4 | oldest version available, then each consolidated version: 1 January 2012 to 1 January 2024 |
| `172-212-rss-pers/` | Règlement régissant l'organisation et la gestion de la sécurité et de la protection de la santé au travail pour le personnel de l'Etat du Valais (RS 172.212) | 2 | oldest version available, then each consolidated version: 1 March 2008 to 1 January 2024 |
| `172-216/` | Règlement sur les personnes en formation professionnelle initiale de l'Administration cantonale (RS 172.216) | 2 | oldest version available, then each consolidated version: 1 August 2016 to 1 January 2020 |
| `172-218-rihda/` | Règlement fixant les indemnités et honoraires servis dans le domaine agricole (RS 172.218) | 2 | oldest version available, then each consolidated version: 1 May 2011 to 1 January 2025 |
| `172-220-reglement-sur-la-formation/` | Règlement sur la formation continue pour le personnel de l'Administration cantonale (RS 172.220) | 2 | oldest version available, then each consolidated version: 1 January 2012 to 1 January 2021 |
| `172-224/` | Règlement sur les cartes de légitimation pour les employés d'Etat exerçant une tâche de police (RS 172.224) | 1 | one version (the oldest available), 1 July 2021 |
| `172-230/` | Ordonnance concernant la reconnaissance de la fidélité, de la formation de base et les départs à la retraite (RS 172.230) | 3 | oldest version available, then each consolidated version: 1 January 2012 to 1 January 2021 |
| `172-410-otrait/` | Ordonnance concernant le traitement des employés de l'Etat du Valais (RS 172.410) | 7 | oldest version available, then each consolidated version: 1 January 2012 to 1 January 2025 |
| `172-420-oipg/` | Ordonnance sur l’indemnisation de la perte de gain en cas de maladie et d’accident non professionnel du personnel de l’Etat du Valais (RS 172.420) | 1 | one version (the oldest available), 1 January 2025 |
| `172-431/` | Règlement sur les indemnités de déplacements (RS 172.431) | 2 | oldest version available, then each consolidated version: 1 January 2011 to 1 May 2018 |
| `172-432/` | Règlement fixant les indemnités diverses et de déplacement à verser au personnel ouvrier et aux cantonniers du Service de la mobilité (RS 172.432) | 3 | oldest version available, then each consolidated version: 1 January 2011 to 1 September 2020 |
| `172-512-rcpval/` | Règlement d'exécution de la loi régissant la Caisse de prévoyance du Canton du Valais (CPVAL) (RS 172.512) | 1 | one version (the oldest available), 1 January 2020 |
| `172-514/` | Règlement d'exécution concernant l’utilisation de la provision financée par le fonds CPVAL (RS 172.514) | 1 | one version (the oldest available), 1 January 2020 |
| `172-810-ogbdr/` | Ordonnance d’application générale de la loi sur les bases de données référentielles et sur l’harmonisation des registres (RS 172.810) | 2 | oldest version available, then each consolidated version: 1 January 2021 to 1 June 2022 |
| `172-820-obdr-pp/` | Ordonnance sur la base de données référentielles des personnes physiques (RS 172.820) | 2 | oldest version available, then each consolidated version: 1 January 2021 to 1 June 2022 |
| `172-830-obdr-ee/` | Ordonnance sur la base de données référentielles des entreprises et des établissements (RS 172.830) | 1 | one version (the oldest available), 1 January 2021 |
| `172-840-obdr-bl/` | Ordonnance sur la base de données référentielles des bâtiments et des logements (RS 172.840) | 1 | one version (the oldest available), 1 January 2023 |
| `173-100-rot/` | Règlement d'organisation des tribunaux valaisans (RS 173.100) | 3 | oldest version available, then each consolidated version: 1 January 2011 to 1 July 2025 |
| `173-101/` | Règlement du ministère public du canton du Valais (RS 173.101) | 4 | oldest version available, then each consolidated version: 3 January 2011 to 1 December 2022 |
| `173-102/` | Règlement sur l'archivage des dossiers judiciaires (RS 173.102) | 2 | oldest version available, then each consolidated version: 1 February 2002 to 1 July 2026 |
| `173-104/` | Règlement sur l'accréditation des journalistes auprès des tribunaux valaisans (RS 173.104) | 1 | one version (the oldest available), 1 January 2011 |
| `173-105-recc/` | Règlement fixant la contribution des communes aux frais d'installation et de fonctionnement des tribunaux et des offices du ministère public (RS 173.105) | 2 | oldest version available, then each consolidated version: 1 January 2012 to 1 January 2023 |
| `173-122/` | Règlement concernant la révision du concept salarial des greffiers (RS 173.122) | 1 | one version (the oldest available), 1 January 1996 |
| `173-400/` | Règlement régissant la procédure devant le Tribunal cantonal des assurances (RS 173.400) | 1 | one version (the oldest available), 1 February 2002 |
| `173-700-rcdm/` | Règlement du Conseil de la magistrature (RS 173.700) | 1 | one version (the oldest available), 1 January 2021 |
| `173-710-recorem/` | Règlement de la Commission de recours du Conseil de la magistrature (RS 173.710) | 1 | one version (the oldest available), 30 July 2021 |
| `175-100-ofus/` | Ordonnance sur les fusions de communes (RS 175.100) | 1 | one version (the oldest available), 31 October 2014 |
| `177-101-rlpav/` | Règlement concernant la loi sur la profession d'avocat (RS 177.101) | 8 | oldest version available, then each consolidated version: 1 January 2017 to 1 January 2026 |
| `177-700-oaj/` | Ordonnance sur l'assistance judiciaire (RS 177.700) | 3 | oldest version available, then each consolidated version: 1 January 2011 to 1 July 2023 |
| `178-101-rln/` | Règlement concernant la loi sur le notariat (RS 178.101) | 8 | oldest version available, then each consolidated version: 1 January 2017 to 1 January 2026 |
| `178-104/` | Règlement fixant le tarif des émoluments et des débours des notaires (RS 178.104) | 1 | one version (the oldest available), 1 January 2011 |
| `180-100/` | Règlement d'application de la loi sur les rapports entre les Eglises et l'Etat dans le canton du Valais (RS 180.100) | 2 | oldest version available, then each consolidated version: 1 January 2017 to 1 September 2025 |
| `211-100-oelacc/` | Ordonnance générale d'exécution de la loi d'application du code civil suisse (RS 211.100) | 3 | oldest version available, then each consolidated version: 1 January 2013 to 1 June 2025 |
| `211-130/` | Ordonnance sur l'état civil (RS 211.130) | 1 | one version (the oldest available), 1 January 2008 |
| `211-250-opea/` | Ordonnance sur la protection de l'enfant et de l'adulte (RS 211.250) | 8 | oldest version available, then each consolidated version: 1 January 2016 to 1 January 2027 |
| `211-255-refa/` | Règlement fixant les frais perçus par les autorités de protection de l'enfant et de l'adulte (RS 211.255) | 4 | oldest version available, then each consolidated version: 1 January 2023 to 1 October 2024 |
| `211-260-osap/` | Ordonnance fixant le siège des autorités cantonales de protection de l'enfant et de l'adulte (RS 211.260) | 1 | one version (the oldest available), 1 January 2023 |
| `211-410-raie/` | Règlement sur l'acquisition d'immeubles par des personnes à l'étranger (RS 211.410) | 4 | oldest version available, then each consolidated version: 1 January 2016 to 1 January 2026 |
| `211-600-ocmo/` | Ordonnance sur la mensuration officielle (RS 211.600) | 3 | oldest version available, then each consolidated version: 1 July 2006 to 1 January 2026 |
| `211-610/` | Ordonnance concernant l'introduction du registre foncier dans le canton du Valais (RS 211.610) | 1 | one version (the oldest available), 3 February 2012 |
| `211-611-ocrf/` | Ordonnance cantonale sur le registre foncier (RS 211.611) | 3 | oldest version available, then each consolidated version: 2 January 2015 to 1 October 2025 |
| `211-612/` | Ordonnance sur la tenue du registre foncier informatisé (RS 211.612) | 4 | oldest version available, then each consolidated version: 27 June 2014 to 1 October 2025 |
| `211-700-ocgeo/` | Ordonnance sur la géoinformation (RS 211.700) | 1 | one version (the oldest available), 1 July 2022 |
| `211-705-occrdp/` | Ordonnance sur le cadastre des restrictions de droit public à la propriété foncière (RS 211.705) | 1 | one version (the oldest available), 1 July 2022 |
| `221-210/` | Ordonnance concernant l'octroi d'un crédit à la consommation et le courtage en crédit (RS 221.210) | 1 | one version (the oldest available), 1 July 2004 |
| `271-100/` | Règlement concernant l'assistance financière en médiation civile (RS 271.100) | 1 | one version (the oldest available), 1 June 2014 |
| `281-100-oalp/` | Ordonnance d'application de la législation sur la poursuite pour dettes et la faillite (RS 281.100) | 1 | one version (the oldest available), 1 September 2015 |
| `311-200-oelacp/` | Ordonnance générale d'exécution de la loi d'application du code pénal (RS 311.200) | 2 | oldest version available, then each consolidated version: 3 July 2015 to 1 January 2018 |
| `311-210-olec/` | Ordonnance sur l'exécution des confiscations (RS 311.210) | 1 | one version (the oldest available), 1 January 2018 |
| `311-300/` | Règlement concernant l'utilisation d'un fonds de soutien en faveur des personnes détenues (RS 311.300) | 1 | one version (the oldest available), 19 February 2016 |
| `312-100-reldpolj/` | Règlement d'exécution de la loi concernant les dossiers de police judiciaire (RS 312.100) | 1 | one version (the oldest available), 1 February 2004 |
| `340-100/` | Ordonnance sur les droits et les devoirs de la personne détenue (RS 340.100) | 2 | oldest version available, then each consolidated version: 1 January 2015 to 1 January 2018 |
| `340-104/` | Ordonnance concernant l'organisation, les droits et devoirs du personnel du service de l'application des peines et mesures (RS 340.104) | 1 | one version (the oldest available), 1 May 2017 |
| `343-300/` | Règlement concernant l'octroi d'autorisations de sortie aux personnes condamnées adultes et jeunes adultes (RS 343.300) | 2 | oldest version available, then each consolidated version: 4 April 2014 to 1 April 2024 |
| `343-301/` | Règlement concernant la Fondation latine Projets pilotes - Addictions (RS 343.301) | 1 | one version (the oldest available), 1 June 2014 |
| `343-310/` | Règlement concernant la liste des établissements pour l'exécution des privations de liberté à caractère pénal (RS 343.310) | 1 | one version (the oldest available), 1 January 2011 |
| `343-320-reglement-sur-le-tig/` | Règlement sur l'exécution des peines sous la forme du travail d'intérêt général (RS 343.320) | 1 | one version (the oldest available), 1 January 2018 |
| `343-330-reglement-sur-la-semi-detention/` | Règlement sur l'exécution des peines sous la forme de la semi-détention (RS 343.330) | 1 | one version (the oldest available), 1 January 2018 |
| `343-340/` | Ordonnance sur la surveillance électronique (RS 343.340) | 1 | one version (the oldest available), 1 January 2018 |
| `343-340-1/` | Règlement sur l’exécution des peines privatives de liberté sous surveillance électronique (RS 343.340-1) | 1 | one version (the oldest available), 1 January 2018 |
| `343-400/` | Règlement concernant l'octroi d'autorisations de sortie aux personnes condamnées mineures (RS 343.400) | 1 | one version (the oldest available), 1 January 2014 |
| `343-401/` | Règlement sur le droit disciplinaire applicable aux personnes détenues pénalement ou placées dans des établissements fermés pour mineurs (RS 343.401) | 1 | one version (the oldest available), 1 January 2014 |
| `400-20-opso/` | Ordonnance sur le personnel de la scolarité obligatoire et de l'enseignement secondaire du deuxième degré général et professionnel (RS 400.20) | 5 | oldest version available, then each consolidated version: 1 September 2012 to 1 January 2026 |
| `400-21-rsubfce/` | Règlement concernant le subventionnement de la formation continue individuelle pour le personnel enseignant de la scolarité obligatoire et du secondaire II général (RS 400.21) | 2 | oldest version available, then each consolidated version: 1 August 2024 to 1 August 2026 |
| `400-050/` | Règlement concernant le compte de financement spécial Centrale cantonale des moyens d'enseignement (RS 400.050) | 1 | one version (the oldest available), 5 July 2013 |
| `400-100/` | Règlement concernant l'octroi de subventions diverses en vertu de la loi sur l'instruction publique (RS 400.100) | 3 | oldest version available, then each consolidated version: 1 August 2015 to 1 August 2024 |
| `400-101/` | Règlement concernant la prise en charge des frais pour les fournitures scolaires et les activités culturelles et sportives relatifs à la scolarité obligatoire (RS 400.101) | 3 | oldest version available, then each consolidated version: 1 August 2019 to 1 August 2021 |
| `400-102/` | Règlement concernant l'éducation physique à l'école (RS 400.102) | 1 | one version (the oldest available), 1 August 2015 |
| `400-104-rasn/` | Règlement concernant les modalités d'application de l'action sports de neige (RS 400.104) | 3 | oldest version available, then each consolidated version: 1 December 2020 to 1 August 2024 |
| `400-105/` | Règlement concernant l'apposition de signatures et de sceaux officiels sur des diplômes ou documents similaires émanant d'institutions privées (RS 400.105) | 1 | one version (the oldest available), 1 January 1999 |
| `400-106/` | Règlement concernant la reconnaissance d'une école secondaire privée (RS 400.106) | 1 | one version (the oldest available), 1 November 1965 |
| `400-107/` | Règlement concernant l'inspection des écoles de la scolarité obligatoire et de l'enseignement secondaire du deuxième degré (RS 400.107) | 1 | one version (the oldest available), 1 August 2015 |
| `400-108-reil/` | Règlement concernant les aides aux échanges et immersions linguistiques (RS 400.108) | 1 | one version (the oldest available), 1 January 2025 |
| `400-109/` | Règlement concernant le Conseil de l'instruction publique (RS 400.109) | 1 | one version (the oldest available), 15 August 2008 |
| `400-110-rfrp/` | Règlement concernant la prise en charge des frais pour les ressources pédagogiques relatives à la scolarité obligatoire (RS 400.110) | 1 | one version (the oldest available), 1 August 2024 |
| `400-120-rmftp/` | Règlement concernant les modalités de prise en charge des frais de déplacement en transport public pour les apprentis et étudiants du secondaire du deuxième degré général (RS 400.120) | 8 | oldest version available, then each consolidated version: 1 June 2016 to 1 August 2025 |
| `400-200-rcs/` | Règlement fixant les normes et directives concernant les constructions scolaires de la scolarité obligatoire (RS 400.200) | 4 | oldest version available, then each consolidated version: 1 August 2015 to 1 August 2024 |
| `400-300/` | Règlement concernant l'indemnité versée au personnel enseignant pour l'utilisation de son matériel informatique à des fins professionnelles (RS 400.300) | 1 | one version (the oldest available), 1 September 2021 |
| `405-20/` | Ordonnance concernant la direction des écoles de la scolarité obligatoire (RS 405.20) | 1 | one version (the oldest available), 1 August 2015 |
| `405-30-otso/` | Ordonnance concernant le traitement du personnel de la scolarité obligatoire et de l'enseignement secondaire du deuxième degré général et professionnel (RS 405.30) | 8 | oldest version available, then each consolidated version: 1 August 2015 to 1 January 2025 |
| `405-100/` | Règlement concernant la contribution des communes au traitement du personnel de la scolarité obligatoire et aux charges d'exploitation des institutions spécialisées (RS 405.100) | 2 | oldest version available, then each consolidated version: 12 August 2016 to 1 November 2019 |
| `411-001-olep/` | Ordonnance concernant la loi sur l'enseignement primaire (RS 411.001) | 3 | oldest version available, then each consolidated version: 1 August 2015 to 1 September 2023 |
| `411-100/` | Ordonnance fixant le statut de la commission scolaire (RS 411.100) | 1 | one version (the oldest available), 1 January 2013 |
| `411-101/` | Règlement concernant les congés et les mesures disciplinaires applicables dans les limites de la scolarité obligatoire (RS 411.101) | 3 | oldest version available, then each consolidated version: 1 August 2015 to 1 August 2025 |
| `411-102/` | Règlement fixant l'organisation et les attributions de la commission cantonale de l'enseignement secondaire (RS 411.102) | 1 | one version (the oldest available), 11 October 1989 |
| `411-106-oeval/` | Ordonnance relative à l'évaluation du travail des élèves à l'école obligatoire (RS 411.106) | 2 | oldest version available, then each consolidated version: 1 August 2015 to 1 August 2026 |
| `411-200/` | Ordonnance concernant les structures suprarégionales du cycle d'orientation (RS 411.200) | 3 | oldest version available, then each consolidated version: 1 September 2012 to 1 August 2021 |
| `411-300-oles/` | Ordonnance concernant la loi sur l'enseignement spécialisé (RS 411.300) | 2 | oldest version available, then each consolidated version: 7 November 2008 to 1 September 2017 |
| `411-320/` | Règlement fixant l'organisation et les attributions de la commission stratégique cantonale de la pédagogie spécialisée (RS 411.320) | 1 | one version (the oldest available), 1 January 2019 |
| `412-100-olalfpr/` | Ordonnance concernant la loi d'application de la loi fédérale sur la formation professionnelle (RS 412.100) | 2 | oldest version available, then each consolidated version: 1 September 2012 to 22 April 2022 |
| `412-101/` | Ordonnance concernant le statut et le traitement des maîtres professionnels des cours interentreprises organisés dans les écoles professionnelles cantonales (RS 412.101) | 1 | one version (the oldest available), 1 September 2013 |
| `412-103-oospc/` | Ordonnance sur l'orientation scolaire, professionnelle et de carrière (RS 412.103) | 3 | oldest version available, then each consolidated version: 1 September 2012 to 22 April 2022 |
| `412-104/` | Ordonnance concernant les procédures de qualifications professionnelles pour adultes (RS 412.104) | 1 | one version (the oldest available), 1 January 2024 |
| `412-105-rap/` | Règlement concernant la reconnaissance d’acquis professionnels (RS 412.105) | 1 | one version (the oldest available), 1 May 2024 |
| `412-106-oomp/` | Ordonnance sur l'organisation de la maturité professionnelle (RS 412.106) | 2 | oldest version available, then each consolidated version: 1 September 2014 to 1 August 2026 |
| `412-309/` | Ordonnance concernant le fonctionnement des écoles cantonales du secondaire du deuxième degré professionnel (RS 412.309) | 1 | one version (the oldest available), 1 September 2013 |
| `412-310-oodesp/` | Ordonnance concernant l'organisation et les directions des écoles cantonales du secondaire du deuxième degré professionnel (RS 412.310) | 2 | oldest version available, then each consolidated version: 1 September 2012 to 1 September 2023 |
| `412-500/` | Règlement d'exécution de la loi sur le fonds cantonal en faveur de la formation professionnelle (RS 412.500) | 2 | oldest version available, then each consolidated version: 1 January 2013 to 1 January 2021 |
| `412-510-rfcfca/` | Règlement concernant le fonds cantonal de la formation continue des adultes (RS 412.510) | 2 | oldest version available, then each consolidated version: 1 January 2021 to 22 April 2022 |
| `412-550/` | Règlement concernant le compte de financement spécial "Formation professionnelle" (RS 412.550) | 1 | one version (the oldest available), 27 October 2010 |
| `413-100/` | Règlement général concernant les établissements de l'enseignement secondaire du deuxième degré (RS 413.100) | 2 | oldest version available, then each consolidated version: 1 September 2012 to 1 August 2025 |
| `413-101/` | Ordonnance concernant les directions des écoles cantonales du degré secondaire II général (RS 413.101) | 1 | one version (the oldest available), 1 September 2012 |
| `413-105-rmsop/` | Règlement de la maturité spécialisée orientation pédagogie du canton du Valais (RS 413.105) | 2 | oldest version available, then each consolidated version: 1 September 2013 to 1 August 2024 |
| `413-106-rec/` | Règlement des écoles des métiers du commerce (RS 413.106) | 4 | oldest version available, then each consolidated version: 1 August 2015 to 1 August 2026 |
| `413-108/` | Règlement de l'école de culture générale (RS 413.108) | 3 | oldest version available, then each consolidated version: 1 September 2008 to 1 August 2021 |
| `413-109/` | Règlement des écoles préprofessionnelles du canton du Valais (RS 413.109) | 1 | one version (the oldest available), 1 September 2007 |
| `413-110/` | Règlement concernant les études gymnasiales et les examens de maturité (RS 413.110) | 2 | oldest version available, then each consolidated version: 1 September 2010 to 1 August 2017 |
| `413-111-rmsso/` | Règlement de la maturité spécialisée domaine "travail social" du canton du Valais (RS 413.111) | 2 | oldest version available, then each consolidated version: 1 September 2010 to 1 August 2024 |
| `413-112-rve/` | Règlement concernant les voyages d'études pour les écoles du secondaire II général (RS 413.112) | 1 | one version (the oldest available), 1 September 2011 |
| `413-113/` | Règlement relatif à l'examen complémentaire permettant aux titulaires d'un certificat fédéral de maturité professionnelle ou d'un certificat de maturité spécialisée reconnu au niveau suisse d'être admis aux hautes écoles universitaires (RS 413.113) | 3 | oldest version available, then each consolidated version: 1 February 2016 to 1 September 2017 |
| `413-115-rmssa/` | Règlement de la maturité spécialisée domaine "santé/sciences expérimentales" du canton du Valais (RS 413.115) | 2 | oldest version available, then each consolidated version: 1 September 2015 to 1 August 2024 |
| `413-116-rmsmt/` | Règlement de la maturité spécialisée domaine "musique et théâtre" du canton du Valais (RS 413.116) | 2 | oldest version available, then each consolidated version: 1 September 2015 to 1 August 2024 |
| `413-210-otes/` | Ordonnance concernant les titres et diplômes pour l'enseignement dans les écoles de l'enseignement secondaire du degré I et du degré II général (RS 413.210) | 2 | oldest version available, then each consolidated version: 1 March 2008 to 1 August 2021 |
| `414-300-reglement-es-social/` | Règlement d'études concernant les filières école supérieure (ES) éducation de l’enfance et maîtrise socioprofessionnelle de la Haute Ecole Spécialisée de Suisse occidentale Valais-Wallis (RS 414.300) | 4 | oldest version available, then each consolidated version: 1 September 2013 to 1 August 2025 |
| `414-305/` | Règlement d’études concernant la filière ES (école supérieure) en soins infirmiers (RS 414.305) | 3 | oldest version available, then each consolidated version: 1 September 2018 to 1 September 2022 |
| `414-701/` | Ordonnance concernant le statut du personnel de la Haute Ecole Spécialisée de Suisse occidentale Valais/Wallis (RS 414.701) | 2 | oldest version available, then each consolidated version: 1 September 2016 to 1 April 2022 |
| `414-702/` | Ordonnance concernant le traitement du personnel de la Haute Ecole Spécialisée de Suisse occidentale Valais/Wallis (RS 414.702) | 2 | oldest version available, then each consolidated version: 1 September 2016 to 1 April 2022 |
| `414-703/` | Ordonnance concernant la gestion et le contrôle financier et des prestations de la HES-SO Valais/Wallis (RS 414.703) | 2 | oldest version available, then each consolidated version: 1 January 2015 to 31 December 2017 |
| `414-705-o-langues-hes-so-vs-ws/` | Ordonnance concernant l'usage du français et/ou de l'allemand dans l'enseignement à la HES-SO Valais/Wallis et dans ses relations avec les étudiants (RS 414.705) | 1 | one version (the oldest available), 1 September 2019 |
| `414-720/` | Règlement des modules complémentaires santé (RS 414.720) | 2 | oldest version available, then each consolidated version: 1 September 2016 to 1 August 2020 |
| `414-733-rpivhes/` | Règlement concernant la propriété intellectuelle, la valorisation et l'exploitation des résultats acquis par la recherche de la HES-SO Valais/Wallis (RS 414.733) | 2 | oldest version available, then each consolidated version: 1 January 2010 to 1 January 2024 |
| `415-100/` | Ordonnance sur le sport (RS 415.100) | 1 | one version (the oldest available), 1 January 2018 |
| `415-102-rsis/` | Règlement concernant le subventionnement des installations sportives (RS 415.102) | 1 | one version (the oldest available), 1 January 2024 |
| `415-200/` | Règlement d'exécution de la loi réglant l'octroi de subventions cantonales pour la construction et l'agrandissement d'aménagements destinés à la gymnastique et au sport (RS 415.200) | 1 | one version (the oldest available), 1 January 2012 |
| `416-100-obpe/` | Ordonnance sur les bourses et prêts d'études (RS 416.100) | 6 | oldest version available, then each consolidated version: 1 July 2016 to 1 July 2023 |
| `416-110-rafsi/` | Règlement concernant les aides à la formation pour les filières en soins infirmiers en école supérieure et en haute école spécialisée (RS 416.110) | 1 | one version (the oldest available), 1 July 2024 |
| `417-030/` | Ordonnance concernant le traitement du personnel des écoles de formation professionnelle supérieure en Valais (RS 417.030) | 1 | one version (the oldest available), 1 January 2015 |
| `417-100-r-lccs/` | Règlement fixant la localisation et la contribution des communes sièges aux institutions de formation et de recherche du degré tertiaire (RS 417.100) | 3 | oldest version available, then each consolidated version: 1 January 2015 to 1 January 2026 |
| `417-403-rri/` | Règlement concernant la reconnaissance institutionnelle des acquis informels (RS 417.403) | 2 | oldest version available, then each consolidated version: 1 January 2007 to 1 January 2024 |
| `419-101-ohep/` | Ordonnance concernant l'admission et la formation initiale à la Haute école pédagogique (RS 419.101) | 2 | oldest version available, then each consolidated version: 1 September 2013 to 1 September 2019 |
| `419-104-rtaxes-hep-vs/` | Règlement concernant les taxes et les contributions financières à la Haute école pédagogique du Valais (RS 419.104) | 1 | one version (the oldest available), 1 August 2020 |
| `419-105/` | Règlement concernant le plan d'études cadres de la formation initiale de la Haute école pédagogique du Valais (RS 419.105) | 1 | one version (the oldest available), 1 September 2013 |
| `419-106/` | Règlement général concernant les formations complémentaires (RS 419.106) | 1 | one version (the oldest available), 2 August 2004 |
| `419-107-ofes/` | Ordonnance sur la formation à l'enseignement du degré secondaire I et/ou du degré secondaire II (RS 419.107) | 3 | oldest version available, then each consolidated version: 1 August 2013 to 1 August 2021 |
| `419-109/` | Règlement sur la rétribution des intervenants par la Haute école pédagogique du Valais (RS 419.109) | 1 | one version (the oldest available), 17 February 2014 |
| `419-200-osp-hep-vs/` | Ordonnance concernant le statut du personnel de la Haute école pédagogique du Valais (RS 419.200) | 2 | oldest version available, then each consolidated version: 1 January 2021 to 30 December 2022 |
| `419-202-otp-hep-vs/` | Ordonnance concernant le traitement du personnel de la Haute école pédagogique du Valais (RS 419.202) | 2 | oldest version available, then each consolidated version: 1 January 2021 to 30 December 2022 |
| `419-204-ogcf-hep-vs/` | Ordonnance concernant la gestion et le contrôle financiers de la Haute école pédagogique du Valais (RS 419.204) | 2 | oldest version available, then each consolidated version: 1 January 2021 to 30 December 2022 |
| `419-206-rcost-hep-vs/` | Règlement sur la composition, l’organisation et les attributions du conseil stratégique de la Haute école pédagogique du Valais (RS 419.206) | 1 | one version (the oldest available), 1 September 2023 |
| `420-101-r-leher/` | Règlement sur l’encouragement des hautes écoles et de la recherche (RS 420.101) | 1 | one version (the oldest available), 1 January 2026 |
| `420-104-raphe/` | Règlement concernant l’activité sur le territoire cantonal des prestataires privés offrant des formations conduisant à l'obtention de diplômes de niveau haute école (RS 420.104) | 3 | oldest version available, then each consolidated version: 1 April 2021 to 1 July 2026 |
| `440-100-rprc/` | Règlement sur la promotion de la culture (RS 440.100) | 3 | oldest version available, then each consolidated version: 19 November 2010 to 1 September 2026 |
| `440-102-rspc/` | Règlement sur la sauvegarde du patrimoine culturel mobilier, documentaire, immatériel et linguistique (RS 440.102) | 2 | oldest version available, then each consolidated version: 1 July 2019 to 1 September 2026 |
| `440-104-remas/` | Règlement sur les écoles de musique et les écoles de formation culturelle dans le domaine des arts de la scène (RS 440.104) | 2 | oldest version available, then each consolidated version: 1 January 2018 to 1 September 2026 |
| `451-100-ocpn/` | Ordonnance sur la protection de la nature, du paysage et des sites (RS 451.100) | 2 | oldest version available, then each consolidated version: 1 January 2012 to 1 January 2018 |
| `451-102/` | Ordonnance sur l'octroi de contributions à l'exploitation agricole du sol pour des prestations en faveur de la nature et du paysage (RS 451.102) | 1 | one version (the oldest available), 1 October 2000 |
| `451-104/` | Règlement sur la gestion du fonds cantonal pour la protection des sites bâtis, des monuments historiques et du patrimoine archéologique (RS 451.104) | 1 | one version (the oldest available), 1 October 2018 |
| `451-106/` | Règlement sur l'aide financière en faveur de la biodiversité, du paysage et de l'adaptation aux changements climatiques dans le milieu bâti (RS 451.106) | 1 | one version (the oldest available), 1 March 2026 |
| `455-100/` | Ordonnance concernant la formation des nouveaux détenteurs de chiens (RS 455.100) | 1 | one version (the oldest available), 1 January 2020 |
| `501-100-oppex/` | Ordonnance sur la protection de la population et la gestion des situations particulières et extraordinaires (RS 501.100) | 4 | oldest version available, then each consolidated version: 22 May 2015 to 1 January 2023 |
| `501-201/` | Règlement d'organisation et de fonctionnement du Groupe de coordination cantonal Blatten 2030 (RS 501.201) | 1 | one version (the oldest available), 11 February 2026 |
| `503-100-optsd/` | Ordonnance sur la police des tirs, les installations de tir et les autorités compétentes pour prononcer les sanctions disciplinaires (RS 503.100) | 2 | oldest version available, then each consolidated version: 1 January 1999 to 1 January 2023 |
| `520-100-olalpci/` | Ordonnance de la loi d'application de la législation fédérale sur la protection civile (RS 520.100) | 2 | oldest version available, then each consolidated version: 1 January 2012 to 1 January 2024 |
| `520-101-raspci/` | Règlement concernant l'administration durant le service de protection civile (RS 520.101) | 2 | oldest version available, then each consolidated version: 9 June 2006 to 1 January 2024 |
| `520-200-ofcr/` | Ordonnance sur le fonds cantonal des contributions de remplacement en faveur des constructions de protection civile (RS 520.200) | 2 | oldest version available, then each consolidated version: 1 January 2012 to 1 January 2024 |
| `540-100-rpien/` | Règlement organisant l'exécution du service de protection contre l'incendie et les éléments naturels (RS 540.100) | 2 | oldest version available, then each consolidated version: 1 January 2012 to 1 January 2020 |
| `540-101/` | Ordonnance concernant l'entretien, le nettoyage et le contrôle des installations recevant du feu ou des fumées (RS 540.101) | 3 | oldest version available, then each consolidated version: 1 March 2017 to 1 July 2025 |
| `540-102-ompi/` | Ordonnance concernant les mesures préventives contre les incendies (RS 540.102) | 2 | oldest version available, then each consolidated version: 25 July 2008 to 1 September 2026 |
| `550-100-opol/` | Ordonnance de la loi sur la police cantonale (RS 550.100) | 5 | oldest version available, then each consolidated version: 1 January 2017 to 1 November 2024 |
| `550-101-oluc/` | Ordonnance sur l'usage des moyens de contrainte par la police cantonale (RS 550.101) | 1 | one version (the oldest available), 1 January 2018 |
| `550-102-ovidpol/` | Ordonnance sur les mesures de vidéo et d'audio-surveillance par la police cantonale (RS 550.102) | 2 | oldest version available, then each consolidated version: 1 January 2018 to 1 October 2021 |
| `550-103/` | Règlement concernant la création d'un fonds financier pour le financement des tâches confidentielles d'enquête de police (RS 550.103) | 1 | one version (the oldest available), 18 September 1998 |
| `550-110-otrapol/` | Ordonnance concernant le traitement, les frais et indemnités des membres du corps de la police cantonale (RS 550.110) | 5 | oldest version available, then each consolidated version: 1 May 2008 to 1 January 2025 |
| `550-300/` | Règlement sur les entreprises de sécurité (RS 550.300) | 1 | one version (the oldest available), 1 October 1999 |
| `550-500/` | Règlement d'application du concordat instituant des mesures contre la violence lors de manifestations sportives (RS 550.500) | 1 | one version (the oldest available), 1 April 2015 |
| `550-600-ovd/` | Ordonnance sur les violences domestiques (RS 550.600) | 3 | oldest version available, then each consolidated version: 1 January 2017 to 1 May 2026 |
| `611-100-ogf/` | Ordonnance concernant la gestion financière (RS 611.100) | 1 | one version (the oldest available), 1 January 2013 |
| `611-101/` | Ordonnance concernant la délégation de compétences financières du Conseil d'Etat aux départements et aux services (RS 611.101) | 2 | oldest version available, then each consolidated version: 1 August 2005 to 1 January 2022 |
| `611-102-ogfco/` | Ordonnance sur la gestion financière des communes (RS 611.102) | 2 | oldest version available, then each consolidated version: 5 October 2012 to 1 March 2021 |
| `611-103/` | Règlement concernant la représentation de l'Etat devant les tribunaux (RS 611.103) | 2 | oldest version available, then each consolidated version: 9 June 1989 to 27 March 2020 |
| `611-104/` | Ordonnance concernant les procédures d'encaissement et de recouvrement (RS 611.104) | 1 | one version (the oldest available), 1 October 2006 |
| `611-105/` | Ordonnance sur le controlling des finances, du personnel et des prestations (RS 611.105) | 1 | one version (the oldest available), 1 January 2010 |
| `613-100-opfi/` | Ordonnance sur la péréquation financière intercommunale (RS 613.100) | 1 | one version (the oldest available), 1 January 2012 |
| `614-100-ricf/` | Règlement concernant l'Inspection cantonale des finances (RS 614.100) | 2 | oldest version available, then each consolidated version: 29 September 1995 to 1 September 2023 |
| `616-100/` | Ordonnance sur les subventions (RS 616.100) | 2 | oldest version available, then each consolidated version: 9 October 2015 to 1 September 2023 |
| `642-100-ralf/` | Règlement d'application de la loi fiscale (RS 642.100) | 2 | oldest version available, then each consolidated version: 1 January 2011 to 1 January 2020 |
| `642-108/` | Ordonnance sur la communication aux autorités fiscales des transferts de propriété immobilière (RS 642.108) | 1 | one version (the oldest available), 1 January 2001 |
| `642-111/` | Ordonnance concernant le dépôt de la déclaration d'impôt des personnes physiques par voie électronique sans signature (RS 642.111) | 1 | one version (the oldest available), 1 January 2018 |
| `642-200-oalia/` | Ordonnance d'application de la loi fédérale sur l'impôt anticipé et de l'ordonnance fédérale relative à l'imputation d'impôts étrangers prélevés à la source (RS 642.200) | 3 | oldest version available, then each consolidated version: 20 July 2012 to 1 January 2026 |
| `642-300/` | Ordonnance concernant la fixation du caractère confiscatoire de l'impôt sur la fortune (RS 642.300) | 1 | one version (the oldest available), 1 January 2016 |
| `642-400/` | Ordonnance sur l'impôt d'après la dépense (RS 642.400) | 1 | one version (the oldest available), 1 January 2016 |
| `642-500/` | Ordonnance concernant la dation en paiement (RS 642.500) | 1 | one version (the oldest available), 1 January 2016 |
| `645-100/` | Règlement concernant les taxes cadastrales (RS 645.100) | 2 | oldest version available, then each consolidated version: 1 January 2011 to 1 January 2017 |
| `645-102/` | Règlement concernant les teneurs des registres d'impôts dans les communes (RS 645.102) | 1 | one version (the oldest available), 1 January 2012 |
| `652-100/` | Règlement concernant la perception de l'impôt sur les chiens (RS 652.100) | 2 | oldest version available, then each consolidated version: 1 January 2012 to 1 January 2020 |
| `701-100-omp/` | Ordonnance fixant les montants de la prime de démolition (RS 701.100) | 1 | one version (the oldest available), 1 October 2026 |
| `701-105/` | Règlement sur les mesures d’encouragement et sur le régime de compensation en matière d’aménagement du territoire (RS 701.105) | 2 | oldest version available, then each consolidated version: 19 April 2019 to 1 October 2026 |
| `701-201/` | Règlement fixant le tarif des prestations cantonales en matière de remembrement parcellaire urbain (RS 701.201) | 1 | one version (the oldest available), 1 January 2009 |
| `704-100-riml/` | Règlement sur les itinéraires de mobilité de loisirs (RS 704.100) | 2 | oldest version available, then each consolidated version: 1 January 2017 to 1 May 2023 |
| `705-100-oc/` | Ordonnance sur les constructions (RS 705.100) | 7 | oldest version available, then each consolidated version: 1 June 2015 to 1 January 2026 |
| `705-106-reglement-econstruction-rec/` | Règlement d’accès et d’utilisation de la plateforme cantonale eConstruction (RS 705.106) | 2 | oldest version available, then each consolidated version: 1 January 2022 to 1 January 2026 |
| `721-100-odnace/` | Ordonnance sur les dangers naturels et l'aménagement des cours d'eau (RS 721.100) | 2 | oldest version available, then each consolidated version: 1 July 2011 to 1 August 2024 |
| `721-200/` | Ordonnance relative à la détermination des espaces réservés aux eaux superficielles des grands cours d'eau (RS 721.200) | 1 | one version (the oldest available), 4 July 2014 |
| `721-800-relcfh/` | Règlement concernant l'exécution de la loi sur l'utilisation des forces hydrauliques (RS 721.800) | 2 | oldest version available, then each consolidated version: 1 January 2018 to 1 January 2025 |
| `721-801-reglement-sur-l-assurance-rc/` | Règlement concernant l'application de l'article 46 de la loi sur l'utilisation des forces hydrauliques (RS 721.801) | 1 | one version (the oldest available), 23 November 1990 |
| `721-803-rbs/` | Règlement sur les bénéfices issus de la solidarité (RS 721.803) | 1 | one version (the oldest available), 1 December 2025 |
| `725-105/` | Règlement relatif à la fermeture hivernale des routes et chemins cantonaux (RS 725.105) | 1 | one version (the oldest available), 15 October 2010 |
| `725-109/` | Règlement sur les taxes perçues pour l'usage particulier du domaine public relatif aux voies publiques cantonales, au Rhône et au Léman (RS 725.109) | 2 | oldest version available, then each consolidated version: 14 April 2017 to 1 January 2026 |
| `726-100-ocmp/` | Ordonnance sur les marchés publics (RS 726.100) | 3 | oldest version available, then each consolidated version: 1 January 2012 to 1 January 2024 |
| `726-101-olpa/` | Ordonnance concernant les listes des entreprises remplissant les conditions de participation et les critères d’aptitude (RS 726.101) | 3 | oldest version available, then each consolidated version: 1 June 2003 to 1 January 2025 |
| `730-100-ocene/` | Ordonnance sur l'énergie (RS 730.100) | 3 | oldest version available, then each consolidated version: 1 June 2011 to 1 January 2025 |
| `740-100-ratv/` | Règlement concernant l'octroi d'autorisations cantonales pour le transport de voyageurs (RS 740.100) | 2 | oldest version available, then each consolidated version: 1 June 1999 to 1 May 2023 |
| `740-200-rltpmdquot/` | Règlement sur les transports publics et la mobilité douce quotidienne (RS 740.200) | 1 | one version (the oldest available), 1 January 2023 |
| `741-100-rccsr/` | Règlement de la commission cantonale de signalisation routière (RS 741.100) | 4 | oldest version available, then each consolidated version: 8 February 1999 to 1 July 2026 |
| `741-101-resi/` | Règlement d’accès et d’utilisation de la plateforme numérique SIROUT (RS 741.101) | 1 | one version (the oldest available), 1 July 2026 |
| `741-104-rtaroac/` | Règlement fixant le tarif des émoluments et des frais en matière d'admission des personnes et des véhicules à la circulation routière (RS 741.104) | 7 | oldest version available, then each consolidated version: 1 July 2003 to 1 July 2025 |
| `741-110/` | Règlement sur les pistes de karting, de motocross et autres pistes similaires (RS 741.110) | 1 | one version (the oldest available), 1 July 1999 |
| `741-111/` | Règlement sur l'utilisation des véhicules à chenilles (RS 741.111) | 1 | one version (the oldest available), 1 February 2003 |
| `743-20/` | Ordonnance concernant la construction et l'exploitation de téléphériques et de téléskis sans concession fédérale (RS 743.20) | 1 | one version (the oldest available), 1 June 1999 |
| `747-201/` | Règlement concernant la navigation motorisée de plaisance sur les voies d'eau valaisannes (RS 747.201) | 1 | one version (the oldest available), 27 July 1990 |
| `747-202-rnavrhone/` | Règlement sur l'interdiction de naviguer sur le Rhône (RS 747.202) | 1 | one version (the oldest available), 1 April 2025 |
| `747-204/` | Règlement fixant le tarif des émoluments et des frais en matière de navigation intérieure (RS 747.204) | 1 | one version (the oldest available), 1 July 2016 |
| `748-100/` | Règlement d'exécution de la loi fédérale sur la navigation aérienne (RS 748.100) | 1 | one version (the oldest available), 1 June 1951 |
| `748-101/` | Ordonnance sur la demande en mainlevée de la saisie conservatoire d'un aéronef (RS 748.101) | 1 | one version (the oldest available), 1 January 2011 |
| `800-15/` | Ordonnance sur les conditions salariales, sociales et de prévoyance professionnelle du personnel des institutions psychiatriques du Valais romand et du Centre valaisan de pneumologie (établissements sanitaires cantonaux) (RS 800.15) | 1 | one version (the oldest available), 1 February 2007 |
| `800-16/` | Ordonnance sur le transfert des infrastructures hospitalières (RS 800.16) | 1 | one version (the oldest available), 1 February 2007 |
| `800-100/` | Ordonnance sur l'Hôpital du Valais (RS 800.100) | 2 | oldest version available, then each consolidated version: 1 January 2015 to 1 January 2018 |
| `800-101/` | Ordonnance sur la composition de l'Hôpital du Valais (RS 800.101) | 2 | oldest version available, then each consolidated version: 1 January 2017 to 1 April 2020 |
| `800-102/` | Ordonnance relative à l'Office de l'Ombudsman de la santé et des institutions sociales (RS 800.102) | 3 | oldest version available, then each consolidated version: 1 January 2018 to 1 January 2022 |
| `800-200/` | Ordonnance sur le Conseil de santé et d'éthique (RS 800.200) | 1 | one version (the oldest available), 1 October 2021 |
| `800-300-oqssp/` | Ordonnance sur la qualité des soins et la sécurité des patients (RS 800.300) | 2 | oldest version available, then each consolidated version: 26 September 2014 to 1 June 2024 |
| `800-400/` | Ordonnance sur la régulation des équipements médico-techniques lourds (RS 800.400) | 1 | one version (the oldest available), 1 January 2021 |
| `800-500/` | Ordonnance sur les mesures limitant la liberté de mouvement dans les institutions sanitaires (RS 800.500) | 1 | one version (the oldest available), 1 January 2023 |
| `801-20/` | Ordonnance concernant les structures de la santé mentale du canton du Valais (RS 801.20) | 1 | one version (the oldest available), 1 December 1996 |
| `801-100-opps/` | Ordonnance sur la promotion de la santé et la prévention des maladies non-transmissibles et des accidents (RS 801.100) | 3 | oldest version available, then each consolidated version: 1 January 2012 to 1 May 2025 |
| `801-120/` | Ordonnance sur la santé scolaire (RS 801.120) | 1 | one version (the oldest available), 1 January 2016 |
| `805-10-osld/` | Ordonnance sur la planification et le financement des soins de longue durée (RS 805.10) | 4 | oldest version available, then each consolidated version: 1 January 2015 to 1 July 2026 |
| `810-10/` | Ordonnance sur la planification sanitaire et le subventionnement des établissements et institutions sanitaires (RS 810.10) | 1 | one version (the oldest available), 1 January 2012 |
| `810-12/` | Ordonnance sur les autorisations d'exploiter une institution sanitaire (RS 810.12) | 2 | oldest version available, then each consolidated version: 1 December 1996 to 1 October 2021 |
| `810-13/` | Ordonnance sur les hospitalisations hors canton (RS 810.13) | 2 | oldest version available, then each consolidated version: 1 May 2013 to 1 January 2018 |
| `810-20/` | Ordonnance sur la planification et le financement hospitaliers (RS 810.20) | 2 | oldest version available, then each consolidated version: 1 January 2015 to 1 January 2018 |
| `810-40/` | Ordonnance sur l'Observatoire valaisan de la santé (RS 810.40) | 3 | oldest version available, then each consolidated version: 1 January 2015 to 1 January 2019 |
| `810-41/` | Ordonnance sur la statistique sanitaire cantonale (RS 810.41) | 1 | one version (the oldest available), 1 January 2015 |
| `810-800/` | Ordonnance sur l'organisation des secours sanitaires (RS 810.800) | 3 | oldest version available, then each consolidated version: 1 December 1996 to 1 January 2025 |
| `811-100-oex/` | Ordonnance sur l'exercice des professions de la santé (RS 811.100) | 6 | oldest version available, then each consolidated version: 1 January 2014 to 1 September 2023 |
| `811-102-osps/` | Ordonnance sur la surveillance des professions de la santé (RS 811.102) | 2 | oldest version available, then each consolidated version: 1 January 2021 to 1 March 2024 |
| `811-104/` | Règlement sur la formation continue obligatoire pour les professionnels de la santé (RS 811.104) | 1 | one version (the oldest available), 1 January 2020 |
| `811-200/` | Ordonnance sur les activités de santé publique déléguées par l'Etat (RS 811.200) | 2 | oldest version available, then each consolidated version: 1 January 2015 to 1 March 2022 |
| `811-300/` | Ordonnance sur la mise à disposition des places de stage et d’apprentissage pour les professions non universitaires de la santé (RS 811.300) | 3 | oldest version available, then each consolidated version: 1 August 2021 to 1 January 2026 |
| `811-900/` | Règlement de la Conférence suisse des directrices et directeurs cantonaux de la santé (CDS) concernant les émoluments pour l'examen intercantonal des ostéopathes (RS 811.900) | 1 | one version (the oldest available), 10 April 2014 |
| `812-200-opth/` | Ordonnance sur les produits thérapeutiques (RS 812.200) | 4 | oldest version available, then each consolidated version: 1 July 2009 to 1 May 2025 |
| `814-100-reie/` | Règlement sur l’examen des impacts sur l’environnement (RS 814.100) | 3 | oldest version available, then each consolidated version: 17 June 2016 to 1 September 2024 |
| `814-105/` | Règlement sur la gestion du fonds cantonal pour les investigations préalables des sites présumés pollués (RS 814.105) | 1 | one version (the oldest available), 5 January 2007 |
| `814-107/` | Règlement sur la gestion du fonds cantonal pour les mesures d'exécution par substitution en matière de protection de l'environnement (RS 814.107) | 1 | one version (the oldest available), 15 June 2012 |
| `814-200/` | Règlement concernant la procédure relative à la délimitation des zones et périmètres de protection des eaux souterraines, ainsi que des secteurs de protection des eaux superficielles (RS 814.200) | 1 | one version (the oldest available), 11 September 2015 |
| `814-700-olalrnis/` | Ordonnance concernant la loi d'application de la loi fédérale sur la protection contre les dangers liés au rayonnement non ionisant et au son (RS 814.700) | 1 | one version (the oldest available), 1 January 2026 |
| `817-101/` | Ordonnance concernant les installations d'alimentation en eau potable (RS 817.101) | 2 | oldest version available, then each consolidated version: 1 January 1993 to 1 February 2017 |
| `818-100/` | Ordonnance sur la lutte contre les maladies transmissibles (RS 818.100) | 1 | one version (the oldest available), 1 April 2016 |
| `818-120-ordonnance-fumee-passive-ofp/` | Ordonnance sur la protection de la population contre la fumée passive et l'interdiction de la publicité pour les produits du tabac, la cigarette électronique, la vaporette, le cannabis légal, les produits nicotiniques et autres produits à fumer (RS 818.120) | 3 | oldest version available, then each consolidated version: 1 January 2014 to 1 May 2025 |
| `818-400-ocd/` | Ordonnance sur la constatation des décès et les interventions sur les cadavres humains (RS 818.400) | 2 | oldest version available, then each consolidated version: 5 September 2014 to 1 January 2025 |
| `822-100-octr/` | Ordonnance cantonale sur le travail (RS 822.100) | 1 | one version (the oldest available), 1 October 2016 |
| `822-106-rpm/` | Règlement sur l'octroi de permis professionnels pour les conducteurs de machines de chantier (RS 822.106) | 2 | oldest version available, then each consolidated version: 1 April 2015 to 1 January 2025 |
| `822-200/` | Règlement d'exécution de la loi sur le repos du dimanche et des jours de fête (RS 822.200) | 1 | one version (the oldest available), 2 December 1966 |
| `822-201-rlom/` | Règlement concernant l'ouverture des magasins (RS 822.201) | 5 | oldest version available, then each consolidated version: 1 November 2002 to 1 March 2024 |
| `823-100/` | Ordonnance de la loi d'application de la loi fédérale sur les travailleurs détachés et de la loi fédérale sur le travail au noir (RS 823.100) | 2 | oldest version available, then each consolidated version: 1 October 2016 to 1 May 2021 |
| `823-102-omci/` | Ordonnance sur le moyen de contrôle individuel (RS 823.102) | 1 | one version (the oldest available), 1 January 2025 |
| `831-103/` | Règlement concernant la Caisse de compensation du canton du Valais et les agences locales AVS (RS 831.103) | 1 | one version (the oldest available), 1 January 2001 |
| `831-300-rpc/` | Règlement sur les prestations complémentaires à l'AVS/AI (RS 831.300) | 3 | oldest version available, then each consolidated version: 1 January 2015 to 1 January 2022 |
| `831-305-rmpc/` | Règlement relatif au remboursement des frais de maladie et des frais résultant de l'invalidité en matière de prestations complémentaires (RS 831.305) | 4 | oldest version available, then each consolidated version: 1 January 2014 to 1 January 2021 |
| `832-001-oalam/` | Ordonnance d'application sur la limitation de l'admission des médecins à facturer à la charge de l'assurance-maladie obligatoire (RS 832.001) | 6 | oldest version available, then each consolidated version: 1 July 2016 to 1 July 2026 |
| `832-100/` | Ordonnance désignant les autorités et les procédures en matière d'assurance maladie (RS 832.100) | 1 | one version (the oldest available), 1 January 2011 |
| `832-101/` | Ordonnance sur le fonds cantonal de secours en matière d'assurance-maladie (RS 832.101) | 1 | one version (the oldest available), 1 January 2001 |
| `832-102/` | Règlement concernant la composition et l'organisation du tribunal arbitral prévu à l'article 25 de la LAMA, ainsi que la procédure à suivre devant ce tribunal (RS 832.102) | 1 | one version (the oldest available), 1 January 1999 |
| `832-105-ocrip/` | Ordonnance concernant l'assurance-maladie obligatoire et les réductions individuelles des primes (RS 832.105) | 6 | oldest version available, then each consolidated version: 1 January 2017 to 1 May 2026 |
| `836-100-ocafam/` | Ordonnance cantonale sur les allocations familiales (RS 836.100) | 4 | oldest version available, then each consolidated version: 1 January 2013 to 1 January 2025 |
| `836-101-ocrafam/` | Ordonnance cantonale sur l'adaptation des montants des allocations familiales au renchérissement (RS 836.101) | 1 | one version (the oldest available), 1 January 2025 |
| `837-100-remc/` | Règlement sur l'emploi et les mesures en faveur des chômeurs (RS 837.100) | 1 | one version (the oldest available), 14 February 2014 |
| `837-101/` | Règlement fixant l'organisation et la gestion de la Caisse publique cantonale valaisanne de chômage (RS 837.101) | 2 | oldest version available, then each consolidated version: 8 July 2011 to 1 March 2017 |
| `841-100/` | Règlement d'exécution de la loi sur le logement (RS 841.100) | 1 | one version (the oldest available), 1 January 2006 |
| `850-60-odiph/` | Ordonnance sur les droits et l'inclusion des personnes en situation de handicap (RS 850.60) | 2 | oldest version available, then each consolidated version: 1 January 2008 to 1 January 2022 |
| `850-100-olias/` | Ordonnance sur l'intégration et l'aide sociale (RS 850.100) | 3 | oldest version available, then each consolidated version: 1 January 2016 to 1 October 2024 |
| `850-101-rfisp/` | Règlement d'utilisation du fonds cantonal pour l'intégration socio-professionnelle (RS 850.101) | 1 | one version (the oldest available), 1 October 2024 |
| `850-200/` | Règlement sur l'harmonisation du financement des régimes sociaux et d'insertion socio-professionnelle (RS 850.200) | 1 | one version (the oldest available), 1 January 2005 |
| `850-301-orace/` | Ordonnance sur le recouvrement et les avances de contributions d’entretien (RS 850.301) | 2 | oldest version available, then each consolidated version: 12 December 2012 to 1 January 2022 |
| `850-400-oje/` | Ordonnance sur les différentes structures en faveur de la jeunesse (RS 850.400) | 5 | oldest version available, then each consolidated version: 15 December 2016 to 1 January 2023 |
| `850-402-rdsje/` | Règlement sur les différentes structures en faveur de la jeunesse (RS 850.402) | 4 | oldest version available, then each consolidated version: 1 June 2001 to 1 September 2026 |
| `850-600/` | Règlement concernant l'octroi de subventions aux investissements en vertu de la loi sur l'intégration des personnes handicapées (RS 850.600) | 1 | one version (the oldest available), 11 February 1994 |
| `850-610/` | Ordonnance sur l'organisation et le fonctionnement de La Castalie (RS 850.610) | 2 | oldest version available, then each consolidated version: 15 February 2013 to 1 January 2022 |
| `857-100/` | Règlement de la législation fédérale et cantonale sur les centres de consultation en matière de grossesse (RS 857.100) | 1 | one version (the oldest available), 1 October 2001 |
| `900-101-opoleco/` | Ordonnance sur la politique économique cantonale (RS 900.101) | 1 | one version (the oldest available), 1 January 2001 |
| `900-120-romea/` | Règlement sur l'octroi de mesures exceptionnelles à des acteurs économiques touchés par des événements majeurs et imprévisibles, exogènes (RS 900.120) | 1 | one version (the oldest available), 4 December 2024 |
| `900-150/` | Ordonnance sur la création de la société de promotion du Valais (RS 900.150) | 1 | one version (the oldest available), 1 January 2013 |
| `901-100/` | Ordonnance sur la loi sur la politique régionale (RS 901.100) | 5 | oldest version available, then each consolidated version: 1 January 2014 to 1 January 2026 |
| `902-100-olerm/` | Ordonnance concernant la loi sur l’encouragement des remontées mécaniques (RS 902.100) | 1 | one version (the oldest available), 1 March 2019 |
| `902-110/` | Règlement sur le fonds cantonal pour les remontées mécaniques (RS 902.110) | 1 | one version (the oldest available), 1 September 2019 |
| `910-100-ocagr/` | Ordonnance sur l'agriculture et le développement rural (RS 910.100) | 3 | oldest version available, then each consolidated version: 1 January 2016 to 1 May 2019 |
| `910-102-omavv/` | Ordonnance sur la modernisation, l'adaptation et la valorisation du vignoble valaisan (RS 910.102) | 1 | one version (the oldest available), 1 January 2025 |
| `910-103-rtpma/` | Règlement fixant le tarif des prestations cantonales en matière agricole (RS 910.103) | 3 | oldest version available, then each consolidated version: 1 February 2017 to 1 May 2022 |
| `910-110-rfsra/` | Règlement sur le financement spécial pour risques météorologiques ou phytosanitaires en matière agricole (RS 910.110) | 1 | one version (the oldest available), 1 April 2024 |
| `916-142-ovv/` | Ordonnance sur la vigne et le vin (RS 916.142) | 5 | oldest version available, then each consolidated version: 1 January 2017 to 1 April 2026 |
| `916-148/` | Ordonnance sur l'authenticité du matériel végétal viticole valaisan (RS 916.148) | 1 | one version (the oldest available), 1 September 1999 |
| `916-340/` | Ordonnance portant exécution de la législation fédérale sur l'abattage d'animaux et le contrôle des viandes (RS 916.340) | 2 | oldest version available, then each consolidated version: 1 June 2005 to 1 March 2017 |
| `916-400/` | Ordonnance concernant l'élimination des sous-produits animaux (RS 916.400) | 1 | one version (the oldest available), 1 January 2017 |
| `916-472-reglement-sur-les-frais-veterinaires-rfv/` | Règlement fixant les frais et les indemnités dans le domaine vétérinaire (RS 916.472) | 3 | oldest version available, then each consolidated version: 1 January 2016 to 1 October 2022 |
| `921-100-ocfo/` | Ordonnance sur les forêts (RS 921.100) | 3 | oldest version available, then each consolidated version: 1 January 2013 to 1 August 2024 |
| `921-150/` | Règlement concernant la fonction et les tâches du garde forestier (RS 921.150) | 1 | one version (the oldest available), 1 January 2013 |
| `922-100-rexchp/` | Règlement d'exécution de la loi sur la chasse (RS 922.100) | 8 | oldest version available, then each consolidated version: 8 July 2016 to 1 July 2026 |
| `922-150/` | Règlement sur l'administration et l'utilisation du fond cantonal relatif au financement des dommages causés par la faune sauvage (RS 922.150) | 1 | one version (the oldest available), 1 October 2012 |
| `923-100-ocpe/` | Ordonnance sur l'exercice de la pêche (RS 923.100) | 4 | oldest version available, then each consolidated version: 1 January 2014 to 1 June 2023 |
| `923-150/` | Règlement sur l'administration et l'utilisation du fonds piscicole (RS 923.150) | 1 | one version (the oldest available), 1 June 2012 |
| `923-900/` | Règlement d'exécution du concordat intercantonal sur la pêche dans le lac Léman (RS 923.900) | 1 | one version (the oldest available), 1 January 2001 |
| `930-100/` | Ordonnance concernant la loi sur la police du commerce (RS 930.100) | 1 | one version (the oldest available), 1 January 2016 |
| `932-100-oprost/` | Ordonnance sur la prostitution (RS 932.100) | 1 | one version (the oldest available), 1 January 2016 |
| `935-100/` | Ordonnance concernant la loi sur le tourisme (RS 935.100) | 1 | one version (the oldest available), 1 January 2015 |
| `935-101/` | Ordonnance concernant une exonération de la taxe de séjour (RS 935.101) | 1 | one version (the oldest available), 1 November 1996 |
| `935-102/` | Règlement sur le fonds cantonal pour le tourisme (RS 935.102) | 1 | one version (the oldest available), 1 January 2016 |
| `935-200-ogar/` | Ordonnance sur les guides de montagne et les organisateurs d'autres activités à risque (RS 935.200) | 2 | oldest version available, then each consolidated version: 1 January 2014 to 1 September 2026 |
| `935-300-ohr/` | Ordonnance concernant la loi sur l'hébergement, la restauration et le commerce de détail de boissons alcoolisées (RS 935.300) | 3 | oldest version available, then each consolidated version: 1 January 2005 to 1 January 2025 |
| `935-505-obl/` | Ordonnance concernant l'attribution des bénéfices résultant des loteries (RS 935.505) | 3 | oldest version available, then each consolidated version: 1 July 2001 to 1 October 2026 |
| `935-506/` | Règlement concernant l’attribution annuelle des bénéfices résultant de la Loterie romande au fonds de secours du Conseil d’Etat (RS 935.506) | 3 | oldest version available, then each consolidated version: 1 July 2010 to 19 March 2021 |
| `935-509-reglement-sur-laide-durgence-pour-blatten/` | Règlement concernant la contribution de solidarité en faveur de la population, des entreprises et des sociétés locales de Blatten, à la suite de l’éboulement du 28 mai 2025 ainsi que l’octroi d’un crédit supplémentaire au budget 2025 pour le versement de 10 millions de francs d’aides dans le cadre de l’aide d’urgence pour Blatten (RS 935.509) | 1 | one version (the oldest available), 11 September 2025 |
| `935-520/` | Ordonnance concernant la répartition de la part du produit des jeux résultant de l'exploitation des maisons de jeu (RS 935.520) | 2 | oldest version available, then each consolidated version: 1 May 2003 to 19 March 2021 |
| `935-550-olaljar/` | Ordonnance concernant la loi d'application de la loi fédérale sur les jeux d'argent (RS 935.550) | 1 | one version (the oldest available), 21 May 2021 |
| `935-700-rfds/` | Règlement sur le Fonds du Sport (RS 935.700) | 4 | oldest version available, then each consolidated version: 1 January 2014 to 1 December 2023 |
| `935-701-rfdna/` | Règlement concernant l'utilisation des fonds mis à disposition par la Loterie de la Suisse romande en vue de venir en aide aux victimes de dommages non assurables causés par les forces de la nature (RS 935.701) | 4 | oldest version available, then each consolidated version: 28 April 2006 to 9 December 2022 |
| `935-703/` | Règlement fixant les modalités d'attribution d'aides financière du fonds du sport aux centres de sports à caractère national (RS 935.703) | 1 | one version (the oldest available), 1 January 2009 |
| `941-4/` | Ordonnance d'exécution de la loi fédérale et de l'ordonnance sur les substances explosibles (RS 941.4) | 2 | oldest version available, then each consolidated version: 25 August 1993 to 1 February 2017 |
| `941-200/` | Ordonnance concernant la loi d'application de la loi fédérale sur la métrologie (RS 941.200) | 1 | one version (the oldest available), 1 January 2006 |

## Source

The RS (systematic collection) of the canton, published by the canton at <https://lex.vs.ch/>. For each act it gives every consolidated version it holds, with the day each version took effect, and a change table listing each amendment: its decision date, the day it took effect, the provision it touched and its entry in the chronological collection (RCV). Annexes the collection publishes only as separate PDF files are not included.

## Dates

- Each commit is dated at **noon, Europe/Zurich, on the day the version took effect**, as the collection gives it ("in Kraft seit / von"). The decision date of each amending act is the `Enacted:` trailer.
- An act's first commit is its oldest version in the collection. It is credited to the act as enacted only when the change table shows no amendment in force before it; otherwise it is the "oldest version available", naming the earlier amendments.
- Versions that take effect after the retrieval day are on the `futur` branch, never merged into `main`.
- `--before="YYYY-MM-DD"` alone uses your clock's time of day; use `T23:59:59Z` or `tools/on.py`.

## Files

`<act>/art-005.md` is Art. 5 (or § 5), `art-005a.md` Art. 5a; `ingress.md` holds the title, date and preamble; `gliederung.md` the section headings; `schluss.md` the closing formula and signatures. One paragraph or list item per line. Amendment markers (`*`), footnote numbers and the "Stand" date are left out.

## How it is checked

- Every version of every act is read back from git on the day it took effect and on the day before (`tools/check_repo.py`); both must match `corpus.json`.
- The letters and digits of every version equal those of the canton's own text of that version, and every article's text appears in it in order.
- Health checks: no merge commits, commit dates never go backwards, nothing dated in the future, and every commit's trailers parse.

## What "author" means

The author of a commit is the amending act, named by its entry in the chronological collection (RCV), with an e-mail address that cannot exist (`<act key>@lex.vs.ch.invalid`). Where one version holds changes by several amending acts and the change table does not say which provision each one touched, the commit names them all. The committer is always Lexifina.

## Limits

This is not an official publication. The binding text is the one the canton publishes as binding (its chronological collection, or its systematic collection where cantonal law makes that binding). The history starts with the oldest consolidated version the collection holds for each act, which for many acts is later than the act's enactment. Only the acts listed above are included.
