# Les instructions JOIN sont utilisées pour exécuter correctement les requêtes jointes.
# Le code connecte les formulaires New Artist et New Venue à une base de données en utilisant avec succès SQLAlchemy pour insérer de nouveaux enregistrements dans la base de données lors de la soumission du formulaire. Les erreurs dans la soummision précedentes sont dues à la taille des caractères pour les différents liens. 120 par defaut, mis à 500 actuellement. J'ai utilisé str(Exception) cette fois pour que vous voyez vous meme la sortie d'erreur! 

# Tout marche à présent !

**Dans cette version**
# Les champs contacts sont définies sur numeric et sont obligatoires en base.
# On peut réchercher un artiste à partir de la page Venue, et le sélectionner pour créer un Show
# Tout marche à présent !
NB:
- Créer une base de données ffyur ou autre et le spécifier dans le fichier *config.py*
- Exécuter les migrations : flask db init ; flask db migrate; flask db upgrade;


