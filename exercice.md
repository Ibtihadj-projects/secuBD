#Les attaques
|Types|Attaques|
|-----|--------|
|Le phishing|On distngue l'ancien procédé qui consiste à envoyer des ficfiers frauduleux par hasard et plus récemment le **spear phishing** qui s'attaque à des sujets sur lesquels des recherches ont été faites au préalable |
|Les malwares|ransomwares, adwares, spywares, chevaux de troie|
|Le deni de service|__|
|Les attaques visant les mots de passe|espionnage des données sur le réseau, ingénieurie sociale, attaque par brute force, attaques par dictionnaires|
|L'homme du milieu|sniffing, evil twin qu consiste à créer un faux point accès wifi, usurpation de données|

Les attaques pouvant compromettre la base de sonnées sont: l'homme du milieu(par usurpation), le deni de service qui rendrait inaccessible la base de données.

#Emplacements et extensions des fichiers de données

|SGBD|Emplacement|Extension|
|----|-----------|---------|
|Oracle|__|.dbf|
|SQL Server|C:\Program Files\Microsoft SQL Server\MSSQL{n,n}.MyInstance\ |.mdf|
|PostgreSQL|C:\Program Files\PostgreSQL\numéro_version\data\ |.psql|
|MySQL|C:\Program Files\MySQL\MySQL Server 5.5\data|.frm avec le moteur InnoDB et .myl avec le moteur Mysam|

#Politique de confidentialité Isec

Le site web Isec Formation est détenu par ISEC FORMATION, qui est un contrôleur de données de vos données personnelles.

Nous avons adopté cette politique de confidentialité, qui détermine la manière dont nous traitons les informations collectées par Isec Formation, qui fournit également les raisons pour lesquelles nous devons collecter certaines données personnelles vous concernant. Par conséquent, vous devez lire cette politique de confidentialité avant d'utiliser le site web de Isec Formation.
Nous prenons soin de vos données personnelles et nous nous engageons à en garantir la confidentialité et la sécurité.

Les informations personnelles que nous collectons :

Lorsque vous visitez le Isec Formation, nous recueillons automatiquement certaines informations sur votre appareil, notamment des informations sur votre navigateur web, votre adresse IP, votre fuseau horaire et certains des cookies installés sur votre appareil. En outre, lorsque vous naviguez sur le site, nous recueillons des informations sur les pages web ou les produits individuels que vous consultez, sur les sites web ou les termes de recherche qui vous ont renvoyé au site et sur la manière dont vous interagissez avec le site. Nous désignons ces informations collectées automatiquement par le terme "informations sur les appareils". En outre, nous pourrions collecter les données personnelles que vous nous fournissez (y compris, mais sans s'y limiter, le nom, le prénom, l'adresse, les informations de paiement, etc.) lors de l'inscription afin de pouvoir exécuter le contrat.

Pourquoi traitons-nous vos données ?

Notre priorité absolue est la sécurité des données des clients et, à ce titre, nous ne pouvons traiter que des données minimales sur les utilisateurs, uniquement dans la mesure où cela est absolument nécessaire pour maintenir le site web. Les informations collectées automatiquement sont utilisées uniquement pour identifier les cas potentiels d'abus et établir des informations statistiques concernant l'utilisation du site web. Ces informations statistiques ne sont pas autrement agrégées de manière à identifier un utilisateur particulier du système.

Vous pouvez visiter le site web sans nous dire qui vous êtes ni révéler d'informations, par lesquelles quelqu'un pourrait vous identifier comme un individu spécifique et identifiable. Toutefois, si vous souhaitez utiliser certaines fonctionnalités du site web, ou si vous souhaitez recevoir notre lettre d'information ou fournir d'autres détails en remplissant un formulaire, vous pouvez nous fournir des données personnelles, telles que votre e-mail, votre prénom, votre nom, votre ville de résidence, votre organisation, votre numéro de téléphone. Vous pouvez choisir de ne pas nous fournir vos données personnelles, mais il se peut alors que vous ne puissiez pas profiter de certaines fonctionnalités du site web. Par exemple, vous ne pourrez pas recevoir notre bulletin d'information ou nous contacter directement à partir du site web.

Vos droits :

Si vous êtes un résident européen, vous disposez des droits suivants liés à vos données personnelles :
Le droit d'être informé.
Le droit d'accès.
Le droit de rectification.
Le droit à l'effacement.
Le droit de restreindre le traitement.
Le droit à la portabilité des données.
Le droit d'opposition.
Les droits relatifs à la prise de décision automatisée et au profilage.

Si vous souhaitez exercer ce droit, veuillez nous contacter via les coordonnées ci-dessous.
En outre, si vous êtes un résident européen, nous notons que nous traitons vos informations afin d'exécuter les contrats que nous pourrions avoir avec vous (par exemple, si vous passez une commande par le biais du site), ou autrement pour poursuivre nos intérêts commerciaux légitimes énumérés ci-dessus. En outre, veuillez noter que vos informations pourraient être transférées en dehors de l'Europe, y compris au Canada et aux États-Unis.

Liens vers d'autres sites web :

Notre site web peut contenir des liens vers d'autres sites web qui ne sont pas détenus ou contrôlés par nous. Sachez que nous ne sommes pas responsables de ces autres sites web ou des pratiques de confidentialité des tiers. Nous vous encourageons à être attentif lorsque vous quittez notre site web et à lire les déclarations de confidentialité de chaque site web susceptible de collecter des informations personnelles.
Sécurité de l'information :
Nous sécurisons les informations que vous fournissez sur des serveurs informatiques dans un environnement contrôlé et sécurisé, protégé contre tout accès, utilisation ou divulgation non autorisés. Nous conservons des garanties administratives, techniques et physiques raisonnables pour nous protéger contre tout accès, utilisation, modification et divulgation non autorisés des données personnelles sous son contrôle et sa garde. Toutefois, aucune transmission de données sur Internet ou sur un réseau sans fil ne peut être garantie.

Divulgation légale :

Nous divulguerons toute information que nous collectons, utilisons ou recevons si la loi l'exige ou l'autorise, par exemple pour nous conformer à une citation à comparaître ou à une procédure judiciaire similaire, et lorsque nous pensons de bonne foi que la divulgation est nécessaire pour protéger nos droits, votre sécurité ou celle d'autrui, enquêter sur une fraude ou répondre à une demande du gouvernement.
 Source:[Isec site]:(https://isec.re/politique-de-confidentialite)

-------------------------------------------------

#Notion de droits sous postgresql 15

>l existe un certain nombre de droits différents : SELECT, INSERT, UPDATE, DELETE, TRUNCATE, REFERENCES, TRIGGER, CREATE, CONNECT, TEMPORARY, EXECUTE, USAGE, SET et ALTER SYSTEM. Les droits applicables à un objet particulier varient selon le type d'objet (table, fonction...). Plus de détails sur la signification de ces droits sont donnés ci-dessous. La section et les chapitres suivants présentent l'utilisation de ces droits.
Le droit de modifier ou détruire un objet est inhérent au propriétaire de l'objet et ne peut ni être donné ni être enlevé. Néanmoins, comme tous les droits, il peut être hérité pour les membres du rôle propriétaire)

Un objet peut se voir affecter un nouveau propriétaire avec la commande ALTER correspondant à l'objet, par exemple

ALTER TABLE nom_table OWNER TO nouveau_propriétaire;
Les superutilisateurs peuvent toujours le faire. Les rôles ordinaires ne peuvent le faire que s'ils sont le propriétaire actuel de l'objet (ou un membre du rôle propriétaire) et un membre du nouveau rôle propriétaire.

La commande GRANT est utilisée pour accorder des droits. Par exemple, si joe est un rôle et comptes une table, le droit de modifier la table comptes peut être accordé à joe avec :

GRANT UPDATE ON comptes TO joe;
Écrire ALL à la place d'un droit spécifique accorde tous les droits applicables à ce type d'objet.

Le nom de « rôle » spécial PUBLIC peut être utilisé pour donner un droit à tous les rôles du système. De plus, les rôles de type « group » peuvent être configurés pour aider à la gestion des droits quand il y a beaucoup d'utilisateurs dans une base -- pour les détails, voir Chapitre 22.

Pour révoquer un droit précédemment donné, on utilise la commande nommée REVOKE, comme dans l'exemple ci-dessous :

REVOKE ALL ON comptes FROM PUBLIC;
Habituellement, seul le propriétaire de l'objet ou un superutilisateur peuvent accorder ou révoquer les droits sur un objet. Néanmoins, il est possible de donner un droit « avec possibilité de transmission »(« with grant option »), qui donne à celui qui le reçoit le droit de donner ce droit à d'autres. Si cette option est ensuite révoquée, alors tous ceux qui ont reçu ce droit par cet utilisateur(directement ou indirectement via la chaîne des dons) perdent ce droit. Pour les détails, voir les pages de références GRANT et REVOKE.

Le propriétaire d'un objet peut décider de révoquer ses propres droits standards. Par exemple, il peut rendre une table en lecture seule pour eux comme pour les autres. Mais les propriétaires sont toujours traités comme ayant le droit de donner des droits, pour qu'ils puissent toujours retrouver leur anciens droits.

Les droits disponibles sont :

SELECT
Autorise SELECT de n'importe quelle colonne, ou colonnes, désignée(s) d'une table, vue, vue matérialisée ou tout autre objet utilisable comme une table. Permet aussi l'utilisation de COPY TO. Ce droit est aussi nécessaire pour référencer les valeurs actuelles d'une colonne dans UPDATE ou DELETE. Pour les séquences, ce droit permet aussi d'utiliser la fonction currval. Pour les « Large Objects », ce droit permet de lire l'objet binaire.

INSERT
Permet l'INSERT d'une nouvelle ligne dans une table, vue, etc. Peut être accordé sur des colonnes spécifiques, auquel cas seules ces colonnes pourront être affectées dans l'ordre INSERT (les autres commandes recevront alors les valeurs par défaut). Permet aussi d'utiliser COPY FROM.

UPDATE
Autorise l'UPDATE de n'importe quelle colonne, ou colonnes, désignée(s) d'une table, vue, etc.(En pratique, toute commande UPDATE non triviale requiert en plus le droit SELECT puisqu'il faut se référer aux colonnes de la table pour déterminer les lignes à mettre à jour et/ou calculer les nouvelles valeurs des colonnes.) SELECT ... FOR UPDATE et SELECT ... FOR SHARE requièrent aussi ce droit sur au moins une colonne, en plus du droit SELECT. Pour les séquences, ce droit autorise l'usage des fonctions nextval et setval. Pour les « Large Objects », ce droit permet d'écrire dans l'objet ou de le tronquer.

DELETE
Permet le DELETE d'une ligne dans une table, vue, etc. (En pratique, toute commande DELETE non triviale nécessite aussi le droit SELECT puisqu'il faut lire les colonnes de la table pour déterminer les lignes à supprimer.)

TRUNCATE
Permet TRUNCATE sur une table.

REFERENCES
Permet la création de clés étrangères référençant une table, ou des colonnes spécifiques d'une table.

TRIGGER
Permet la création d'un trigger sur une table, vue, etc.

CREATE
Pour les bases de données, autorise la création de nouveaux schémas et publications dans la base, et autorise l'installation d'extensions de confiance dans la base de données.

Pour les schémas, autorise la création de nouveaux objets dans le schéma. Pour renommer un objet existant, vous devez posséder l'objet et posséder ce droit pour le schéma de l'objet.

Pour les tablespaces, permet de créer des tables, index et fichiers temporaires dans le tablespace, et de créer des bases de données ayant ce tablespace comme tablespace par défaut.

Notez que révoquer ce droit ne modifiera pas l'emplacement des objets.

CONNECT
Permet au bénéficiaire de ce droit de se connecter à la base de données. Ce droit est vérifié au démarrage de la connexion(en plus de la vérification de toute restriction imposée par le fichier pg_hba.conf).

TEMPORARY
Permet aux tables temporaires d'être créées dans la base de données.

EXECUTE
Permet d'appeler une fonction ou procédure, y compris en utilisant des opérateurs implémentés par-dessus la fonction. C'est le seul type de droit applicable aux fonctions et procédures.

USAGE
Pour les langages procéduraux, permet d'utiliser le langage pour la création de fonctions. C'est le seul type de droit applicable aux langages procéduraux.

Pour les schémas, permet l'accès aux objets contenus dans le schéma (à supposer que les droit d'accès requis par les objets soient aussi respectés). Cela autorise essentiellement le bénéficiaire à « rechercher » des objets dans le schéma. Sans ce droit, il reste possible de voir les noms des objets, par exemple en consultant les catalogues système. Après révocation de ce droit, les sessions existantes peuvent avoir des ordres ayant précédemment effectué cette recherche, donc ce n'est pas une manière totalement sûre d'interdire l'accès à un objet.

Pour les séquences, permet l'utilisation des fonctions currval et nextval.

Pour les types et domaines, permet l'utilisation du type ou domaine dans la création de tables, fonctions et autres objets. (Notez que ce droit ne contrôle pas l'« utilisation » de ce type, comme les valeurs apparaissant dans les requêtes. Il se limite à interdire la création d'objets qui dépendent de ce type. Le but principal de ce droit est de contrôler quels utilisateurs peuvent créer des dépendances envers un type, qui pourraient empêcher le propriétaire de modifier le type plus tard.)

Pour les foreign data wrappers, permet la création de nouveaux serveurs avec ce wrapper.

Pour les serveurs distants (foreign servers), permet la création de tables distantes utilisant le serveur. Les bénéficiaires du droit peuvent créer, modifier, supprimer leurs propres correspondances d'utilisateurs (user mappings) associées à ce serveur.

SET
Permet la configuration d'un paramètre à une nouvelle valeur dans la session en cours. (Bien que ce droit puisse être donné pour tout paramètre, ce ne serait pas sensé sauf pour les paramètres qui nécessitent l'attribut SUPERUSER pour le configurer.)

ALTER SYSTEM
Permet la configuration d'un paramètre du serveur avec une nouvelle valeur en utilisant la commande ALTER SYSTEM.

Les droits requis par d'autres commandes sont listés sur la page de référence de la commande.

Par défaut, PostgreSQL accorde des droits sur certains types d'objets à PUBLIC dès la création des objets. Aucun droit n'est accordé à PUBLIC par défaut sur les tables, colonnes de table, séquences, foreign data wrappers, serveurs distants, large objects, schémas, tablespaces et paramètres de configuration. Pour les autres types d'objets, les droits par défaut accordés à PUBLIC sont les suivants : sur les bases de données : les droits CONNECT et TEMPORARY(création de table temporaire) ; sur les fonctions et procédures : le droit EXECUTE  ; et sur les langages et types de données (y compris les domaines) : le droit USAGE. Bien sûr, le propriétaire de l'objet peut révoquer, à l'aide de la commande REVOKE, les droits par défaut comme ceux expressément accordés. (Pour une sécurité maximale, ordonnez REVOKE dans la même transaction que celle qui crée l'objet ; il n'y a alors aucune fenêtre où un autre utilisateur peut utiliser l'objet.) Ces droits par défaut peuvent aussi être remplacés avec la commande ALTER DEFAULT PRIVILEGES.

#La norme sql

SQL signifie langage de requête structuré (Structured Query Language). SQL est un langage de programmation standard spécialement conçu pour stocker, extraire, gérer ou manipuler les données à l'intérieur d'un système de gestion de bases de données relationnelles (SGBDR). SQL est devenu une norme ISO en 1987.

SQL est le langage de base de données le plus largement mis en oeuvre et soutenu par les systèmes de base de données relationnelles populaires, comme MySQL, SQL Server, et Oracle. Cependant, certaines fonctionnalités de la norme SQL sont implémentées différemment dans différents systèmes de bases de données.

SQL a été développé à l'origine par IBM au début des années 1970. Initialement, il s’appelait SEQUEL (Structured English Query Language), qui a ensuite été remplacé par SQL

#Version actuelle de sql

>__
#SGBD et leurs versions de SQL

|SGBD|Version SQL|
|----|-----------|
|Oracle|__|
|SQL server|__|
|mySQL|__|
|PostgreSQL|__|