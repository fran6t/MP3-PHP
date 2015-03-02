# MP3-PHP
Lecture de fichier MP3 et gestion des paroles (pas de gestion play liste)

Grosso modo, vous rangez sur votre serveur vos fichiers MP3 de la façon suivante:

Un repertoire A avec dedans autant de repertoire que d'artiste commençant par A, idem pour B...
Exemple 

<img="http://blog.passion-tarn-et-garonne.info/public/MP3-PHP/arborescence.jpg" alt="Exemple rangement" />

Un seul fichier index.php qui fait le gros du travail:

- il permet de se ballader dans l'arborescence;
- utilisation des TAG mp3 pour presenter les infos,
- écouter les chansons d'un repertoire;
- montrer la pochette (à la condition d'avoir enregistré un fichier cover.jp correspondant);
- lorsque les chansons sont présentes un formulaire permet de mettre les paroles en langue original et en face la traduction.


Utilisation des codes suivants :
getID3() by James Heinrich <info@getid3.org> (pour recupération des infos tag mp3)
jPlayer Website: http://www.jplayer.org/ (pour la lecture de liste mp3 gestion volume..)
