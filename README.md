################################################################################
################################################################################

This package contains data from:

################################################################################

Rehling et al. (2023):
Wind turbines in managed forests partially displace common forest birds
doi: https://doi.org/10.1016/j.jenvman.2022.116968

################################################################################

The package contains one data file, each in .rds and .csv format, that was used in the analyses 
of the above-mentioned publication.

The structures of the data files are listed below with detailed descriptions of their contents.

################################################################################

1. Rehling2023_birds.csv
Point counts of local bird communities along an distance gradient from a wind turbine across 
24 temperate forests in Hesse (Germany). This data also contain information on season, 
forest structure, wind turbine characteristics, and counts of birds at the study sites and 
point count locations.

'data.frame':	863 obs. of  59 variables:
 $ plot                : Factor, ID for study sites
 $ distance            : integer, distance of point counts from wind turbine
 $ year                : Factor, study year
 $ month               : Factor, study period within year
 $ Amsel               : integer, counts of 'Turdus merula'
 $ Baumpieper          : integer, counts of 'Anthus trivialis'
 $ Bergfink            : integer, counts of 'Fringilla montifringrilla'
 $ Blaumeise           : integer, counts of 'Cyanistes caeruleus'
 $ Buchfink            : integer, counts of 'Fringilla coelebs'
 $ Buntspecht          : integer, counts of 'Dendrocopos major'
 $ Eichelhaeher        : integer, counts of 'Garrulus glandarius'
 $ Erlenzeisig         : integer, counts of 'Spinus spinus'
 $ Fichtenkreuzschnabel: integer, counts of 'Loxia curvirostra'
 $ Fitis               : integer, counts of 'Phylloscopus trochilus'
 $ Gartenbauml.ufer    : integer, counts of 'Certhia brachydactyla'
 $ Gartengrasm.cke     : integer, counts of 'Sylvia borin'
 $ Gimpel              : integer, counts of 'Pyrrhula pyrrhula'
 $ Goldammer           : integer, counts of 'Emberiza citrinella'
 $ Grauschnaepper      : integer, counts of 'Muscicapa striata'
 $ Gruenfink           : integer, counts of 'Chloris chloris'
 $ Gruenspecht         : integer, counts of 'Picus viridis'
 $ Haubenmeise         : integer, counts of 'Lophophanes cristatus'
 $ Heckenbraunelle     : integer, counts of 'Prunella modularis'
 $ Hohltaube           : integer, counts of 'Columba oenas'
 $ Kernbeisser         : integer, counts of 'Coccothraustes coccothraustes'
 $ Kleiber             : integer, counts of 'Sitta europaea'
 $ Kohlmeise           : integer, counts of 'Parus major'
 $ Maeusebussard       : integer, counts of 'Buteo buteo'
 $ Misteldrossel       : integer, counts of 'Turdus viscivorus'
 $ Moenchsgrassmuecke  : integer, counts of 'Sylvia atricapilla'
 $ Rabenkraehe         : integer, counts of 'Corvus corone'
 $ Ringeltaube         : integer, counts of 'Columba palumbus'
 $ Rotdrossel          : integer, counts of 'Turdus iliacus'
 $ Rotkehlchen         : integer, counts of 'Erithacus rubecula'
 $ Schwanzmeise        : integer, counts of 'Aegithalos caudatus'
 $ Schwarzspecht       : integer, counts of 'Dryocopus martius'
 $ Singdrossel         : integer, counts of 'Turdus philomelos'
 $ Sommergoldhaenchen  : integer, counts of 'Regulus ignicapilla'
 $ Sperber             : integer, counts of 'Accipiter nisus'
 $ Sperlingskauz       : integer, counts of 'Glaucidium passerinum'
 $ Star                : integer, counts of 'Sturnus vulgaris'
 $ Sumpfmeise          : integer, counts of 'Poecile palustris'
 $ Tannenmeise         : integer, counts of 'Periparus ater'
 $ Waldbaumlaeufer     : integer, counts of 'Certhia familiaris'
 $ Waldlaubsaenger     : integer, counts of 'Phylloscopus sibilatrix'
 $ Weidenmeise         : integer, counts of 'Poecile montanus'
 $ Wintergoldhaenchen  : integer, counts of 'Regulus regulus'
 $ Zaunkoenig          : integer, counts of 'Troglodytes troglodytes'
 $ Zilpzalp            : integer, counts of 'Phylloscopus collybita'
 $ shannon             : numeric, Shannon-Weaver-Index for vertical heterogeneity in vegetation
 $ rotordiameter       : numeric, diameter of rotor blades [m]
 $ heightturbines      : numeric, height of turbines [m]
 $ numberturbines      : integer, number of turbines at a study site
 $ ageturbines         : numeric, age since construction of turbines
 $ forestcomp          : numeric, fraction of coniferous trees in forest
 $ abundance           : integer, total number of birds
 $ diversity           : numeric, species richness of birds
 $ lgstand.age         : numeric, log10-diameter at breast height (DBH) of trees at a point count location
 $ wea_ja              : Factor, operation status of wind turbines 'ja' - yes, 'nein' - no
