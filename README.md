<h1 align="center" id="title">Bank Statement Aggregator</h1>

<p id="description">Developed a Bank Aggregator application to integrate multiple banking services and generate a summarised banking statement. Implemented RESTful APIs for seamless communication between client and server. Utilised SQL for efficient data storage and management ensuring data integrity and security. Integrated AWS S3 for uploading and downloading bank statements.</p>

<h2> Project Structure:</h2>

my-spring-boot-app/ 
├── src/ 
│ ├── main/ 
│ │ ├── java/ 
│ │ │   └── com/ 
│ │ │     └── example/ 
│ │ │        └── aggregator/ 
│ │ │            ├── BankStatementAggregatorapplicatio.java 
│ │ │            ├── config/ 
│ │ │            │ ├── SecurityConfig.java 
│ │ │            ├── controllers/ 
│ │ │            │ ├── BranchController.java 
│ │ │            │ ├── CompanyController.java      
│ │ │            │ └── StatementController.java 
│ │ │            │ └── UserController.java 
│ │ │            ├── services/ 
│ │ │            │ ├── AWSservice.java 
│ │ │            │ ├── BankStatementservice.java 
│ │ │            │ └── CompanyService.java 
│ │ │            │ └── UserService.java 
│ │ │            │ └── BranchServie.java 
│ │ │            ├── repositories/ 
│ │ │            │ ├── BankStatementRepository.java 
│ │ │            │ ├── BrancjRepository.java 
│ │ │            │ └── CompanyRepository.java 
│ │ │            │ └── TransactionRepository.java 
│ │ │            │ └── UserRepository.java 
│ │ │            ├── model/ 
│ │ │            │ ├── BankStatement.java 
│ │ │            │ ├── Branch.java 
│ │ │            │ └── Company.java 
│ │ │            │ ├── Transaction.java 
│ │ │            │ ├── User.java 
│ │ └── resources/ 
│ │      ├── application.properties 
│ │          └── static/ 
│ │            └── css/ 
│ │               └── js/ 
│ │                 └── templates/ 
│ │                    └── index.html 
│ └── test/ 
│    └── java/ 
│       └── com/ 
│         └── example/ 
│               └── myapp/
│                  └── BankStatementAggregatorApplication.java/
│── JRE System Library [JavaSE-17]
│── Maven Dependencies
│── src/
│── target/
│── HELP.md
│── mvnw
│── mvnw.cmd
  
<h2>💻 Built with</h2>

Technologies used in the project:

*   Spring Boot
*   AWS S3
*   Core Java
