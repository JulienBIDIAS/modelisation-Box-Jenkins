# Box-Jenkins-modelisation

# Dynamique du PIB camerounais : approche par la méthode de Box-Jenskins

Le recours aux techniques de traitement via l’économétrie des séries temporelles permet
de retracer la dynamique de plusieurs phénomènes supposés se répéter dans les mêmes conditions.
Les séries temporelles (ou séries chronologiques) portent donc sur l’analyse statistique
et probabiliste d’observations ordonnées chronologiquement. Cela permet de justifier l’étude à
travers le temps de l’évolution du PIB camerounais par ces mêmes techniques. L’objectif étant
de pouvoir à travers une analyse, une modélisation rigoureuse caractériser ou définir le modèle
qui permet aux mieux d’expliquer les périodes de fortes hausses et les périodes de fortes baisses
de ce dernier. En outre, les modèles ne sont pas conçus pour refléter la réalité à 100% mais pour
la décrire, prévoir le phénomène étudié dans le futur. C’est ainsi qu’il existe une kyrielle de
modèles abondant dans la littérature. Dès lors, on peut donc s’interroger directement sur quel
modèle choisir ?


En analyse univariée, l’on considère le plus souvent qu’un phénomène présent peut dépendre
dans le futur de ses valeurs passées : il s’agit des processus autorégressifs (AR1). Ou encore,
de ses perturbations antérieures : il s’agit des processus moyennes mobiles (MA2). Enfin, le
processus peut être une combinaison des deux (ARMA) et présenter dans un cas bien précis une
saisonnalité on parlera de modèles ARIMA. Cette typologie de modèles fera donc l’objet de cette
section dans laquelle nous choisirons à travers l’inférence statistique celui adéquat, permettant
d’expliquer les fluctuations de croissance du PIB du Cameroun de la période 1970 à 2020 et
aussi de pouvoir se prononcer en termes de perspectives.

# Approche méthodologique

L’approche retenue pour étudier notre série et choisir donc le bon modèle porte essentiellement
sur celle de Box-Jenskins (1976) compléter par Anderson (1977), Ljung et Box (1978),
Roy (1982). La méthode se décompose en 7 étapes (Anderson, 1977) :

- familiarisation avec les données,
- analyse préliminaire,
- identification ou spécification du modèle,
- estimation des paramètres,
- validation par tests ou test d’adéquation du modèle,
- prévision,
- interprétation des résultats.


# Présentation des données

Les données mobilisées dans le cadre de notre étude proviennent du site du groupe la Banque
Mondiale. Il s’agit des taux de croissance du PIB réel de la période 1976 à 2020. Il s’agit donc
de données quantitatives, positives ou négatives et indexées par le temps. La série ne
présentent aucune valeur manquante. Les taux de croissance des années 2021 et 2022 sont 
déjà connus et valent respectivement 3,6% et 3,5% selon la Banque Mondiale. 
Ainsi, nous travaillerons avec nos données sur la période 1976 à 2020, ensuite nous 
fournirons des estimations du taux de croissance du PIB camerounais pour
les années ultérieures.
