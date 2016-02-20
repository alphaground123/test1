# Simulateur de chute de particules

Le simulateur de chute de particules considère autant de particules que l'utilisateur aura décidé de mettre.

Le programme demande à l'utilisateur de saisir d'abord les propriétés de la simulation puis, les propriétés de la particle.
Les propriétés de la simulation sont :
- le nombre de particules
- le temps total de la simulation
- le pas de temps de la simulation

Les propriétés de la particle sont :
- le rayon de la particle
- la masse de la particle
- le coefficient de restitution à l'impact
- le coefficient de frottement
- sa position initiale
- sa vitesse initiale

Une fois, que le programme a saisi toutes les données, il va calculer toutes les positions en x, y et z de la particle en fonction du temps. 
Les positions x, y et z de chaque particle sont stockées dans des fichiers .data qui sont créés automatiquement et des commandes gnuplot sont générées
dans le fichier 'positions.plt' qui sera créé automatiquement. 

[![solarized dualmode](https://github.com/altercation/solarized/raw/master/img/solarized-yinyang.png)](#features)

![alt tag](http://www.hostingpics.net/viewer.php?id=132839cinqparticules.png][IMG]http://img15.hostingpics.net/pics/132839cinqparticules.png)
