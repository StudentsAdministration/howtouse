# How to use

How to use er en beskrivelse af hvordan du som underviser bruger materialet fra denne GitHub organization
Materialet vedrører 2. semester softewarekostruktion på kea datamatikkeruddannelsen.

## Semesterplan
Et eksempel på en semesterplan kan du se [her](https://studentsadministration.github.io/)    
Hvis du vil redigere indholdet ligger html filerne i dette repository [studentsadministration.github.io](https://github.com/StudentsAdministration/studentsadministration.github.io)

## Alt materiale
Alle blokke af lektioner (dage) har et identifikationsnummer. Den første undervisningsdag er nummer 01 osv. 
Prefixet (01_ etc.) gør at alt materiale til en specifik undervisningsgang kan findes ved at søge efter f.eks. 01.     

Hvis du vil se alt materiale til en bestemt undervisningsgang kan du også søge på feks. [01](https://github.com/StudentsAdministration?utf8=%E2%9C%93&q=01) ligesom her.    

<img src="https://github.com/StudentsAdministration/howtouse/blob/master/img/studentsadmin.png" width="300px" />

## Agendaer
Agenderne er "drejebogen" for undervisningen.    
Det er her du skal kigge hvis du vil have et overblik over hvad jeg har lavet den pågældende dag.    

Alle agendaer er navngivet efter systemet 01_agenda, 02_agenda osv.    

Hvis du vil se alle 26 agendaer jeg har brugt i dette semester kan du desuden søge på [agenda](https://github.com/StudentsAdministration?utf8=✓&q=agenda&type=&language=)

## Øvelser
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
* Gruppearbejde med Fitness Øvelsen
### [Dag 3](https://github.com/StudentsAdministration?utf8=✓&q=03)
#### Formål
* De skal kunne lave et "Sprig Boot Initializer" project
* De skal kunne lave en controller
* De skal kunne lave en metode der returnere en index.html side
* de skal kunne lave en index.html side (de ved ikke noget om html endnu).
* De skal kunne se deres website i deres browser på http://loalhost:8080

### [Dag 4](https://github.com/StudentsAdministration/04_agenda)
#### Formål
* At lære lige præcis nok HTML og CSS til at komme igang.

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

### [Dag 6](https://github.com/StudentsAdministration/06_agenda)
#### Formål 
* Fortsættelse af sidste gang

### [Dag 7](https://github.com/StudentsAdministration/07_agenda)
#### Formål
* Få de resterende Crud metoder (Create, readone, update, delete) til at virke til at fungere, der skrives stadig til en ArrayList

#### Emner i undervisningen
* Thymeleaf    
````   th:Field="$(student.firstName)"  ````     
  
  
### Dag 8
#### Formål 
* Fortsættelse af sidste gang

### Dag 9
#### Formål 
* Repositories
* Interfaces
### Dag 10
### Dag 11
### Dag 12
### Dag 13
### Dag 14
### Dag 15
### Dag 16
### Dag 17
### Dag 18
### Dag 19
### Dag 20
### Dag 21
### Dag 22
### Dag 23
### Dag 24
### Dag 25
### Dag 26


## Bidrag til materialet
Hvis i har nogle forslag, ændringer, rettelser, øvelser, nye emner der kan medtages så sig til. Den smarte måde er at "forke" et repository, lave ændringer/forbedringer og herefter lave et pull request ([i kan se her hvordan det gøres](https://help.github.com/articles/creating-a-pull-request-from-a-fork/))    

## #TODO
Todos in all repos

* Git skal includeres i de første lektioner.
* [#3 Annotations explained - skriv det](https://github.com/StudentsAdministration/03_annotations/blob/master/README.md)
* [#4 Html, css (lav øvelser om table og div tags)](https://github.com/StudentsAdministration/04_agenda/blob/master/README.md)
* [#5 Thyleaf (find literatur)](https://github.com/StudentsAdministration/05_agenda/blob/master/README.md)

* [#6 Students List Tutorial](https://github.com/StudentsAdministration/06_tutorial_students_list/blob/master/README.md)
* [#6 find literatur der forklare Model objectet] (https://github.com/StudentsAdministration/06_tutorial_students_list/blob/master/README.md)

* Skriv literatur om model, model.addAttribute, thymeleaf ${stu.studentId} (passer til lek 05)

* Lav tekst der forklarer @Annontations i forhold til Spring - Passer til lek 03-10

* #16 Øvelse om at vise enrollments på details siden for en studerende. Includere mange til mange forbindelse mellem studerende og courses i students_courses tabellen og enrollments klassen

* [SpringMvcStepByStep](https://github.com/StudentsAdministration/SpringMvcStepByStep) mulig literatur. Udemy kursus [Spring MVC For Beginners : Build Java Web App in 25 Steps](https://www.udemy.com/spring-mvc-tutorial-for-beginners-step-by-step/?altsc=366608) 

* [GitIt skal evt. mmd](https://github.com/StudentsAdministration/GitIt/blob/master/README.md)

