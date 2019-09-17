# Route : http://…
ex : *http://www.monsite.com/segment-fixe/{segment-variable}/{segment-optionnel?}/segment-fixe/{segment-any}/etc*

## Alias éventuel de la route
ex : *list_users*

## Action de la route
ex : *UserController@index*

## Objectifs de la requête
ex : *L’objectif premier de cette requête est d’afficher la liste des utilisateurs. Les objectifs secondaires de cette requête sont d’afficher en plus un formulaire de contact général pour le site (envoi par mail) et une liste des photos du dernier événement*

### Méthode HTTP
ex : *Post, Get, Put, Delete*

### Secure ?
ex : *oui, non*

### Règles pour les segments
ex : *optionnel, chiffre, regexp, etc.*

### Données de la requête
- Donnée 1 - règle de validation
 
### Ajax ?
ex : *oui, non*

### Données persistantes
ex : *cookie : login, session : panier, storage : préférences*

### Filtre avant
ex : *auth, dans la route*

### Filtre après
ex : *concaténation, dans le controlleur MyController*

### Modèle lié ?
ex : *User*

### Commentaire sur la route
ex : *Cette route doit être groupée avec les routes x et y afin d’appliquer le filtre machin. Le controlleur est un controlleur de ressources imbriquées, etc.*

# Réponse
## Type
ex : *Redirect, Vue, JSON, File Download, etc.*

## Si Vue
### Layout ?
ex : *master.layout*
### Vue principale
ex : *users*
### Données pour la vue principale
ex : *La liste des utilisateurs de GSM qui habitent namur et qui n’ont pas encore payé leur forfait* 

### Vues liées ?
ex : *forms.contact, modules.short_comments*
### Données pour la vue liée
ex: *Une liste des 10 derniers commentaires, seulement les 50 premières lettres*

### Compositeur ou créateur de vues éventuel
ex : *closure*

## Cookie associé ?
## En-têtes ?
