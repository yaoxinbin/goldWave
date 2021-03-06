# Goldwave #

* Auteurs : Joseph Lee, contributeurs de NVDA.
* Télécharger [version stable][1]
* Télécharger [version de développement][2]
* Compatibilité NVDA: 2017.3 à 2019.1

Cette extension améliore l'accès et l'utilisation de l'éditeur audio
Goldwave.

## Raccourcis ##

* NVDA+Maj+C : Bascule la verbalisation des commandes lors de l'édition
  audio.
* Contrôle+Maj+P : Annonce la position actuelle de la piste.
* NVDA+Maj+R: Annonce le temps restant de la piste que vous êtes
  actuellement en train de modifier.
* Contrôle+NVDA+1 : Annonce le canal que vous êtes en train de modifier.
* Contrôle+NVDA+2 : Annonce la longueur totale du fichier audio.
* Contrôle+NVDA+3 : annonce un résumé des informations de sélection audio.
* Contrôle+NVDA+4 : Annonce le niveau de zoom.

Pour plus d'informations sur Goldwave et les commandes clavier,
reportez-vous au manuel de Goldwave.

Note : GoldWave 6 requiert la version 64 bits de Windows 7 ou version
ultérieure. NVDA 2014.1 ou version ultérieure est requis pour utiliser le
module complémentaire 2.0.

## Version 18.07

* Correction d'un problème où les zéros en tête ne s'affichaient pas lorsque
  vous essayiez d'obtenir le temps restant pour une piste.

## Version 17.05

* Ajout de la possibilité de fournir des informations de débogage lorsque
  NVDA est en cours d'exécution avec le journal activé en mode débogage
  (NVDA 2017.1 ou version ultérieure).
* Traductions mises à jour.

## Version 16.12

* La version système est maintenant year.month au lieu de major.minor.

## Changements pour la version 4.0

* Le référentiel de l'extension a été déplacé à GitHub (maintenant localisé
  à https://github.com/josephsl/goldwave).
* Amélioration des performances lorsque vous cherchez des informations comme
  le nom du canal et d'autres informations du statut.

## Changements pour la version 3.0

* Ajout d'une commande pour annoncer le temps restant pour la piste actuelle
  (NVDA+Maj+R).
* Légère amélioration dans l'annonce d'informations de statut  telles que
  les informations du canal.

## Changements pour la version 2.0

* Support pour GoldWave 6, y compris la version 64-bit de GoldWave (voir la
  note ci-dessus).
* L'aide de l'extension est désormais accessible à partir du Gestionnaire
  d'extensions (NVDA 2014.3 et versions ultérieur).
* NVDA annonce maintenant le canal sélectionné si vous appuyez sur les
  commandes de sélection de canaux tels que Ctrl+Maj+L pour le canal gauche.
* Divers problèmes avec les zones d'édition numérique comme le détecteur de
  zone et le sélecteur de temps dans la boîte de dialogue du mélangeur a été
  corrigé, y compris la sélection de texte, mise à jour des valeurs et ainsi
  de suite.
* Le paramètre d'annonce de commande sera mémorisé lors du basculement vers
  d'autres programmes.

## Changements pour la version 1.2

* Correction d'un problème où NVDA avait des Difficultés à annoncer
  certaines zones d'édition.
* Traductions nouvelles et mises à jour.
* Veuillez noter qu'en raison de changements récents dans NVDA, la sélection
  audio et le statut d'autres commandes peuvent ne pas fonctionner comme
  prévu sur certains systèmes.

## Changements pour la version 1.1

* prise en charge des annonces de message en braille.
* le résumé de la Sélection audio est présentée dans des langues autres que
  l'anglais.
* Autres annonces de commande ajoutés y compris le mouvement de la position
  du point de repère et les opérations supprimer/couper.
* Correction d'un problème dans les zones d'édition numérique comme les
  divers effets  des boîtes de dialogues où rien ou le mauvais nom de la
  zone était annoncé.
* Traductions nouvelles et mises à jour.

## Changements pour la version 1.0

* Première version.

[[!tag dev stable]]

[1]: https://addons.nvda-project.org/files/get.php?file=gwv

[2]: https://addons.nvda-project.org/files/get.php?file=gwv-dev
