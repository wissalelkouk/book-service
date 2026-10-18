# book-service

Microservice de catalogue et de gestion des emprunts (Node.js, Express).
Fait partie du projet Gestion Bibliothèque : voir le dépôt `gitops-config` pour l'architecture globale.

## Endpoints

- `GET /health` : état du service
- `GET /books` : liste et recherche de livres (à venir)
- `POST /books` : ajout d'un livre, admin (à venir)
- `POST /loans` : emprunt d'un livre (à venir)

## Lancement local

```bash
npm install
npm start
```

## Variables d'environnement

- `PORT` : port d'écoute (défaut 3001)
