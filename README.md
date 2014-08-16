# [Windows] SDK (Sheol Developer Kit)
### Composition du SDK
* MinGW: un environnement de développement minimaliste pour les applications natives de Microsoft Windows.
* npp (Notepad++): un éditeur de texte générique qui intčgre la coloration syntaxique.
	Dans cette version il est doté de différents plugins dont NppExec qui permet de compiler ou
	d'exécuter notre projet.
* test_code: un simple code en c++ avec un main, une classe et un Makefile.
* Launcher.bat: qui lance Notepad++ avec les bonnes configurations qui permettes de compiler.
* Open command line.bat: ouvre une console ou vous pouvez lancer des commandes comme
	rm, make, g++ ou encore gcc.
	
### Important
Un projet équivaut à un dossier !

### Raccourcis du SDK
* F9: compile notre projet en utilisant notre Makefile, équivalent ŕ la commande "Make"
	(example disponible dans "test_code").
* ctrl + F9: compile également le projet avec un Maekfile mais est équivalent ŕ un "Make re"
* F5: permet de lancer notre programme, une boite de dialogue permet de spécifier le binaire ŕ lancer.

### Scripts du SDK
Tous les scripts du SDK sont disponibles dans : Plugins->NppExec->(en bas du menu)
```
* Make
* Make re
* Make fclean
* Make clean
* Compile one C File
* Compile one C++ File
* Execute Compiled File by Make
* Execute Compiled File only
```