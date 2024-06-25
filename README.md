                                       Modéliser le suivi biologique des patients DNID pour
                                       déterminer des sous- populations de patients à partir
                                       de leur observance du suivi biologique

Le diabète est une maladie chronique, touchant 3,5 millions de personnes en France. Elle est très couteuse et génère de très graves complica tions qui pourraient être évitables. 
D’après plusieurs études réalisées, l’observance des patients est proche de 40% et le niveau de suivi biologique est également très faible.

Nous cherchons à modéliser le suivi biologique des patients DNID du laboratoire QuantiHealth et de déterminer des sous-populations de patients (en utilisant des méthodes de partitionnement) à partir de leur observance du suivi biologique. Pour modéliser le suivi biologique et déterminer d’avantage des sous-populations de patients, nous
parcourons trois parties :


→ Etude des observance pour comprendre l’evolution, le suivi médicale, des patients.

→ Méthode de partitionnement : Classification Ascendante Hiérarchique (CAH).

→ Méthode de partitionnement : K-means.



                                       Conclusion

Les méthodes de partitionnement sont des outils puissants pour regrouper des patients en fonctionde leurs observances médicales. Dans cette analyse des patients diabétiques, on constate que le diabète
touche principalement les hommes, surtout les personnes nées aux années 60 à 80. Pour former des groupes de patients similaires, nous avons appliqué deux méthodes principales :
la CAH et le Clustering K-means. Voici les principales conclusions :

Classification Ascendante Hiérarchique (CAH) :
Trois groupes (K=3) ont offert la meilleure structure en termes de cohésion et de séparation des données. En appliquant la CAH avec trois groupes, nous avons observé une répartition équilibrée entre les patients avec un diabète contrôlé et non contrôlé dans chaque groupe. Le groupe 2 s’est distingué par le plus grand nombre de patients, tandis que le groupe 1 s’est distingué par le plus faible nombre
de patients. Quant à la contribution des variables, le taux d’ALAT a été identifié comme la variable la plus contributive pour le partitionnement, surtout dans le groupe 3.

Clustering K-means :
Quatre groupes (K=4) ont offert la meilleure structure en termes de cohésion et de séparation des données. En appliquant K-means avec quatre groupes, nous avons observé une répartition distincte
des patients. Notamment, le groupe 3 était composé uniquement de patients avec un diabète non contrôlé. Quant à la contribution des variables, le taux d’ALAT a été la variable la plus contributive dans les groupes 1, 2 et 4, tandis que le taux de HbA1c était plus contributif dans le groupe 3.

En conclusion, les deux méthodes ont leurs avantages spécifiques. La CAH, avec la méthode de Ward, offre des clusters bien définis et compacts, tandis que K-means peut identifier des sous-groupes
distincts avec des caractéristiques médicales spécifiques. En examinant la visualisation des clusters formés par les deux méthodes dans l’espace 3D formé par HbA1c (%), ALAT (UI/L) et ASAT
(UI/L), la CAH semble fournir le meilleur partitionnement.

