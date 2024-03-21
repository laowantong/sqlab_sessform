
## Tutoriel
### Projection

- **Exercice 1**. Donnez l'identifiant, la raison, l'activité et la ville de toutes les entreprises.  
  Énoncé complet : 096. Solution : 277188057325886.
- **Exercice 2**. Liste sans redondance des activités des entreprises.  
  Énoncé complet : 072. Solution : 193463557666227.
- **Exercice 3**. Triez la table `formation` par thème (`tid`) croissant, puis prix décroissant.  
  Énoncé complet : 025. Solution : 164626598910464.

### Restriction

- **Exercice 4**. Nom et identifiant des animateurs parisiens.  
  Énoncé complet : 081. Solution : 187585923555809.
- **Exercice 5**. Informations d'état-civil des clientes de province habitant bd Victor Hugo.  
  Énoncé complet : 014. Solution : 121547412884536.
- **Exercice 6**. Titre, prix et durée des formations durant entre 8 et 18 jours.  
  Énoncé complet : 009. Solution : 247973508743026.
- **Exercice 7**. Lignes de la table `client` où le prénom est « Pierre ».  
  Énoncé complet : 057. Solution : 90839909553096.
- **Exercice 8**. Identifiant et ville des sessions ayant débuté le 8 janvier 2021.  
  Énoncé complet : 042. Solution : 280407714100258.
- **Exercice 9**. Identifiant et date de début des sessions de 2022.  
  Énoncé complet : 054. Solution : 57086523185238.
- **Exercice 10**. Identifiant, nom et âge des animateurs sans emploi.  
  Énoncé complet : 047. Solution : 77191907184689.
- **Exercice 11**. Identifiant des sessions de Dijon, Rennes, Pau, Grenoble et Lyon.  
  Énoncé complet : 017. Solution : 199296154983057.

### Jointure

- **Exercice 12**. Identifiant et ville des sessions de la formation « Illustrator ».  
  Énoncé complet : 100. Solution : 48009407921012.
- **Exercice 13**. Identifiant, date de début et date de fin des sessions de la formation « Illustrator ».  
  Énoncé complet : 043. Solution : 74315720283551.
- **Exercice 14**. Ville et nombre d'inscrits de la session `S123`, avec le nom de son animateur responsable.  
  Énoncé complet : 027. Solution : 37656912964149.
- **Exercice 15**. Nom et prime de l'animateur responsable de la session `S123`.  
  Énoncé complet : 006. Solution : 50065234858376.
- **Exercice 16**. Nom et date d'inscription des participants à une session de Nanterre, avec l'identifiant et la date de début de celle-ci.  
  Énoncé complet : 040. Solution : 43366472939700.
- **Exercice 17**. Sessions plus suivies que la session S014, avec la différence en nombre d'inscrits.  
  Énoncé complet : 076. Solution : 15254688931755.
- **Exercice 18**. Couples d'entreprises ayant même activité, avec cette activité.  
  Énoncé complet : 003. Solution : 73069103461713.
- **Exercice 19**. Clients n'ayant réalisé aucune inscription.  
  Énoncé complet : 026. Solution : 109257705314666.

### Agrégation sans `GROUP BY`

- **Exercice 20**. Nombre moyen d'inscrits.  
  Énoncé complet : 085. Solution : 267107579243451.
- **Exercice 21**. Amplitude de la prime de responsabilité (différence entre primes maximale et minimale).  
  Énoncé complet : 059. Solution : 60095328846191.
- **Exercice 22**. Nombre de clients employés d'entreprise.  
  Énoncé complet : 086. Solution : 229235892734731.
- **Exercice 23**. Nombre de clients employés d'entreprise.  
  Énoncé complet : 075. Solution : 35875823604479.
- **Exercice 24**. Nombre d'animateurs ayant exercé la responsabilité d'au moins une session.  
  Énoncé complet : 044. Solution : 27715416342291.

### Agrégation sans `GROUP BY` imbriquée

- **Exercice 25**. Nom du responsable de la session la plus récente, avec l'identifiant et la date de début de celle-ci.  
  Énoncé complet : 079. Solution : 35947495440414.
- **Exercice 26**. Nom du responsable de la session « EMBA » la plus récente, l'identifiant, le `fid` et la date de début de celle-ci.  
  Énoncé complet : 070. Solution : 92586396903411.

###  `GROUP BY` sans `HAVING`

- **Exercice 27**. Pour chaque emploi, nombre d'animateurs qui l'occupent.  
  Énoncé complet : 039. Solution : 233808147721964.
- **Exercice 28**. Pour chaque session de Nice, moyenne d'âge des animateurs.  
  Énoncé complet : 005. Solution : 27863012067778.

### `GROUP BY` avec `HAVING`

- **Exercice 29**. Activités exercées par au moins trois entreprises.  
  Énoncé complet : 021. Solution : 258931831344925.
- **Exercice 30**. Animateurs parisiens ayant été responsables de plus de quatre sessions parisiennes, avec le nombre de celles-ci.  
  Énoncé complet : 068. Solution : 45243283356222.

### Relation symétrique

- **Exercice 31**. Raison des concurrentes de l'entreprise « L'amour en vrac ».  
  Énoncé complet : 067. Solution : 132630497279838.
- **Exercice 32**. Identifiant et raison des entreprises sans entreprises concurrentes.  
  Énoncé complet : 094. Solution : 75342239292029.
- **Exercice 33**. Nombre de concurrentes de l'entreprise « L'amour en vrac ».  
  Énoncé complet : 087. Solution : 53595474351913.

## Examen blanc
### Questions _non_ classées par difficulté

- **Exercice 34**. Pour chaque entreprise, nombre d'employés qui sont clients de la société de formation. Colonnes attendues : identifiant et raison de l'entreprise, nombre d'employés.  
  Énoncé complet : 155. Solution : 9111771762332.
- **Exercice 35**. Titre des formations sans pré-requis.  
  Énoncé complet : 165. Solution : 246080130886204.
- **Exercice 36**. Nombre de formations pour chaque thème, avec l'identifiant et le libellé de celui-ci.  
  Énoncé complet : 195. Solution : 242860797676353.
- **Exercice 37**. Pour chaque animateur ayant été responsable d'au moins 5 sessions parisiennes, nombre total de subordonnés distincts dans ces sessions, classés par nombre de subordonnés décroissant.  
  Énoncé complet : 124. Solution : 179380892567729.
- **Exercice 38**. Deux formations ont le même titre. Trouvez celui-ci, ainsi que l'identifiant de ces formations.  
  Énoncé complet : 111. Solution : 31793961828180.
- **Exercice 39**. Nombre de sessions pour chaque thème, avec l'identifiant et le libellé de celui-ci.  
  Énoncé complet : 138. Solution : 172006321856237.
- **Exercice 40**. Pourcentage de sessions placées sous la responsabilité d'une femme. La valeur cherchée doit être nommée `ratio` et comprise entre 0 et 100.  
  Énoncé complet : 182. Solution : 195629287190133.
- **Exercice 41**. Vous avez trouvé un numéro de téléphone dont manque le dernier chiffre : « 07 00 55 55 7 ». Vous ne savez pas si son possesseur est un client ou un animateur. Renvoyez la liste des possibilités. Colonnes attendues : identifiant du possesseur, nom, type (client ou animateur) et téléphone.  
  Énoncé complet : 107. Solution : 158853303138975.
