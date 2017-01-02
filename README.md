# my_gitignore_global

On clone le repo suivant où on le souhaite, par exemple "~/work/config"

On indique à Git où se situe le fichier de paramètre global .gitignore

	git config --global core.excludesfile '~/.gitignore_global'

On fait un lien symbolique

	ln -s ~/work/config/my_gitignore_global/.gitignore_global ~/.gitignore_global

On tient à jour son fichier dans GitHub, c'est tout et c'est déjà pas mal :)