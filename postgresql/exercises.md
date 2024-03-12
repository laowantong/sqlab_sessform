
## Tutoriel
### Projection

- **Exercice 1**. Donnez l'identifiant, la raison, l'activité et la ville de toutes les entreprises.  
  Énoncé complet : `call decrypt(096)`. Solution : `call decrypt(277188057325886)`.
- **Exercice 2**. Liste sans redondance des activités des entreprises.  
  Énoncé complet : `call decrypt(072)`. Solution : `call decrypt(193463557666227)`.
- **Exercice 3**. Triez la table `formation` par thème (`tid`) croissant, puis prix décroissant, puis nombre de jours croissant.  
  Énoncé complet : `call decrypt(025)`. Solution : `call decrypt(203663835521703)`.

### Restriction

- **Exercice 4**. Nom et identifiant des animateurs parisiens.  
  Énoncé complet : `call decrypt(081)`. Solution : `call decrypt(187585923555809)`.
- **Exercice 5**. Informations d'état-civil des clientes de province habitant bd Victor Hugo.  
  Énoncé complet : `call decrypt(014)`. Solution : `call decrypt(121547412884536)`.
- **Exercice 6**. Titre, prix et durée des formations durant entre 8 et 18 jours.  
  Énoncé complet : `call decrypt(009)`. Solution : `call decrypt(248047814572261)`.
- **Exercice 7**. Lignes de la table `client` où le prénom est « Pierre ».  
  Énoncé complet : `call decrypt(057)`. Solution : `call decrypt(90839909553096)`.
- **Exercice 8**. Identifiant et ville des sessions ayant débuté le 8 janvier 2021.  
  Énoncé complet : `call decrypt(042)`. Solution : `call decrypt(280810661380076)`.
- **Exercice 9**. Identifiant et date de début des sessions de 2022.  
  Énoncé complet : `call decrypt(054)`. Solution : `call decrypt(56523494026760)`.
- **Exercice 10**. Identifiant, nom et âge des animateurs sans emploi.  
  Énoncé complet : `call decrypt(047)`. Solution : `call decrypt(77191907184689)`.
- **Exercice 11**. Identifiant des sessions de Dijon, Rennes, Pau, Grenoble et Lyon.  
  Énoncé complet : `call decrypt(017)`. Solution : `call decrypt(198349216940721)`.

### Jointure

- **Exercice 12**. Identifiant et ville des sessions de la formation « Illustrator ».  
  Énoncé complet : `call decrypt(100)`. Solution : `call decrypt(50068316509299)`.
- **Exercice 13**. Identifiant, date de début et date de fin des sessions de la formation « Illustrator ».  
  Énoncé complet : `call decrypt(043)`. Solution : `call decrypt(86020561798569)`.
- **Exercice 14**. Ville et nombre d'inscrits de la session `S123`, avec le nom de son animateur responsable.  
  Énoncé complet : `call decrypt(027)`. Solution : `call decrypt(37656912964149)`.
- **Exercice 15**. Nom et prime de l'animateur responsable de la session `S123`.  
  Énoncé complet : `call decrypt(006)`. Solution : `call decrypt(50472338226093)`.
- **Exercice 16**. Nom et date d'inscription des participants à une session de Nanterre, avec l'identifiant et la date de début de celle-ci.  
  Énoncé complet : `call decrypt(040)`. Solution : `call decrypt(42814922775400)`.
- **Exercice 17**. Sessions plus suivies que la session S014, avec la différence en nombre d'inscrits.  
  Énoncé complet : `call decrypt(076)`. Solution : `call decrypt(14765676305589)`.
- **Exercice 18**. Couples d'entreprises ayant même activité, avec cette activité.  
  Énoncé complet : `call decrypt(003)`. Solution : `call decrypt(73069103461713)`.
- **Exercice 19**. Clients n'ayant réalisé aucune inscription.  
  Énoncé complet : `call decrypt(026)`. Solution : `call decrypt(109257705314666)`.

### Agrégation sans `GROUP BY`

- **Exercice 20**. Nombre moyen d'inscrits.  
  Énoncé complet : `call decrypt(085)`. Solution : `call decrypt(267012322877659)`.
- **Exercice 21**. Amplitude de la prime de responsabilité (différence entre primes maximale et minimale).  
  Énoncé complet : `call decrypt(058)`. Solution : `call decrypt(1889179276061)`.
- **Exercice 22**. Nombre de clients employés d'entreprise.  
  Énoncé complet : `call decrypt(086)`. Solution : `call decrypt(229235892734731)`.
- **Exercice 23**. Nombre de clients employés d'entreprise.  
  Énoncé complet : `call decrypt(075)`. Solution : `call decrypt(35875823604479)`.
- **Exercice 24**. Nombre d'animateurs ayant exercé la responsabilité d'au moins une session.  
  Énoncé complet : `call decrypt(044)`. Solution : `call decrypt(41309657266481)`.

### Agrégation sans `GROUP BY` imbriquée

- **Exercice 25**. Nom du responsable de la session la plus récente, avec l'identifiant et la date de début de celle-ci.  
  Énoncé complet : `call decrypt(079)`. Solution : `call decrypt(37273556577796)`.
- **Exercice 26**. Nom du responsable de la session « EMBA » la plus récente, l'identifiant, le `fid` et la date de début de celle-ci.  
  Énoncé complet : `call decrypt(070)`. Solution : `call decrypt(92758902033365)`.

###  `GROUP BY` sans `HAVING`

- **Exercice 27**. Pour chaque emploi, nombre d'animateurs qui l'occupent.  
  Énoncé complet : `call decrypt(039)`. Solution : `call decrypt(233808147721964)`.
- **Exercice 28**. Pour chaque session de Nice, moyenne d'âge des animateurs.  
  Énoncé complet : `call decrypt(005)`. Solution : `call decrypt(27307432946912)`.

### `GROUP BY` avec `HAVING`

- **Exercice 29**. Activités exercées par au moins trois entreprises.  
  Énoncé complet : `call decrypt(021)`. Solution : `call decrypt(258931831344925)`.
- **Exercice 30**. Animateurs parisiens ayant été responsables de plus de quatre sessions parisiennes, avec le nombre de celles-ci.  
  Énoncé complet : `call decrypt(068)`. Solution : `call decrypt(48024087451568)`.

### Relation symétrique

- **Exercice 31**. Raison des concurrentes de l'entreprise « L'amour en vrac ».  
  Énoncé complet : `call decrypt(067)`. Solution : `call decrypt(132630497279838)`.
- **Exercice 32**. Identifiant et raison des entreprises sans entreprises concurrentes.  
  Énoncé complet : `call decrypt(094)`. Solution : `call decrypt(75342239292029)`.
- **Exercice 33**. Nombre de concurrentes de l'entreprise « L'amour en vrac ».  
  Énoncé complet : `call decrypt(087)`. Solution : `call decrypt(53595474351913)`.

## Examen blanc
### Questions _non_ classées par difficulté

- **Exercice 34**. Pour chaque entreprise, nombre d'employés qui sont clients de la société de formation. Colonnes attendues : identifiant et raison de l'entreprise, nombre d'employés.  
  Énoncé complet : `call decrypt(155)`. Solution : `call decrypt(9111771762335)`.
- **Exercice 35**. Titre des formations sans pré-requis.  
  Énoncé complet : `call decrypt(165)`. Solution : `call decrypt(245953508436144)`.
- **Exercice 36**. Nombre de formations pour chaque thème, avec l'identifiant et le libellé de celui-ci.  
  Énoncé complet : `call decrypt(195)`. Solution : `call decrypt(212158702623071)`.
- **Exercice 37**. Pour chaque animateur ayant été responsable d'au moins 5 sessions parisiennes, nombre total de subordonnés distincts dans ces sessions, classés par nombre de subordonnés décroissant.  
  Énoncé complet : `call decrypt(124)`. Solution : `call decrypt(181703762557071)`.
- **Exercice 38**. Deux formations ont le même titre. Trouvez celui-ci, ainsi que l'identifiant de ces formations.  
  Énoncé complet : `call decrypt(111)`. Solution : `call decrypt(31366715971326)`.
- **Exercice 39**. Nombre de sessions pour chaque thème, avec l'identifiant et le libellé de celui-ci.  
  Énoncé complet : `call decrypt(138)`. Solution : `call decrypt(158529861132039)`.
- **Exercice 40**. Pourcentage de sessions placées sous la responsabilité d'une femme. La valeur cherchée doit être nommée `ratio` et comprise entre 0 et 100.  
  Énoncé complet : `call decrypt(182)`. Solution : `call decrypt(194375321203169)`.
- **Exercice 41**. Vous avez trouvé un numéro de téléphone dont manque le dernier chiffre : « 07 00 55 55 7 ». Vous ne savez pas si son possesseur est un client ou un animateur. Renvoyez la liste des possibilités. Colonnes attendues : identifiant du possesseur, nom, type (client ou animateur) et téléphone.  
  Énoncé complet : `call decrypt(107)`. Solution : `call decrypt(158853303138975)`.
