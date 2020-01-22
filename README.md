# Boup
Plateforme de blog pour enfant

Créer un générateur de blog

Nom projet: Boup
Langages : PHP

Contraintes:
-Articles
  titre
  date de publi
  auteur
  MAJ
  commentaires
  contenu
  News Letter

-Base de données
-Serveur
-Conception

Générateur de blog dans un cadre scolaire pour des enfants de 8-12 ans lettrés.
  Partage de contenu enfants/profs
  initiation à l'écriture, format blog
  les parents doivent avoir accès en lecture
  archivage > export

Cible/Publique concerné:
enfants 8-12ans
  Lecteurs
  Scolaire 
professeur
  administration contenue
  ouverture / fermeture serveur
Besoins:
    Modération par professeur (valider ou refuser)
Fonctionnalités:
  Gestion d'articles
  Gestion de permissions 
    >insituteur 1e lv valider/supprimer/archiver post && gestion de permissions élèves
    >élèves 2e lv selon choix instituteur && publier/modifier/supprimer
    >famille/autres 3e lv lecture seule
  1 article peut contenir image/vidéo/audio/etc
  Visibilité article
    publication : 5 enfants valident pour publier ou le prof
  Accès public pour les parents
  Export plus tard
  Gestion des comptes (Mot de passe)

Interface:
  Ludique, simple et intuitif


Article:
  titre [string]
  contenu [texte]
  date de publication [date]
  utilisateur(s)
  visibilité [bool]
  brouillon [bool],
Utilisateur:
  UID (identifiant unique)
  Nom
  Prénom
  Mot de passe
Validation: article ID, utilisateur ID
