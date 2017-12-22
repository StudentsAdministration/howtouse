# How to use

How to use er en beskrivelse af hvordan du som underviser bruger materialet fra denne GitHub organization
Materialet vedrører 2. semester softewarekostruktion på kea datamatikkeruddannelsen.

## Semesterplan
Et eksempel på en semesterplan kan du se [her](https://studentsadministration.github.io/)    
Hvis du vil redigere indholdet ligger html filerne i dette repository [studentsadministration.github.io](https://github.com/StudentsAdministration/studentsadministration.github.io)

## Alt materiale
Alle blokke af lektioner (dage) har et identifikationsnummer som bruges som prefix (01_ etc.). Den første undervisningsdag er nummer 01 osv.    

Hvis du vil se alt materiale til en bestemt undervisningsgang kan du også søge på feks. [01](https://github.com/StudentsAdministration?utf8=%E2%9C%93&q=01) ligesom her.    

<a href="https://github.com/StudentsAdministration?utf8=%E2%9C%93&q=01"> <img src="https://github.com/StudentsAdministration/howtouse/blob/master/img/studentsadmin.png" width="300px" /></a>    

## Teacher Materials Branch
De fleste repositories har en branch med Underviser materialer. Det kan være øvelser, tutorials eller lignende i forskellige filformater (pdf, docx, tex etc.). Det kan også være mine noter til den pågældende undervisningsgang.

Teacher Materials findes ved at skifte "branch" i øverste venstre hjørne.

![branch chooser](https://github.com/StudentsAdministration/howtouse/blob/master/img/branch.png)

## Agendaer 
[<sub>Link til alle agendaer</sub>](https://github.com/StudentsAdministration?utf8=%E2%9C%93&q=agenda&type=&language=)    

Agenderne er "drejebogen" for undervisningen.    
Det er her du skal kigge hvis du vil have et overblik over hvad jeg har lavet den pågældende dag.    

Alle agendaer er navngivet efter systemet 01_agenda, 02_agenda osv.    

Hvis du vil se alle 26 agendaer jeg har brugt i dette semester kan du desuden søge på [agenda](https://github.com/StudentsAdministration?utf8=✓&q=agenda&type=&language=)

## Øvelser
[<sub>Link til alle øvelser</sub>](https://github.com/StudentsAdministration?utf8=%E2%9C%93&q=exercise&type=&language=)

Hvis du vil se alle øvelser jeg har brugt i dette semester kan du søge på [exercise](https://github.com/StudentsAdministration?utf8=✓&q=exercise&type=&language=)    

### Løsninger til øvelserne
I mange af øvelserne ligger der en løsning i en __solution branch__. For eksempel har øvelse [03_create_spring_application](https://github.com/StudentsAdministration/03_create_spring_application/tree/master) en løsning liggende i en **_solution.md_** fil i [solution branch](https://github.com/StudentsAdministration/03_create_spring_application/tree/solution).    
Løsningerne er primært tænkt som hjælp til undervisere, men man kan selvfølgelig bruge dem som man finder pædagogisk bedst.

## Curriculum
Semesterets pensum kan du finde ved at kigge i listen [Curriculum](https://github.com/StudentsAdministration/curriculum).

## Lektionernes formål
Det følgende giver et overblik over hver lektions formål, og hvilke emner jeg har berørt den pågældende dag.    

### [Dag 1](https://github.com/StudentsAdministration?utf8=✓&q=01)
#### Formål
* Installer IntelliJ
* Få deres hjerner sporet ind på at vi starter igen gennem øvelser og snak
* Give et overblik over dette semester
* Start på Fitnees Øvelsen

### [Dag 2](https://github.com/StudentsAdministration?utf8=✓&q=02)
#### Formål
* Genopfriskning af 1. semesters emner gennem gruppearbejde med Fitness Øvelsen.

### [Dag 3](https://github.com/StudentsAdministration?utf8=✓&q=03)

#### Formål

* De skal kunne lave et "Sprig Boot Initializer" project
* De skal kunne lave en controller
* De skal kunne lave en metode der returnere en index.html side
* de skal kunne lave en index.html side (de ved ikke noget om html endnu).
* De skal kunne se deres website i deres browser på http://loalhost:8080

#### Materialer

* [03_agenda](https://github.com/StudentsAdministration/03_agenda)
* [03_hello_spring](https://github.com/StudentsAdministration/03_hello_spring)
   * [Branch: Teacher_materials](https://github.com/StudentsAdministration/03_hello_spring/tree/teacher_materials)
* [03_my_first_website](https://github.com/StudentsAdministration/03_my_first_website)
* [03_spring_framework_elements_explained](https://github.com/StudentsAdministration/03_spring_framework_elements_explained)
* [Øvelse: 03_create_spring_application](https://github.com/StudentsAdministration/03_create_spring_application)
   * [Branch: solution](https://github.com/StudentsAdministration/03_create_spring_application/blob/solution/solution.md)


### [Dag 4](https://github.com/StudentsAdministration/04_agenda)

#### Formål

* At lære lige præcis nok HTML og CSS til at komme igang.

#### Materialer

* [04_agenda](https://github.com/StudentsAdministration/04_agenda)
* [Øvelse: Warm Up](https://github.com/StudentsAdministration/04_agenda)
* [Øvelse: Exercise 2](https://github.com/StudentsAdministration/04_exercise_2)
* [Øvelser: w3schools html exercises](https://www.w3schools.com/html/exercise.asp)
* [Øvelser: w3schools css exercises](https://www.w3schools.com/css/exercise.asp)
* [Øvelse: 02 Exercise 3: HIT](https://github.com/StudentsAdministration/04_exercise_3/blob/master/readme.md)

_Note: Som underviser skal du være opmærksom på at at html sider i en Spring Boot Application har et anstrængt forhold til html5 tags. Xhtml tags understøttes. (Dette kan dog have ændret sig i de efterfølgende semestre)_ 

### [Dag 5](https://github.com/StudentsAdministration/05_agenda)    
#### Formål
* Lave en index.html side med en liste af Studerende som denne, der returneres og fyldes med data fra controlleren:
<img src="https://github.com/StudentsAdministration/05_agenda/blob/master/students_index.png" width="300px" />     

#### Emner i undervisningen
* HTML - Tabeller
* CSS - Meget simpel
    * De får noget af os og vi forklare koncepterne.
* Thymeleaf    
 ````  th:text="$(student.firstName)" ````   
 ````  th:each="student: ${students}"````     
 

### [Dag 6](https://github.com/StudentsAdministration/06_agenda)
#### Formål 
* Fortsættelse af sidste gang med resten af CRUD medtoderne og lave disse sider:
<img src="/img/create.png" width="300px" />
<img src="/img/details.png" width="300px" />
<img src="/img/update.png" width="300px" />
<img src="/img/delete.png" width="300px" />    

#### Emner i undervisningen    
* Html tags including the Form Tag
* Styling through CSS
* In both the HTML and CSS case, you will learn through the LTS method (Learning through stealing)
* Sending data from the Controller by adding it to the "Model Object".
* Recieving and displaying data in the View using Thymeleaf.
* Sending data from the html page back to the Controller.
* Working with dates in the view and in the model
* Routing ````GetMapping()```` and ````PostMapping()````    
* Thymeleaf    
   ````   th:Field="$(student.firstName)"  ````   
   
   ````   
         <form method="post" th:action="@{/create}">
            <input type="text" th:field="${student.name}" />
          </form>  
   ````  

### [Dag 7](https://github.com/StudentsAdministration/07_agenda)
#### Formål
* Fortsættelse af dag 6
* Få det de mangler af det fra sidst på plads. 

#### Emner i undervisningen
  
### [Dag 8](https://github.com/StudentsAdministration/08_agenda)
#### Formål 
* Tilføje repositories til StudentsAdministration applikationen.
* Lære om interfaces og fordelene ved disse
   * Udviklingsmetode (en kontrakt)
   * StudentsInMemoryRepository
   * StudentsTextFileRepository
   * Senere StudentsDbRepository

### [Dag 9](https://github.com/StudentsAdministration/09_agenda)
#### Formål 
* Fortsættelse af dag 8
* Få det de mangler af det fra sidst på plads. 

### [Dag 10](https://github.com/StudentsAdministration/10_agenda)
#### Formål
* Introduktion til Databaser
* Opret en GigaHost konto
* opret en dabase
* Select i IntelliJ eller DataGrib
   * Select
   * Insert
   * Delete
   * (evt. update)

### Dag 11
**_TODO: Oversæt til eng_**
### Dag 12
### Dag 13
### Dag 14
### Dag 15
### Dag 16
### Dag 17
### Dag 18
**_TODO: Oversæt til eng_**
### Dag 19
### Dag 20
### Dag 21
### Dag 22
### Dag 23
### Dag 24
### Dag 25
### Dag 26


## Bidrag til materialet
Hvis i har nogle forslag, ændringer, rettelser, øvelser, nye emner der kan medtages så sig til. Den smarte måde er at "forke" et repository, lave ændringer/forbedringer og herefter lave et pull request ([i kan se her hvordan det gøres](https://github.com/StudentsAdministration/git_pull_request))    

## #TODO
Todos in all repos

* Git skal includeres i de første lektioner.
* [#3 Annotations explained - skriv det](https://github.com/StudentsAdministration/03_annotations/blob/master/README.md)
* [#4 Html, css (lav øvelser om table og div tags)](https://github.com/StudentsAdministration/04_agenda/blob/master/README.md)
* [#5 Thyleaf (find literatur)](https://github.com/StudentsAdministration/05_agenda/blob/master/README.md)
* [#6 find literatur der forklare Model objectet] (https://github.com/StudentsAdministration/06_tutorial_students_list/blob/master/README.md)

* Skriv literatur om model, model.addAttribute, thymeleaf ${stu.studentId} (passer til lek 05)

* Lav tekst der forklarer @Annontations i forhold til Spring - Passer til lek 03-10

* #16 Øvelse om at vise enrollments på details siden for en studerende. Includere mange til mange forbindelse mellem studerende og courses i students_courses tabellen og enrollments klassen

* [SpringMvcStepByStep](https://github.com/StudentsAdministration/SpringMvcStepByStep) mulig literatur. Udemy kursus [Spring MVC For Beginners : Build Java Web App in 25 Steps](https://www.udemy.com/spring-mvc-tutorial-for-beginners-step-by-step/?altsc=366608) 

* [GitIt skal evt. mmd](https://github.com/StudentsAdministration/GitIt/blob/master/README.md)

* [Step by step - MysqlDump explanation]()

* Includer Singleton pattern i jdbc / Database undervisningen 



_<div align="right">&copy; clbo@kea.dk</div>_
