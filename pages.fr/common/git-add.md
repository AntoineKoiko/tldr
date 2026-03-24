# git add

> Ajoute les fichiers changés pour un commit.
> Plus d'informations : <https://git-scm.com/docs/git-add>.

- Ajoute un fichier pour un commit :

`git add {{chemin/vers/fichier}}`

- Ajoute tous les fichiers (suivis et non-suivis) :

`git add {{[-A|--all]}}`

- Ajoute tous les fichiers récursivement depuis le dossier actuel :

`git add .`

- Ajoute seulement les fichiers déjà suivis :

`git add {{[-u|--update]}}`

- Ajoute un fichier ignoré :

`git add {{[-f|--force]}} {{chemin/vers/fichier}}`

- Ajoute de manière intéractive des parties de fichier :

`git add {{[-p|--patch]}}`

- Ajoute de manière intéractive des parties d'un fichier :

`git add {{[-p|--patch]}} {{chemin/vers/fichier}}`

- Ajoute un fichier de manière intéractive :

`git add {{[-i|--interactive]}}`
