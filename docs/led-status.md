## Séquence LED au démarrage du Reach

Au démarrage, le module Reach traverse 3 phases:

* Recherche réseau
* Synchronisation temporelle
* Démarrage de ReachView

### Recherche réseau

Le module Reach indique la recherche réseau par un clignottement <font color="yellow">jaune</font>. Si un réseau Wi-Fi connu est détecté, le module Reach s'y connectera et la LED devient <font color="blue">bleue</font>. Si aucun réseau connu n'est détécté, un point d'accès Wi-Fi est démarré et la LED devient <font color="green">verte</font>.

### Synchronisation temporelle

La synchronisation temporelle est indiquée par un clignottement <font color="magenta">magenta</font>. Ils sont ajoutés aux autres indications de recherche de réseau. Cela signifie qu'un synchronisation temporelle en cours alors que le point d'accès Wi-Fi est démarré affichera des clignottements <font color="green">verts</font>/<font color="magenta">magenta</font> et la synchronisation temporelle après avoir rejoint un réseau Wi-Fi connu affichera des clignottements <font color="blue">bleus</font>/<font color="magenta">magenta</font>.

### Démarrage de ReachView

!!! note
    L'application ne démarre pas tant que la synchronisation temporelle n'est pas effectuée. Une connexion internet assure cela automatiquement, mais en mode point d'accès Wi-Fi le module Reach nécessite une antenne connectée et une certaine visibilité satellite.

Une fois la synchronisation temporelle terminée les clignottements <font color="magenta">magenta</font> s'arrêtent et ReachView démarre. Une démarrage réussi sera indiqué par une couleur <font color="green">verte</font>, alors qu'une erreur sera indiquée en <font color="red">rouge</font>.

**Les statuts des LED donneront plus d'indications sur les interactions et informations dans l'une des prochaines mises à jour.**
