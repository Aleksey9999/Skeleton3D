Je viens vous pr�senter mon petit projet reprap: la skeleton 3D

L�id�e a germ� dans ma t�te apr�s quelques mois d�utilisation de ma prusa i3, beaucoup de personnes dans mon entourage avaient envie de voir la b�cane fonctionner mais ce n�est pas super facile de transporter une i3. De plus, j�ai constat� que j�utilisais tr�s rarement l�enti�re surface d�impression et que la majorit� de mes print se limite � une surface de 100x100.

Apr�s avoir cherch� une petite imprimante compacte, transportable et peu ch�re sur le wiki, j�ai d�cid� d�en concevoir une r�pondant � mes besoins faute d�en trouver une ! 
C�est-�-dire: transportable, robuste, �volutive, peu cher mais avec des impressions de qualit� !

L'union faisant la force et augmentant la cr�ativit�, j�ai travaill� avec un ami poss�dant aussi une i3 qui a tout de suite accroch�.

Nous avons par la suite, commenc� par d�finir :
L�architecture de la machine 
- Pi�ces plastiques + tiges filet�s �8 (?�)
- D�placement de la hotend en X et Y (course 100x100) et du plateau en Z (course 100 � 150 mm)
- Mouvements axiaux + Extrusion
- 4 moteurs NEMA 17 de 40 mm et 4kg
- 1 extruder con�u pour �tre compact et en directdrive

Guidage axiaux :
- Classique avec des LM8UU

Hotend :
- Aluhotend 1.75mm (en cours de test)

Alimentation :
- 72W de pc portable

 736943COM.jpg
736943COM.jpg


Am�liorations apport�es au prototype :
->	Augmentation de la surface de guidage (2xLM8uu) au niveau de l�effort moteur (X et Y) pour supprimer le risque d�arc boutement
->	Augmentation de la surface de guidage du plateau Z (3x LM8uu) pour limiter la flexion
->	Augmentation de la surface de guidage de la hotend (4 x LM8uu) pour supprimer les jeux
->	Mise en place d�un plateau acier galva 15/10
->	Fixation par vis des endstop int�gr� aux pi�ces plastiques
->	Calibrage Z via une vis M4 r�glable
