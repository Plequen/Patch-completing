						Compl�tion d'images par patchs - Readme

//Sous Windows 7 et Windows Vista

Les dossiers rendus et inputs doivent �tre dans le m�me dossier que l'ex�cutable.
Les dll suivantes doivent �tre avec l'ex�cutable : libopencv_core230.dll ; libopencv_highgui230.dll ; glut32.dll.
Ces dll ainsi que l'ex�cutable sont dans le dossier bin.

Ex�cution de l'application :

*sans arguments : applique l'algorithme de reconstruction pour l'image des colonnes 128x128 pr�sente dans le dossier inputs.

*avec un argument quelconque : patch-completing.exe x
	Applique l'algorithme de reconstruction pour certaines images du dossier inputs pour diff�rentes valeurs de la taille du patch et de tau.
	Les r�sultats sont stock�s dans le dossier rendus.
*avec quatre arguments : patch-completing.exe entree masque patch tau
	Applique l'algorithme de reconstruction pour l'image entree avec le masque masque, en prenant patch pour taille de patch et tau pour valeur de tau.
	Les r�sultats sotn stock�s dans le dossier rendus.
	