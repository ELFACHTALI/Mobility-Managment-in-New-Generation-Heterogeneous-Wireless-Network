# Gestion de la Mobilité dans les réseaux hétérogènes de nouvelles générations

Ce projet présente les résultats de simulations des trois schémas de décision de transfert vertical que nous avons proposés pour optimiser l'efficacité du processus de transfert vertical dans les réseaux sans fil hétérogènes de nouvelles générations. Des versions améliorer des algorithmes de colonie de fourmis pour les domaines continus (ACOR) et de recherche tabou (Tabu-search) ainsi qu’une version d’ACOR avec adaptation de l’évaporation de la phéromone (ACOR APER) pour l’estimation de nécessité de transfert, la sélection de cible de transfert et la prise de décision du transfert.

Pour le schéma de mobilité basé sur ACOR : 

Nous avons utilisé MATLAB pour simuler 1000 trajectoires aléatoires dans la zone de couverture de cellules WLAN. Pour chaque trajectoire, 10, 20, 50 et 100 nouvelles solutions (les solutions représentent les cellules WLAN disponibles) sont également générées avec des trajectoires aléatoires (un angle aléatoire entre 0 et 2π a été généré représentant la direction de mouvement du terminal mobile), pour des vitesses allant de 1 km/h à 120 km/h avec un incrément de 1 km/h. des tailles différentes (de 10 à 100) de la table d'archivage sont choisies (cela signifie que nous pouvons avoir ce nombre de solutions dans la base de données).

Dans la fonction de calcul des coûts utilisée dans notre algorithme basé sur ACOR, nous considérons cinq paramètres qui sont l’RSS, la sécurité, la consommation d'énergie, le coût monétaire et la bande passante comme entrées.

Les images représentant les résultats de simulation pour ACOR commencent avec "ACOR".

Pour plus d'information : Imad El Fachtali, Rachid Saadane, Mohammed Elkoutbi:
Vertical Handover Decision Algorithm Using Ants' Colonies for 4G Heterogeneous Wireless Networks. Journal Comp. Netw. and Communic. 2016: 6259802:1-6259802:15 (2016)

Pour le schéma de mobilité basé sur Tabu-search : 

MATLAB a été utilisé pour simuler 1000 trajectoires aléatoires dans la zone de couverture de la cellule WLAN. Pour chaque trajectoire, 50 solutions (les solutions représentent les cellules WLAN disponibles) sont générées avec des trajectoires aléatoires (un angle aléatoire entre 0 et 2π a été généré représentant la direction du mouvement du terminal mobile) pour des vitesses de 1 km/h à 120 km/h avec des incréments de 1 km/h. vingt étapes (itérations) sont réalisées dans chaque simulation où nous mettons à jour les valeurs d'angles, d’RSS et de coûts, mais nous conservons les valeurs des Id des solutions et la bande passante.

La taille initiale de la liste des valeurs autorisées "allowed set" est de 50 alors que  0 est la taille de la liste de solutions taboues ‘Tabu list’, cela signifie que toutes les solutions sont autorisées dans la première itération.

Les images représentant les résultats de simulation pour Tabu-search commencent avec "Tabu search".

Pour plus d'information : Imad El Fachtali, Rachid Saadane, Mohammed El Koutbi, Hasna Chaibi:
Power-optimized vertical handover scheme for 4th generation heterogeneous wireless network. CIST 2016: 824-829


Pour le schéma de mobilité basé sur ACOR avec adaptation de l'évaporation de la phéromone :

Nous avons simulé 1000 trajectoires aléatoires dans la zone de couverture des cellules WLAN en utilisant MATLAB comme pour les simulations ACOR originales. Pour chaque trajectoire, 10, 20, 50 et 100 nouvelles solutions (les solutions représentent les cellules WLAN disponibles) sont également générées avec des trajectoires aléatoires (un angle aléatoire entre 0 et 2π est généré représentant la direction de mouvement du terminal mobile ‘MT’), pour des vitesses allant de 1 km/h à 120 km/h avec un incrément de 1 km/h. Différentes tailles (de 10 à 100) de la table d'archivage des solutions sont choisies (cela signifie que nous pouvons maintenir ce nombre de solutions dans la base de données).
Dans les simulations, nous comparons le schéma original basé sur ACOR aux deux schémas basés sur ACOR  APER et ACOR  LPER.

Les images représentant les résultats de simulation pour ACOR avec adaptation de l'évaporation de la phéromone commencent avec "ACOR APER".

Pour plus d'information : Improved vertical handover decision algorithm using ants' colonies with adaptive pheromone evaporation rate for 4th generation heterogeneous wireless networks. IJWMC 12(2): 154-165 (2017)





