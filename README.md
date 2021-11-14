# Eléments

## Gestion de versions : Git 
* Cf. https://fr.wikipedia.org/wiki/Gestion_de_versions
* Interface en ligne de commande + intégration avec Windows Explorer : https://git-scm.com/

```bash
    git config --global user.name "John Doe"
    git config --global user.email johndoe@example.com
```

* Voir aussi Desktop Application : https://desktop.github.com/

## IDE
* Cf. https://fr.wikipedia.org/wiki/Visual_Studio_Code
* https://code.visualstudio.com/ 

## Python
Choisir une distribution, une version (3.8 vs. 3.9 vs. 3.10)
* Cf. https://www.python.org/
* Cf. https://www.anaconda.com/products/individual

Ajouter un package supplémentaire 
```bash
pip install mathplotlib
```

# Premier-pas avec Visual Studio Code 
* Cloner un dépot
* Ouvrir un fichier .py, ajouter les extensions
* Changer le terminal 
`` 		"terminal.integrated.defaultProfile.windows": "Command Prompt",
* Changer les options de formatage
```bash
"python.formatting.autopep8Args": [
			"--max-line-length",
			"132"
		]
```

Note : exécuter script vs. lancer interpréteur et exécuter sélection


## Code quality and style
* Extension SonarLint piur VSCode
* Nécessite JRE 
