## 🔐 Cybersécurité

### 🛡️ OWASP Top 10
1. Injection SQL
2. Authentification cassée
3. Exposition de données sensibles
4. XSS (Cross-Site Scripting)
5. Contrôle d'accès
6. Mauvaise configuration de sécurité
7. Cross-Site Request Forgery (CSRF)
8. Utilisation de composants vulnérables
9. Journalisation insuffisante
10. Falsification des requêtes côté serveur

### 🔒 Sécuriser une application PHP
- Utiliser `password_hash()` et `password_verify()` pour les mots de passe
- Requêtes préparées avec PDO
- Échapper les sorties (ex: `htmlspecialchars()`)
- Utiliser HTTPS
- Sécuriser les sessions (regen ID, timeout)
