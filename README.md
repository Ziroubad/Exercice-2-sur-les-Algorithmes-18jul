# Exercice-2-sur-les-Algorithmes-18jul
Exercice sur les algorithmes
Comptant pour 10 % de la note finale
Exercice
À partir de la liste (8) des problèmes énoncés, en utilisant du pseudocode, veuillez réaliser individuellement les algorithmes qui permettent de résoudre les problèmes suivants :
Critère de correction
Qualité de la démonstration et précision dans les calculs.
1. Établir la paye hebdomadaire d’un employé :
Considérant que :
 Un commis gagne 12,50$ /h
 Ce taux est majoré de 20% pour les heures cumulées au-delà de 40 h et 50% pour les heures cumulées au-delà de 50 h
 Le taux de base des commis est majoré de 1$ le dimanche
Et que :
 Un assistant gérant gagne 15,50$ /h
 Ce taux est majoré de 30% pour les heures cumulées au-delà de 42 h et 1.45 pour les heures cumulées au-delà de 48 h
 Le taux de base des commis est majoré de 2$ Le vendredi soir, le samedi soir et le dimanche
 Le taux de base des assistant gérant du département C, est majoré de 10%
Ainsi que :
 Un gérant gagne 26,00$ /h
 Le gérant obtient un boni hebdomadaire de 150,00$ lorsque celui-ci a travaillé le vendredi, le samedi et le dimanche.
Truc : pour créer le code nécessaire à ce traitement, il est recommandé de passer à la fonction le temps de travail fait par l’employé pour chaque jour de la semaine individuellement.
2. Calculer combien gagnera un cueilleur de fruits
Considérant que :
 L’employé fera la cueillette de fraises le matin et de framboises l’après-midi
 Les fraises cueillies rapportent 1,35$ le kilo. L’employé gagne un bonus de ,25$ le kilo s’il a cueilli plus de 12 kilos dans l’avant-midi
 Les framboises cueillies rapportent 4,35$ le kilo. L’employé gagne un bonus de ,95$ le kilo s’il a cueilli plus de 5 kilos dans l’après-midi
 L’employé recevra un boni de 25,00$ s’il a atteint les deux bonis la même journée
3. Combien aura accumuler une personne ?
Considérant qu’on lui donne 0,01$ le premier jour, qu’on double ce montant le lendemain, qu’on double à nouveau le montant le sur lendemain et ainsi de suite pour un total de 30 jours.
4. Combien de jour seront nécessaires pour parcourir une distance réelle de 50 km à voile ?
Considérant que le bateau navigue 3 kilomètres par jour mais qu’un courant contraire le faire reculer de x kilomètres par jour où x est inférieur à 3.
5. Combien de spectacles un artiste devra-t-il faire dans sa tournée
Considérant que :
 Les billets se vendent 50$
 Qu’il doit verser 5$ par billet vendus (2000) pour la location des salles
 Qu’à chaque concert, il recevra les pleines recettes de 2000 billets
 Qu’entre chaque déplacement de ville en ville, il a des frais de 10 000$ incluant le déplacement vers son premier spectacle
 Qu’il fera deux spectacles dans la même ville avant de se déplacer
 Que la sonorisation, la sécurité, les techniciens et autre lui coûte 35 000$ par soir de spectacle
 Que son gérant lui charge 10% des recettes de chaque spectacle après réduction des dépenses de sonorisation, sécurité et de technique
 Qu’il souhaite avoir un jour de repos à tous les deux jours (donc 2 jours de spectacle puis un jour de repos). Cette séquence sera appelée un cycle.
 Qu’il a des frais fixes par jour de 20 000 $ par jour de spectacle et de 10 000 $ par jour de repos afin de payer ses musiciens et l’hébergement
 Et qu’il souhaite accumuler au moins 1 000 000$ de profit
 Lorsqu’il aura atteint son objectif, il complètera le cycle (2 jours de spectacle + 1 jour de congé) débuté.
Pour obtenir ce résultat, prendre en considération qu’aucune variable sera passée et que seuls de constantes doivent être prises en considération. De plus, il serait recommandé d’utiliser une boucle basée sur un cycle de 3 jours.
6. Selon les données du problème précédent, combien l’artiste aura t’il accumuler après x jour de sa tournée ?
Pour obtenir ce résultat, il est recommandé d’utiliser la fonction modulo pour établir le traitement à faire à chaque jour calculé.
https://fr.wikipedia.org/wiki/Modulo_(op%C3%A9ration)
7. Calculer le prix d’un item
Considérant que :
 L’item coûte 1,13$ le cm2 s’il est fait d’aluminium
 L’item coûte 0,86$ le cm2 s’il est fait d’acier
À cela s’ajoute :
 Le prix de l’item est multiplié par la somme de 1 + Le nombre de couleur de l’item divisé par 5
À cela s’ajoute :
 0,044$ du cm2 si l’item est recouvert d’une pellicule protectrice de type A
 0,052$ du cm2 si l’item est recouvert d’une pellicule protectrice de type B
8. Quelle distance pourra être parcouru par un camion de livraison
Considérant que
 Le camion consomme en moyenne 12 litres à tous les 100 km lorsqu’il est vide
 Chaque 500 kilos de marchandise augmente la consommation du camion de 2 litres à tous les 100 kilomètres
 Le budget pour l’essence est de 1200$
 Le conducteur A, plus nerveux, fait augmenter la consommation moyenne de 1 litre à tous les 100 kilomètres
 Le conducteur B, plus calme, fait diminuer la consommation moyenne de 0,5 litre à tous les 100 kilomètres
 Le poids de la cargaison sera fixe durant tout le parcours
 Le prix de l’essence demeurera fixe durant tout le parcours
 Le conducteur sera la même pour tout le parcours
 Tout autre facteur n’aura pas d’impact sur la consommation du véhicule
