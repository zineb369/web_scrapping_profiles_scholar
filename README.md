# web_scrapping_profiles_scholar
web scrapping authors profiles in google scholar using python

dans le fichier scrapping_profiles_json.ipynb est le fichier jyputer notebook pour le web scrapping de 20 profiles de chercheurs sur google scholar
le resultat est en format json dans le fichier profiles_json.json

le fichier scrapping_profils_googlescholar_acp-ipynb est le notebook qui contient le code python pour le web scrapping de donnees quantitatives des profiles dans google scholar afin d'appliquer la methode d'analyse en composntes principales

le resulats est stocke dans le fichier excel resultats_scrapping_acp.xlsx



# Explication de choix de methode d'analyse de donnees:

L'ACP peut vous aider à identifier des tendances globales dans les profils académiques, à repérer des chercheurs similaires, et à évaluer la contribution relative de différentes métriques à la performance académique. Elle offre également la possibilité de réduire la complexité des données tout en conservant l'essentiel de l'information.

Dans le contexte des profils académiques fournis, l'ACP peut être appliquée aux différentes métriques telles que le H indice, le nombre de citations, et d'autres indicateurs de performance. Voici comment vous pourriez procéder :

Prétraitement des données :

Organisez les données de manière à avoir un tableau avec les individus en lignes (chercheurs) et les variables en colonnes (métriques telles que le H indice, le nombre de citations, etc.).
Standardisation des données :

Standardisez les données si les échelles des différentes métriques sont différentes. Cela permet d'attribuer des poids égaux à toutes les variables lors de l'analyse.
Application de l'ACP :

Utilisez un outil ou une bibliothèque statistique pour appliquer l'ACP aux données standardisées.
Interprétation des composantes principales :

Analysez les composantes principales pour identifier les variables qui contribuent le plus à chaque composante. Cela peut vous aider à comprendre quelles métriques sont les plus importantes dans la caractérisation des chercheurs.
Visualisation des résultats :

Créez des visualisations, telles que des graphiques en nuage de points des individus, pour mieux comprendre les relations entre les chercheurs et les métriques.
