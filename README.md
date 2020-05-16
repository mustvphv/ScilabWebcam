# ScilabWebcam

# Traitement du signal et des images 
## Application filtres d’images et détection d’images différentes avec webcam 




## Introduction:

Pour pouvoir faire le projet, on applique plusieurs filtres avec des images
ou grâce à la webcam. On applique aussi une détection entre deux
images pour voir si il y’a eu un fort changement entre les deux images,
pour cela on applique un seuil de 3000 différences pour que le
programme puisse détecter la différence entre les deux images.

Toutefois, il faut distinguer les différences négligeables (qui ne sont pas
dû à la résolution de la webcam par exemple) et les différences
importantes (comme le passage d’une main ou d’un bras devant la
webcam), c’est pour cela qu’on à créer un seuil.

Dans l’interface graphique créée avec GUI Builder avec on peut y
insérer deux images et une fois que l’on applique un filtre par les autres
filtres issue du popupmenu, une image résultat apparaît.


## Les différents filtres avec une image:

- Transformation en gris:

![Optional Text](../master/images-readme/image_projet1.png)


- Transformation avec le filtre ‘Prewitt’ :

![Optional Text](../master/images-readme/image_projet2.png)


- Transformation avec le filtre ‘Canny’ :

![Optional Text](../master/images-readme/image_projet3.png)


- La détection avec deux images:

![Optional Text](../master/images-readme/image_projet4.png)



- La détection avec deux images issue de la webcam :

sans différence :

![Optional Text](../master/images-readme/image_projet5.jpg)


On peut constater que la première et la seconde photo prise à l’aide de
la webcam sont pratiquement identiques (certaines différences peuvent
être observées avec la résolution de l’image qui peut légèrement être
modifiée ainsi que l’ombre et la lumière qui peuvent différer entre les
deux images ).

On peut ainsi remarquer ci-dessous que les différences ne sont pas
assez fortes pour être “alarmantes” (les différences comptées ne
dépassent le seuil établie à > 3000



![Optional Text](../master/images-readme/image_projet6.png)


avec différence:

![Optional Text](../master/images-readme/image_projet7.jpg)

On peut constater que la première et la seconde photo sont nettement
différentes.

C’est pour cela que lors du passage du bras dans la deuxième photo
prise par la webcam, il est affiché le message d’alerte car il y a eu un
nombre de différences dépassant le palier de 3000 pour distinguer les
différences négligeables et les différences importantes comme on peut
le voir ci-dessous).


![Optional Text](../master/images-readme/image_projet8.png)












