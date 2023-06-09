
# Hospital-JEE
<H1>Rapport de projet</H1>

<H2>Introduction:</H2>

On a créer une application Web JEE basée sur Spring MVC, Thylemeaf et Spring Data JPA qui permet de gérer les patients.
Notre application nous permet d'Afficher les patients - Faire la pagination - Chercher les patients - Supprimer un patient.


<H2>Partie Code:</H2>

<H3>Structure du code:</H3>

![Structure de code](g1.png)

<H3>Structure détaillé du code:</H3>

![Structure de code](g2.png)

<H3>Notre application</H3>

![Structure de code](g3.png)

<H3>PARTIE WEB: </H3>

<H4>Patient:</H4>

![Structure de code](g4.png)

<H4>Security:</H4>

![Structure de code](g5.png)


<H3>Class Patient</H3>

 L'entité possède plusieurs propriétés telles que "id", "nom", "dateNaissance", "malade" et "score".
 
@Entity : Cette annotation spécifie que la classe est une entité et doit être gérée par JPA.  
@Data : Cette annotation génère des getters et des setters pour les propriétés de la classe.  
@NoArgsConstructor : Cette annotation génère un constructeur sans arguments.  
@AllArgsConstructor : Cette annotation génère un constructeur avec tous les arguments.   
@Id : Cette annotation spécifie que le champ est la clé primaire de l'entité.  
@GeneratedValue : Cette annotation spécifie comment la clé primaire est générée.  
@NotEmpty : Cette annotation spécifie que le champ ne doit pas être vide.  
@Size : Cette annotation spécifie les contraintes de taille sur le champ.  
@Column : Cette annotation spécifie la définition de colonne pour le champ.  
@Temporal : Cette annotation spécifie le type temporel pour le champ de date.  
@DateTimeFormat : Cette annotation spécifie le format pour le champ de date.  
@DecimalMin : Cette annotation spécifie la valeur minimale pour le champ de score.  


![Structure de code](g6.png)

<H3>Templates:</H3>

![Structure de code](g7.png)

<H2>Login</H2>

La page contient un formulaire avec deux champs : "username" pour le nom d'utilisateur et "password" pour le mot de passe. Un bouton "Login" permet de soumettre le formulaire.

Il y a également une case à cocher pour se souvenir de l'utilisateur et un lien vers une page de récupération de mot de passe.

Le code inclut également des liens vers des fichiers CSS et JavaScript du framework Bootstrap pour le style de la page.

![Structure de code](g8.png)


<H2>Patients</H2>

 Les liens de pagination sont générés à l'aide de l'attribut th:each avec la variable pages. La variable status.index contient le numéro de la page actuelle, et la variable currentPage est utilisée pour mettre en évidence le lien de la page courante. L'attribut th:class est utilisé pour définir la classe du lien en fonction de la page actuelle ou non. L'attribut th:href spécifie l'URL pour chaque lien de page, en passant le numéro de la page et le mot clé de recherche en tant que paramètres de requête.
 
 
![Structure de code](g9.png)

<H2>Template</H2>

![Structure de code](g10.png)

<H2>POM.XML</H2>
La déclaration <?xml version="1.0" encoding="UTF-8"?> spécifie que le fichier est un document XML utilisant l'encodage UTF-8.  
L'élément <project> est l'élément racine du POM et contient des sous-éléments qui définissent les métadonnées du projet, les dépendances, les paramètres de construction, etc.   
L'élément <modelVersion> spécifie la version du modèle POM utilisée.  
L'élément <parent> contient des informations sur le projet parent, le cas échéant.  
Les éléments <groupId>, <artifactId> et <version> spécifient les coordonnées du projet, qui sont utilisées pour identifier de manière unique le projet dans un référentiel Maven.  
Les éléments <name> et <description> fournissent des informations sur le projet.  
L'élément <properties> définit des propriétés globales du projet qui peuvent être utilisées dans l'ensemble du POM.  
L'élément <dependencies> répertorie les dépendances du projet, qui sont automatiquement téléchargées par Maven lors de la construction du projet.  
L'élément <build> contient la configuration pour le processus de construction, tels que les plugins à utiliser et les objectifs à exécuter. Dans ce cas, il définit le plugin Maven Spring Boot utilisé pour construire et exécuter l'application Spring Boot.  

![Structure de code](g16.png)




<H1>Les Interfaces du projets:</H1>

<H2>ADMIN:</H2>

![Structure de code](g11.png)
![Structure de code](g12.png)
![Structure de code](g13.png)


<H2>User:</H2>

![Structure de code](g14.png)

<H2>Ma BDD:</H2>

![Structure de code](g15.png)

 <H1>Conclusion:</H1>
 
 la réalisation de ce projet JEE basée sur Spring MVC, Thymeleaf et Spring Data JPA a permis de développer une solution de gestion de patients complète et efficace. Grâce à cette application, les professionnels de santé peuvent gérer de manière simple et rapide les données de leurs patients.  
 L'utilisation de ces technologies a également permis de développer une application web performante et sécurisée. Nous espérons que cette solution sera utile aux professionnels de santé et aux patients, et qu'elle contribuera à améliorer la qualité des soins médicaux.
 
 <H1>Realiser par:</H1>
 <H2>HOUSSAM MESBAH</H2>
 
 



 
 
















 
