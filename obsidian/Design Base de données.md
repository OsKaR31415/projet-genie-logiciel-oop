storypoints::55
# Base de donnée
![[Design Base de données 2022-09-29 12.53.11.excalidraw]]

 - **Utilisateurs**
	 - username
	 - email
	 - <u>ID</u>
	 - photo de profil
	 - rôle (modérateur ? admin ?)
	 - date de création
	 - banni ?
	 - option : nombre de signalements
 - **Questions**
	 - <u>ID</u>
	 - contenu (string)
	 - date postée
	 - Visible ? (affiché dans le site ou non)
	 - nombre de signalements
	 - --> utilisateur (qui à posé la question)
	 - --> réponses
	 - --> commentaires
 - **Réponses**
	 - <u>ID</u>
	 - contenu (string)
	 - Visible ? (affiché dans le site ou non)
	 - upvotes (nombre de votes up)
	 - downvotes (nombres de votes down)
	 - --> utilisateur (qui à posté la réponse)
	 - --> questions
 - **Commentaires**
	 - <u>ID</u>
	 - contenu
	 - --> utilisateur (qui à posté le commentaire)
	 - --> questions

