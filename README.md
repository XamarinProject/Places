# Places
# Sabri Habib
# Alexandre Armando
# [30/03/2020 - *]

Technologies utilis�es :
-	Xamarin forms
-	Shell navigation
- 	

Environnement de d�veloppement :
-	Windows 10
-	Visual Studio 2019
-	Git flow
-	

Plugins utilis�s :
-	

----------------------------------------------------------------------------------------------------------------------------

Th�me :
Le th�me global de l�application sera la m�t�o et d�autres donn�es li�es � la ville. Le but �tant de cr�er une application personnalisable en proposant � l�utilisateur de param�trer ses villes favorites et d�obtenir rapidement les informations qui l�int�resse (tendance actuelle, temp�rature, heure, etc.). 
Structure et contenu :
L�application sera compos�e d�au moins 4 �crans :
-	Un �cran d�accueil contenant les villes ajout�es comme favoris avec la possibilit� d��diter cette liste dynamiquement
-	Un �cran de recherche avec des champs inputs personnalis�s nativement
-	Un �cran de d�tails pr�sentant la m�t�o et les informations (heure, jour/nuit, etc.) de la ville s�lectionn�e et la possibilit� de sauvegarder la ville dans la liste en l�ajoutant aux favoris
-	Un �cran de param�tre permettant de g�rer les donn�es enregistr�es et les donn�es � afficher (activation/d�sactivation des web services, pr�visualisation sur l��cran d�accueil, tendance, temp�rature, humidit�, etc.)

----------------------------------------------------------------------------------------------------------------------------

Navigation :
Nous utiliserons le Shell pour g�rer la navigation entre l��cran d�accueil, la page de recherche et cette de param�tre. Nous proposerons donc un menu lors du swipe vers la droite.

----------------------------------------------------------------------------------------------------------------------------

Api(s) :
-	OpenWeatherMap ( https://openweathermap.org/current )
-	

----------------------------------------------------------------------------------------------------------------------------

Cas d�utilisations :
En tant qu�utilisateur, je veux pouvoir lancer l�application et arriver sur la page d�accueil afin de consulter les informations li�es � mes villes favorites.
En tant qu�utilisateur, je veux pouvoir s�lectionner une ville de ma liste afin de pouvoir consulter des d�tails sur sa m�t�o actuelle et ses pr�visions.
En tant qu�utilisateur, je veux pouvoir naviguer entre les pages via le menu afin de me permettre de d�couvrir les fonctionnalit�s.
En tant qu�utilisateur, je veux pouvoir rechercher une ville afin de pouvoir consulter sa m�t�o.
En tant qu�utilisateur, je veux pouvoir ajouter une ville que j�ai recherch� � mes favoris, afin de pouvoir y acc�der rapidement depuis mon �cran d�accueil.
En tant qu�utilisateur, je veux pouvoir acc�der aux param�tres afin de pouvoir s�lectionner les informations que je souhaite afficher sur mon �cran d�accueil.
En tant qu�utilisateur, je veux que mes informations et pr�f�rences soient enregistr�es afin que mes favoris soient conserv�s la prochaine fois que je lance l�application.

----------------------------------------------------------------------------------------------------------------------------

