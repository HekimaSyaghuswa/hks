Bonjour,

Je suis KATEMBO SYAGHUSWA HEKIMA, étudiant en Gestion Informatique à l'Université de l'Assomption au Congo (UAC), Butembo.

Voir le site en ligne

Mon Portfolio : https://github.com/HekimaSyaghuswa/hks/blob/main/portfolio.html
Catalogue HK Papeterie :https://github.com/HekimaSyaghuswa/hks/blob/main/index.html
Galerie Publique : https://github.com/HekimaSyaghuswa/hks/blob/main/gallery.html
Publier un produit :https://github.com/HekimaSyaghuswa/hks/blob/main/upload.html


HK Papeterie est mon projet actuel : un catalogue où tout le monde peut publier ses produits avec son nom, à Butembo.

Fonctionnalités :
-  Publier un produit avec photo, prix, vendeur, lieu
-  Rechercher un produit, un vendeur, une ville
-  Compteur de produits publiés
-  Commander en 1 clic sur WhatsApp
-  Modifier prix / description avec code admin
-  Supprimer un produit avec code admin
-  Galerie publique pour tous



 Technologies utilisées

- HTML / CSS / JavaScript
- Firebase Realtime Database pour les données
- Cloudinary pour les images des produits
- GitHub Pages pour l'hébergement du site



Comment fonctionne Cloudinary sur mon site ?

J'utilise Cloudinary pour gérer les images des produits.

Pourquoi ?
Parce que GitHub Pages ne peut pas stocker les images que les utilisateurs envoient. Il faut un service en ligne pour ça.

Comment ça marche, en 3 étapes :
1.  L'utilisateur choisit une photo sur son téléphone dans upload.html
2.  La photo part directement vers Cloudinary, qui la compresse et la sécurise
3.  Cloudinary me renvoie un lien (URL) de la photo, et c'est ce lien qu' s'enregistre automatiquement dans le Firebase avec le nom, le prix et le vendeur du produit.

Ensuite, quand quelqu'un ouvre index.html ou gallery.html, le site affiche la photo à partir de ce lien Cloudinary.

securité de mon site

oui, tout le monde et autorisé de publier sur mon site mais il n'est pas autorisé de faire quelques action notement: la supression, la modification du prix ou du nom , ....... sur tout ça je mis un mot de passe sur ces actions, donc c'est moi l'administrateur qui ai droit de supprimer ou de tout modifier.

pourquoi  les photos dans mon dossier images/ ?

Les photos dans mon dossier images/ comme hekima.jpg (ma photo de profil) ne sont pas sur Cloudinary.

Elles sont stockées directement sur GitHub, car ce sont des images fixes qui ne changent pas.

En résumé :
- GitHub = pour mes photos fixes (portfolio, logo)
- Cloudinary = pour les photos dynamiques des produits publiés par les utilisateurs
- Firebase = pour les textes (nom, prix, vendeur, lien de la photo)
