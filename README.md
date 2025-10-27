# Site Web en Go

Ce projet est un site web développé en Go qui affiche une page vide pour le moment. 

## Fonctionnalités

Le site affiche pour le moment une page vide. Deux fonctionnalités sera développée en parallèle, depuis la branche dev déjà existante.

## Installation

```bash
go mod tidy
go run main.go
```

Le serveur sera accessible sur http://localhost:8080


Réponse question 6
diff entre revert et reset 
git revert annul un commit en faisant un nouveau commit, sans changer l'historique alors que reset déplace le pointer HEAD vers un commit antérieur en réécrivant l'historique. Reset est plus dangereux vu qu'on peut perdre les données.