## app stay safe mobile:
 - donnees de user(nom,prenom,phone,email,status) usage de sqlite (1ere fois).
 - Service partage longitude et latitude en temp reel avec une REST API.
 - comparer les deff entre les latlong des utilisateurs si dans le rayon de 5m afficher un notification ou alert.

## REST API: (GET and POST)  MySQL

```
{server}/proximity/nearby/you/{id_request_owner}
```
get all the people that near by and show this status it can be exploited in a map and notificatin message.
  ``` 
  [
{
"id_near_user": 2,
"langitude": 7.54,
"latitude": 8.9,
"status": "p",
"surface_between": 6
},
{
"id_near_user": 4,
"langitude": 7.1,
"latitude": 8,
"status": "n",
"surface_between": 78
}
]
```
 


