storypoints::55
# Base de donnée
![[Design Base de données 2022-09-29 12.53.11.excalidraw]]

 - **Utilisateurs** x
	 - username
	 - email
	 - <u>ID</u>(row)
	 - photo de profil (chemin/blob)
	 - rôle (modérateur ? admin ?)
	 - date de création
	 - banni ?
	 - option : nombre de signalements
 - **Questions** x
	 - <u>ID</u>
	 - contenu (string)
	 - date postée
	 - Visible ? (affiché dans le site ou non)
	 - nombre de signalements
	 - --> utilisateur (qui à posé la question)
	 - --> réponses
	 - --> commentaires
 - **Réponses** x
	 - <u>ID</u>
	 - contenu (string)
	 - Visible ? (affiché dans le site ou non)
	 - upvotes (nombre de votes up)
	 - downvotes (nombres de votes down)
	 - --> utilisateur (qui à posté la réponse)
	 - --> questions
 - **Commentaires** x
	 - <u>ID</u>
	 - contenu
	 - --> utilisateur (qui à posté le commentaire)
	 - --> questions
- **Signalements** x

- **roles** x
