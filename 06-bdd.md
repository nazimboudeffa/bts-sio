## 🗃️ Base de Données

### 🔍 SQL – Jointures
```sql
SELECT c.nom, o.date_commande
FROM clients c
LEFT JOIN commandes o ON c.id = o.client_id;
```

### 🛠️ Modélisation
- MCD (MERISE), MLD, MPD
- UML : cas d'utilisation, diagramme de classes
- Clés primaires / étrangères

## REFS

### 🛠️ Bases de Données / SQL

- SQL.sh – le site de référence pour apprendre SQL en français.

- Modele-rel.fr – apprentissage des bases relationnelles.

- DB-Fiddle – pour tester vos requêtes en ligne.
