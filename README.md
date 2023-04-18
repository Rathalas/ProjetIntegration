# ProjetIntegration

Pour débuter, mettre le contenu du projet dans un catkin workspace.\

Dans src se trouve le paquet hc10, contenant tous les fichiers générés par moveit assistant, à partir des fichiers urdf se trouvant dans motoman/motoman_hc10_support.\

Configurer l'environnement en écrivant :
```
. devel/setup.bash
```
Se placer dans le catkin workspace et écrire :
```
roslaunch hc10 demo_gazebo.launch.
```

Dans un second terminal, écrire :
```
python3 src/hc10/scripts/move_robot.py"
```
La simulation devrait se dérouler dans RViz, démontrant l'acquisition du cube par un nuage de points.
