## Processus de jeu - Partie 7 (niveau avancé)

### Introduction aux nombres

Sans attribuer de valeurs numériques aux commandes (supérieures ou inférieures à la commande), le robot utilise les paramètres de mouvement par défaut :  
- Avancer de 10 cm (100 mm).  
- Rotation de 90 degrés.  

Vous pouvez contrôler ces valeurs en ajoutant des paramètres numériques aux commandes dans des cellules jumelées.  

Exemple : Ajoutez la valeur **200** à la commande **"Avancer"** et observez la distance parcourue par le robot. Ajoutez la valeur **180** à la commande **"Tourner"** et évaluez les changements.  

![example1](images/example1.excalidraw.svg)

> **Important :** La télécommande conserve la dernière valeur définie pour le mouvement et la rotation. 
- Si une commande est utilisée sans une nouvelle valeur, la dernière valeur enregistrée est appliquée jusqu'à l'extinction de la télécommande !
- Ainsi, définir un nouveau paramètre modifie la valeur par défaut.  
- Vous pouvez restaurer les valeurs d'origine (100 mm et 90°) en les indiquant explicitement dans les commandes ou en éteignant puis rallumant la télécommande.  

Un contrôle flexible des nombres étend les possibilités d'apprentissage. En modifiant la distance et l'angle de rotation, vous pouvez :  
- Créer des figures complexes.  
- Programmer un mouvement selon une trajectoire courbe.  
- Implémenter de nouveaux scénarios de mouvement.  

Utilisez les paramètres variables pour améliorer le contrôle du robot. Consultez des exemples sur la [page des dessins mathématiques](/ru/math_drawings_ru).

---

## Processus de jeu - Partie 8 (niveau avancé)

### Introduction aux opérations arithmétiques

Les valeurs numériques avec des opérations arithmétiques modifient les commandes de mouvement. Cela permet d'ajuster dynamiquement les commandes (Avancer, Reculer, Gauche, Droite), rendant le contrôle du robot plus flexible.

Comment ça fonctionne ?
Lorsque vous ajoutez une opération arithmétique, la télécommande modifie la valeur enregistrée pour la commande et envoie la nouvelle valeur au robot.

Exemple :
La commande "Avancer 200" fera avancer le robot de 200 mm (20 cm).
Si la commande suivante est "Avancer +100", le robot avancera de 300 mm (30 cm).

![example2](images/example2.excalidraw.svg)

Si ces commandes sont utilisées en boucle, elles peuvent créer des suites numériques - progressions arithmétiques et géométriques.

> Point important : Si une commande réduit la valeur à un nombre négatif, le robot effectuera l'action opposée : 
Au lieu d'avancer, il reculera.
Au lieu de tourner à gauche, il tournera à droite.

Opérations arithmétiques disponibles :
- Addition (+) - augmente la valeur.
- Soustraction (-) - diminue la valeur.
- Multiplication (*) - multiplie la valeur.
- Division (/) - divise la valeur.
- Racine (√) - extrait la racine carrée.
- Puissance (^) - élève à une puissance donnée.

Vous voulez voir comment créer des motifs mathématiques complexes avec ces opérations ? Consultez la [page des dessins mathématiques](/ru/math_drawings_ru) !

---

## Jouez et apprenez avec les enfants !

Vous connaissez mieux que quiconque vos élèves et la meilleure manière de travailler avec eux. Le développement et l'éducation des enfants dépendent de vous. PrimaSTEM est un outil polyvalent pour enseigner aux enfants, non seulement la logique et la programmation, mais aussi d'autres matières. Utilisez sa flexibilité pour créer un environnement d'apprentissage ludique. Tout ne dépend que de votre imagination !

*p/s: Merci d'utiliser PrimaSTEM dans votre processus d'apprentissage ou de vous y intéresser !
Nous espérons recevoir vos retours, n'hésitez pas à [nous écrire](/ru/contacts.md) sur votre expérience.*
