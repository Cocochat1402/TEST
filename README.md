Lecteur vidéo HTML personnalisé
Aperçu
Il s'agit d'un lecteur vidéo HTML5 personnalisé, développé en HTML, CSS et JavaScript. Son interface moderne et intuitive offre les fonctionnalités essentielles de lecture vidéo, avec un style CSS personnalisé et un design épuré et adaptatif. Conçu pour fonctionner avec les navigateurs web modernes, il propose diverses commandes pour une expérience de visionnage optimale.

Caractéristiques
Lecture/Pause : Activez/désactivez la lecture vidéo à l'aide d'un bouton ou en cliquant sur la vidéo.
Barre de progression : Accédez à des points précis de la vidéo en cliquant ou en faisant glisser la barre de progression, avec un aperçu temporel au survol de la souris.
Contrôle du volume : Ajustez le volume à l’aide d’un curseur ou activez/désactivez le son à l’aide d’un bouton.
Mode plein écran : Activez l’affichage plein écran pour une expérience immersive.
Vitesse de lecture : Choisissez parmi plusieurs vitesses de lecture (0,5x, 0,75x, 1x, 1,25x, 1,5x, 2x) via un menu de paramètres.
Activation/désactivation des sous-titres : Activer/désactiver les sous-titres de substitution (extensible avec WebVTT pour de vrais sous-titres).
Indicateur de chargement : retour visuel pendant la mise en mémoire tampon de la vidéo.
Conception adaptative : s'adapte aux différentes tailles d'écran, avec des ajustements pour les appareils mobiles.
Style moderne : Interface utilisateur épurée et minimaliste avec effets de survol, couleurs personnalisées et transitions fluides.
Usage
Lecture/Pause : Cliquez sur le bouton de lecture (▶/❚❚) ou sur la vidéo elle-même pour activer/désactiver la lecture.
Recherche : Cliquez ou faites glisser la barre de progression pour accéder à une heure précise. Survolez la barre de progression pour afficher un aperçu de l’heure.
Volume : Utilisez le curseur de volume pour ajuster les niveaux audio ou cliquez sur le bouton muet (🔊/🔇) pour activer/désactiver le mode muet.
Plein écran : Cliquez sur le bouton plein écran (⛶) pour entrer/sortir du mode plein écran.
Vitesse de lecture : Cliquez sur le bouton des paramètres (⚙️) pour ouvrir le menu et sélectionner une vitesse de lecture.
Sous-titres : Cliquez sur le bouton des sous-titres (CC) pour activer/désactiver les sous-titres provisoires (utilisez WebVTT pour obtenir les véritables sous-titres).
Comportement adaptatif : Le lecteur ajuste sa mise en page et la taille de ses commandes aux écrans plus petits.
Personnalisation
Source vidéo : Mettez à jour la <source>balise dans l’ <video>élément pour utiliser votre propre fichier vidéo.
Style : Modifiez les variables CSS dans la :rootsection (par exemple, --primary-color, --bg-color) pour changer le schéma de couleurs.
Légendes : Pour ajouter de véritables légendes, incluez un fichier WebVTT et ajoutez un <track>élément à la <video>balise, par exemple :
<track src="captions.vtt" kind="subtitles" srclang="en" label="English">
Image d'affiche : Remplacez l' posterattribut dans la <video>balise par l'URL de votre propre image pour la miniature de la vidéo.
Fonctionnalités supplémentaires : Étendez le JavaScript pour ajouter des fonctionnalités telles que des raccourcis clavier, une sélection de qualité ou des contrôles personnalisés.
Notes
Dépendances : Aucune dépendance externe n'est requise, car tous les styles et fonctionnalités sont implémentés avec du HTML, du CSS et du JavaScript purs.
Limitations :
La fonction de sous-titres est temporaire et nécessite un fichier WebVTT pour fonctionner pleinement.
Certains navigateurs peuvent restreindre la lecture automatique ou le mode plein écran lorsque l'hébergement n'est pas effectué sur un serveur, en raison de politiques de sécurité.
Débogage : Ouvrez les outils de développement du navigateur (F12) pour vérifier la console et rechercher les erreurs si une fonctionnalité ne fonctionne pas comme prévu.
Source vidéo : La vidéo d’exemple ( BigBuckBunny.mp4) est hébergée sur un serveur externe. Assurez-vous que votre source vidéo est accessible et dans un format compatible.
Dépannage
Commandes non fonctionnelles : assurez-vous que le fichier vidéo est accessible et que votre navigateur prend en charge la vidéo HTML5. Consultez la console pour détecter d’éventuelles erreurs.
Problèmes liés au mode plein écran : Certains navigateurs exigent que la page soit servie via HTTP/HTTPS pour que le mode plein écran fonctionne.
Erreurs d'affichage de la durée : Si la durée affichée est incorrecte, vérifiez que les métadonnées du fichier vidéo sont valides et que l' loadedmetadataévénement est bien déclenché.
Performances : Pour les vidéos volumineuses, assurez-vous que votre serveur prend en charge les requêtes de plage pour permettre une recherche fluide.
Pour toute assistance supplémentaire ou demande de fonctionnalités, n'hésitez pas à modifier le code ou à contacter le support !
