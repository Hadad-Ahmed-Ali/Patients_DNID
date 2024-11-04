                                       Modéliser le suivi biologique des patients DNID pour
                                       déterminer des sous- populations de patients à partir
                                       de leur observance du suivi biologique

Le diabète est une maladie chronique, touchant 3,5 millions de personnes en France. Elle est très couteuse et génère de très graves complica tions qui pourraient être évitables. 
D’après plusieurs études réalisées, l’observance des patients est proche de 40% et le niveau de suivi biologique est également très faible.

Dans le cadre de mon stage en tant que Data Analyst chez Quanti Health, sous la supervision de Mme Dabo, data analyste et chercheuse en statistique inférentielle à l'Université de Lille 1, j'ai travaillé sur la modélisation du suivi biologique des patients diabétiques. Mon objectif était d'identifier des sous-populations de patients en fonction de leur observance médicale, en utilisant des techniques de machine learning pour le partitionnement.

Les techniques de partitionnement que j'ai appliquées sont les suivantes :

 **- Classification Ascendante Hiérarchique (CAH)**
 
 **- K-means**

Avant d'appliquer ces méthodes, j'ai effectué une étude préliminaire de nettoyage des données pour garantir la qualité des informations utilisées. Ensuite, j'ai réalisé des analyses descriptives afin de mieux comprendre l’évolution médicale, le suivi des patients, ainsi que d'autres caractéristiques spécifiques.

Pour gérer la grande quantité de données et réduire le nombre de variables, j'ai utilisé une analyse factorielle afin de synthétiser les variables en axes factoriels. Cela m'a permis de simplifier l'analyse tout en conservant l'essentiel des informations pertinentes.

Les résultats de mes analyses nous ont permis de mieux comprendre les tendances d'observance médicale des patients. J'ai également rédigé un rapport à destination des médecins, détaillant et caractérisant les sous-populations identifiées à l'issue de l'analyse.


                                       Conclusion

Dans cette analyse des patients diabétiques, on constate que le diabète touche principalement les hommes, surtout les personnes nées aux années 60 à 80. Pour former des groupes de patients similaires, nous avons appliqué deux méthodes principales :
la CAH et le Clustering K-means. Voici les principales conclusions :

Classification Ascendante Hiérarchique (CAH) :
Trois groupes (K=3) ont offert la meilleure structure en termes de cohésion et de séparation des données. En appliquant la CAH avec trois groupes, nous avons observé une répartition équilibrée entre les patients avec un diabète contrôlé et non contrôlé dans chaque groupe. Le groupe 2 s’est distingué par le plus grand nombre de patients, tandis que le groupe 1 s’est distingué par le plus faible nombre de patients. Quant à la contribution des variables, le taux d’ALAT a été identifié comme la variable la plus contributive pour le partitionnement, surtout dans le groupe 3.

Clustering K-means :
Quatre groupes (K=4) ont offert la meilleure structure en termes de cohésion et de séparation des données. En appliquant K-means avec quatre groupes, nous avons observé une répartition distincte des patients. Notamment, le groupe 3 était composé uniquement de patients avec un diabète non contrôlé. Quant à la contribution des variables, le taux d’ALAT a été la variable la plus contributive dans les groupes 1, 2 et 4, tandis que le taux de HbA1c était plus contributif dans le groupe 3.

En conclusion, les deux méthodes ont leurs avantages spécifiques. La CAH, avec la méthode de Ward, offre des clusters bien définis et compacts, tandis que K-means peut identifier des sous-groupes distincts avec des caractéristiques médicales spécifiques. En examinant la visualisation des clusters formés par les deux méthodes dans l’espace 3D formé par HbA1c (%), ALAT (UI/L) et ASAT(UI/L), la CAH semble fournir le meilleur partitionnement.

