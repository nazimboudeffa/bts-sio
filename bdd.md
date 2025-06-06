## 🗃️ Base de Données

### 🔍 SQL – Jointures
```sql
SELECT c.nom, o.date_commande
FROM clients c
LEFT JOIN commandes o ON c.id = o.client_id;
```

### 🛠️ Modélisation
- MCD (MERISE), UML
- Clés primaires / étrangères
