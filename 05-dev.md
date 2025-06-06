## 💻 Développement (SLAM)

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
