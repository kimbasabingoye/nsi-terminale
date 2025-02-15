Voici un petit quiz pour évaluer un élève de Terminale NSI sur la programmation orientée objet en Python.  

---

### **Quiz : Programmation Orientée Objet en Python**  

**1. Vocabulaire de la programmation objet**  
_(4 points)_  
Associez chaque définition au bon terme parmi : **classe, instance, attribut, méthode**  

a) Une fonction définie à l’intérieur d’une classe et qui peut agir sur ses instances.  
b) Une variable associée à une instance et qui stocke une valeur propre à celle-ci.  
c) Un plan ou un modèle qui définit des attributs et des méthodes communes à plusieurs objets.  
d) Un objet créé à partir d’une classe.  

---

**2. Création d'une classe et d'instances**  
_(4 points)_  
Que va afficher le code suivant ?  

```python
class Voiture:
    def __init__(self, marque, vitesse):
        self.marque = marque
        self.vitesse = vitesse

ma_voiture = Voiture("Toyota", 120)
print(ma_voiture.marque)
print(ma_voiture.vitesse)
```

a) Toyota et 120  
b) Erreur car la classe n’a pas de méthode **init**  
c) Rien, car on n’a pas défini de méthode pour afficher les informations  
d) Erreur car self n’a pas été utilisé dans **init**  

---

**3. Utilisation de la notation pointée**  
_(4 points)_  
Quel est le résultat de ce programme ?  

```python
class Chien:
    def __init__(self, nom):
        self.nom = nom

    def aboyer(self):
        return f"{self.nom} aboie !"

chien1 = Chien("Rex")
print(chien1.aboyer())
```

a) "aboyer"  
b) "Rex aboie !"  
c) Erreur car self.nom est mal utilisé  
d) Rien, car la méthode aboyer ne contient pas d’instruction print  

---

**4. Compréhension du paramètre self**  
_(4 points)_  
Pourquoi utilise-t-on **self** dans une méthode de classe ?  

a) Pour indiquer qu’il s’agit d’une fonction globale  
b) Pour faire référence à l'instance courante et accéder à ses attributs et méthodes  
c) Ce n'est pas obligatoire, on peut utiliser n'importe quel mot à la place  
d) Pour initialiser automatiquement tous les objets créés  

---

### **Correction**  

1. a) **Méthode** - b) **Attribut** - c) **Classe** - d) **Instance**  
2. a) **Toyota et 120**  
3. b) **"Rex aboie !"**  
4. b) **Pour faire référence à l'instance courante et accéder à ses attributs et méthodes**  

**Score :**  
16-12 : Excellent 🎉  
11-8 : Bon niveau 👍  
7-4 : À revoir 🧐  
3-0 : Besoin de révisions 📚  

---

Tu veux que j'ajoute d'autres questions ou que je le transforme en QCM interactif ? 😊
