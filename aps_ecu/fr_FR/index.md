# Plugin APS ECU

# Description
Ce plugin permet de récupérer les données d'un ECU APSystems en temps réel.

# Pré-requis
Ce plugin nécessite le module sockets php pour se connecter à l'ECU.

# Utilisation
Entrez l'IP locale de l'ECU et son port qui par défaut est 8899 dans l'équipement. Sauvegardez et l'équiment va être créée avec les commandes correpondant au type d'ECU et d'onduleurs détéctés.

## Commandes disponibles

* Energie Totale : Energie totale produite depuis la mise en service
* Energie Aujourd'hui : Energie produite le jour courant
* Puissante importée courante : Puissance importée du réseau (seulement sur les ECU-C avec les pinces ampèremétriques branchées et activées)
* Puissance Courante : Puissance totale produite actuellement

Pour chaque onduleur :

* En Ligne : L'onduleur est en ligne et communique avec l'ECU
* Fréquence : Fréquence du réseau
* Température : Température de l'onduleur
* Signal Radio : Qualité du signal radio avec l'onduleur
* Puissance Totale : Puissance Totale produite actuellement par l'onduleur
* Puissance : Puissance produite actuellement pour chaque module connecté à l'onduleur
* Tension : Tension du réseau

## Attention
*Les valeurs de puissance maximum ne peuvent être détéctés automatiquement avec l'ECU. Vous devez entrer manuellement chaque valeur pour chaque onduleur et chaque module photovoltaïque.*
