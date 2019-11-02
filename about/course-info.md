# System Integration 2019 Fall

#### Instructor
	Dr. Todorka Dimitrova <br>
	tdi@cphbusiness.dk

## Contents
- [Introduction](#introduction)
- [Learning Objectives](#learning-objectives)
- [Tentative Plan](#tentative-plan) 
- [Assignments](#assignments)
- [Score](#score)
- [Exam](#exam)
- [Resources](#recommended-books)

## Introduction

**System integration** in information technology  is the process of bringing together different computing systems and software applications physically or functionally, to act as a coordinated whole. It is the main approach for both upgrading large legacy systems and building new software applications as aggregation of interacting subsystems and service components. 

This course provides knowledge and skills in implementing various methods and techniques for system integration.

#### Prerequisites
Participating students are expected to have understanding of software architectures and networking, as well as sufficient programming skills for independent development of software applications.

## Learning Objectives
The learning objectives of System Integration course are defined in the National curriculum (in Danish), which can be found at: 
[Studieordning for professionsbacheloruddannelsen  i softwareudvikling 2017] [1].   

[1]: https://www.cphbusiness.dk/media/78341/pba_soft_cba_studieordning_2017.pdf

Here is a selection, you should be familiar with:
### Indhold
Fagelementet skal medvirke til, at den studerende udvikler kompetencer til at kunne
arbejde med teknisk integration af systemer. Den studerende skal efter modulet
kunne integrere eksisterende systemer, integrere eksisterende systemer i forbindelse
med udvikling af nye systemer, samt kunne udvikle nye systemer som understøtter
fremtidig integration.
### Læringsmål
#### Viden
Den studerende har viden om:
- de forretningsmæssige overvejelser omkring systemintegration
- standarder og standardiseringsorganisationer
- lagring, transformation og integration af dataressourcer
- servicebegrebet og forstå dets sammenhæng med serviceorienteret arkitektur
- teknologier som kan bruges til at implementere en serviceorienteret arkitektur
- værktøjer til integration
#### Færdigheder
Den studerende kan:
- anvende et objektorienteret system i en serviceorienteret arkitektur
- designe et system, så det er let at integrere med andre systemer, og så det
- anvender eksisterende services
- transformere eller udvide et system således at det kan fungere i en
- serviceorienteret arkitektur
- anvende mønstre der understøtter systemintegration
- integrere generiske og andre systemer
- vælge mellem forskellige metoder til integration
- omsætte elementer i en forretningsstrategi til konkrete krav til integration af
systemer.
#### Kompetencer
Den studerende kan:
- vælge mellem forskellige teknikker til integration
- tilegne sig viden om udviklingen i standarder for integration
- tilpasse IT-arkitektur, så der tages højde for fremtidig integration af systemer.


## Tentative Plan
Here is a tentative plan of topics and teaching sessions (please, be aware it may be updated in the way).
						
     						
|session| date       | school week | calendar week | topic                                                               | programming activity                                       | technology                      |
|------------|------------|-------------|---------------|---------------------------------------------------------------------|------------------------------------------------------------|---------------------------------|
| 1         | 28/08/2019 | 1           | 35            | Introduction, technical	integration	of	software	systems          | Integration architectures and standards,  P2P connectivity | TCP/IP ports and sockets        |
| 2          | 04/09/2019 | 2           | 36            | Distributed computing, Client\-Server paradigm                      | Technologies for invocation of remote objects              | RPC, RMI                        |
| 3          | 11/09/2019 | 3           | 37            | Web Services, core functionallity and standartization, SOAP         | Description, registration and implementation of SOAP WS    | XML, WSDL, SOAP, UDDI           |
| 4          | 18/09/2019 | 4           | 38            | REST, RESTfull Web Services and implementations, RESTfull API       | HTTP protocol and data formats, web API                    | HTTP,  JSON, cURL, Postman      |
| 5          | 25/09/2019 | 5           | 39            | Group Project 1                                                     | Presentations and feedback                                 |                                 |
| 6          | 02/10/2019 | 6           | 40            | Enterprise Integration Architecture, business considerations        | Business Process Modelling, protocols and standards        | BPMN, BPEL                      |
| 7          | 09/10/2019 | 7           | 41            | Enterprise Integration Architecture, middleware, SOA                | Web Services composition and coordination, SOA, ESB        | OpenESB                         |
|Fall Break
|                                                                                                                                                                        
| 8          |23/10/2019  | 9           | 43            | Enterprise Integration Architecture, Message Oriented Middleware    | Message brokers                                            | ActiveMQ/RabbitMQ               |
| 9          | 30/10/2019 | 10          | 44            | Enterprise Application Integration, enterprise integration patterns | EAI integration development environments                   | Java DSL, Camel                 |
| 10         | 06/11/2019 | 11          | 45            | Group Project 2                                                     | Presentations and feedback                                 |                                 |
| 11         | 13/11/2019 | 12          | 46            | Microservices architectecture                                       | Development and integration of microservices               | Java, Spring Boot               |
| 12         | 20/11/2019 | 13          | 47            | Enterprise container platforms and orchestration                    | Deployment of microservices applications                   | Docker, Docker Composer, Eureka |
| 13         | 27/11/2019 | 14          | 48            | Integrating legacy systems, API business aspects                    | Choosing a method, building efficient APIs                 | Kubernetes                      |
| 14         | 04/12/2019 | 15          | 49            | Agile development and integration, DevOps technologies and tools    | Cloud computing, CI/CD                                     | Jenkins, IBM cloud              |
| 15         | 11/12/2019 | 16          | 50            | Group Project 3                                                     | Presentations and feedback                                 |                                 |

## Assignments
During the semester, you will work on various projects and programming tasks. 
There will be **three group projects**, **four individual homework tasks**, **two peer grade tasks**, and **one multiple choice test**, as shown below.
Each assignment provides certain number of credit points. The total number of points is 100. 


| **#** | **assignments**                             |**points**|
|-------|---------------------------------------------|----------|
|  1    | Homework 1: RMI programming task            |  5       |
|  2    | **Group Project 1: Web Services**               | 20       |
|  3    | PeerGrade on Group Project 1                |  5       |
|  4    | Homework 2: BPEL design task                |  5       |
|  5    | **Group Project 2: EIA, SOA, and EIP**          | 20       |
|  6    | Homework 3: EIP research                    |  5       |
|  7    | PeerGrade on Group Project 2                |  5       |
|  8    | Homework 4: Microservice, data source       |  5       |
|  9    | **Group Project 3: Microservices Architecture** | 20       |
| 10    | Multiple Choice Test                        | 10       |


## Score
During the semester you need to collect minimum 80% (80 points), in order to qualify for the exam.
**If you miss to fulfill this requirement, you will miss an exam attempt.**
Fulfilling the requirement automatically signs you up for an exam.

## Exam
The course ends with a successful examination. 
There are three exam dates, scheduled by the administration – one regular exam and two re-exams. The exam is oral and graded. 
The examination commission consists the course instructors and an external censor. 
- Before the exam, students, in groups, develop, document, and submit to WiseFlow a previously defined exam project. 
- The exam starts with 20-minutes group presentation of the exam project and continues with 15-minutes individual discussions with each student separately.  
- The group presentation introduces the project solution **focusing on the system integration issues** and **highlighting the team members personal contribution** in the project development.  
The individual discussions cover topics related to the project, the report and the presentation, as well as other topics related to the course curriculum. 

## Recommended Books
Here is a reference of some books, which will be used in the teaching.
- Enterprise Integration Patterns: Designing, Building, and Deploying Messaging Solutions
Gregor Hohpe, Bobby Woolf
ISBN-10: 0321200683 • ISBN-13: 9780321200686
©2004 • Addison-Wesley, 736 pp.
- Service-Oriented Architecture: Analysis and Design for Services and Microservices (2nd Edition) 
	Thomas Erl 
	ISBN-10: 0133858588 • ISBN-13: 978-0133858587
	©2016 • Prentice Hall / Pearson • 416 pp.
- Microservices for Java Developers. A Hands-on Introduction to Frameworks and Containers • Christian Posta 
ISBN: 978-1-491-96207-7 • O’Reilly, 2016

More titles, as well as links to Internet resources can be found in Github folders and lecturers’ presentations.




