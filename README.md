# [Windows] SDK (Sheol Developer Kit)### Composition du SDK- MinGW: un environnement de d�veloppement minimaliste pour les applications natives de Microsoft Windows.- npp (Notepad++): un �diteur de texte g�n�rique qui int�gre la coloration syntaxique.	Dans cette version il est dot� de diff�rents plugins dont NppExec qui permet de compiler ou	d'ex�cuter notre projet.- test_code: un simple code en c++ avec un main, une classe et un Makefile.- Launcher.bat: qui lance Notepad++ avec les bonnes configurations qui permettes de compiler.- Open command line.bat: ouvre une console ou vous pouvez lancer des commandes comme	rm, make, g++ ou encore gcc.	### ImportantUn projet �quivaut � un dossier !### Raccourcis du SDK- F9: compile notre projet en utilisant notre Makefile, �quivalent � la commande "Make"	(example disponible dans "test_code").- ctrl + F9: compile �galement le projet avec un Maekfile mais est �quivalent � un "Make re"- F5: permet de lancer notre programme, une boite de dialogue permet de sp�cifier le binaire � lancer.### Scripts du SDKTous les scripts du SDK sont disponibles dans : Plugins->NppExec->(en bas du menu)- Make- Make re- Make fclean- Make clean- Compile one C File- Compile one C++ File- Execute Compiled File by Make- Execute Compiled File only