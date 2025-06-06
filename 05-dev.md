## 💻 Développement (SLAM)

### 🔹 Fiche Langage : HTML/CSS
#### 🧱 HTML (structure)
- Doctype : `<!DOCTYPE html>`
- Balises de base :
```html
<html>
  <head>
    <title>Page</title>
  </head>
  <body>
    <h1>Titre</h1>
    <p>Paragraphe</p>
    <a href="#">Lien</a>
  </body>
</html>
```
- Formulaires : `<form>`, `<input>`, `<label>`, `<button>`

#### 🎨 CSS (style)
- Sélecteurs : `element`, `.class`, `#id`
- Propriétés courantes :
```css
body {
  background-color: #f0f0f0;
  font-family: Arial;
  color: #333;
}
```
- Positionnement : `flex`, `grid`, `relative`, `absolute`
- Media queries :
```css
@media screen and (max-width: 768px) {
  body {
    font-size: 14px;
  }
}
```
- Animation simple :
```css
button:hover {
  background-color: blue;
  transition: background-color 0.3s;
}
```

### 🔹 Fiche Langage : PHP
- Syntaxe de base : `<?php ... ?>`
- Variables : `$nom = "valeur";`
- Structures de contrôle : `if`, `while`, `foreach`
- Fonctions : `function nomFonction() {}`
- Connexion PDO :
```php
$conn = new PDO("mysql:host=localhost;dbname=ma_base", "root", "");
```
- Sécurité : `password_hash`, requêtes préparées

### 🔹 Fiche Langage : JavaScript
- Variables : `let`, `const`, `var`
- Fonctions :
```js
function addition(a, b) {
  return a + b;
}
```
- DOM : `document.querySelector`, `addEventListener`
- Exemple d'événement :
```js
button.addEventListener('click', () => alert("Clic!"));
```
- JSON & Fetch :
```js
fetch('/api')
  .then(res => res.json())
  .then(data => console.log(data));
```

### 🔹 Fiche Langage : SQL
- SELECT, INSERT, UPDATE, DELETE
- Filtres : `WHERE`, `AND`, `OR`
- Tri : `ORDER BY`, `LIMIT`
- Jointures :
```sql
SELECT c.nom, o.date_commande
FROM clients c
LEFT JOIN commandes o ON c.id = o.client_id;
```
- Agrégats : `COUNT`, `SUM`, `AVG`

### 🔹 POO (Programmation Orientée Objet)
- Classe : structure définissant les objets
- Objet : instance d'une classe
- Encapsulation : protection des données internes (`private`, `public`, `protected`)
- Héritage : une classe peut hériter d'une autre (`extends`)
- Polymorphisme : surcharge et redéfinition de méthodes

### 🔹 Fiche Langage : C#
- Déclaration :
```csharp
int x = 5;
string nom = "Alice";
```
- Structures de contrôle : `if`, `switch`, `while`, `for`
- Fonctions :
```csharp
void AfficherNom(string nom) {
  Console.WriteLine(nom);
}
```
- Classes & Objets :
```csharp
class Personne {
  public string Nom { get; set; }
  public Personne(string nom) {
    Nom = nom;
  }
}
```
- Manipulation fichiers :
```csharp
File.WriteAllText("fichier.txt", "Bonjour");
string contenu = File.ReadAllText("fichier.txt");
```
- LINQ :
```csharp
var resultats = liste.Where(p => p.Age > 18).ToList();
