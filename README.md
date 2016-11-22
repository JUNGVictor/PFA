# PFA

## 22/11 : 
J'ai ajouté tout le code avec les callbacks.  
J'ai également ajouté un bouton update qui sert à charger dans l'éditeur les valeurs du carré selectionné (à la souris ça sera automatique).  
Les boutons copier/coller fonctionnent correctement.  
J'ai changé la structure des notes, qui sont maintenant en "(num gamme)" (72 5) => (Do en gamme 5)  
J'ai changé la liste de tous les carrés en vecteur. La variable se nomme désormais ALLSQUARES.  
> Acces a l'élément n : (vector-ref ALLSQUARES n) O(1)  
> Parcours de tous les élements : O(n) (avant : O(n²))
