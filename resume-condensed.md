# Resume/CV

## Devin Austin

devin.austin@gmail.com

970-290-6669


## Summary: I am a web software developer.

I build web applications. I learn quickly. I'm extremely tenacious when it comes to getting things done and figuring things out.  I have experience with high pressure situations that require fast action, precise movements and critical thinking skills. Good software is developed by combining research, planning, quick iterations, testing, and communication.  I build the best product that is possible, in the time given. I make sure I have the tools and knowledge required to do so.

Give me a specification, I will do everything in my power to produce a reusable, extensible, fast, and efficient solution; on time, and with a smile.

# Skills

## Languages

* Java
* Scala
* Python

## Applications/Technologies

* AWS
   * S3, RDS/Aurora, IAM policies, SSM documents, EC2, KMS secrets, Cloudformation, Glue, Athena, DynamoDB, Batch, EventBridge, Fargate
* Various SQL database flavors (Postgres, MySQL, SQL Server)
* Cassandra
* Kafka
* Kubernetes
* Terraform


# Professional Experience

## June 2025 - Present: Empower
### Senior Software Engineer

Inherited and made thorough enhancements to an ANTLR4 based Java code validation project created to validate code from projects being migrated from 1990's ProC code to Spring Boot 3 Rest services.

Developed a maven plugin around said validation project that allowed developers to run it against their codebase and get a report detailing violations against the company coding standards defined to maintain parity between the new java codebases and the ProC modules they were being converted from.

Developed code based rule definitions and a rule execution engine that allowed for reasonably flexible code standard rule implementations to parse and detect things like Spring annotations being used where required, POM dependencies meeting version requirements using Maven version ranges, transaction related method call counts, querying Oracle databases to verify per service error messages are populated, and ensuring DAO implementation classes have configuration dependencies injected that have the correct configuration annotations.

Handled design, development, documentation, build and release for all of the above nearly completely independently.  Managed bug fixes, rule definition refinement, integrating user feedback changes and digging into issues related to edge cases that weren't being detected properly in certain projects.

Optimized slow, serial Java file parsing by refactoring to a multi threaded implementation.  Dealt with code that wasn't thread safe, and refactoring an initial multi threaded work stealing pool + blocking queue implementation into a much more simple parallel stream implementation.

Mentored a junior developer that contributed changes to the project.  Paired, code reviewed and assigned tasks aimed at onboarding him onto the application and becoming familiar enough to make consistent changes.  Gathered feedback as well regarding the ergonomics of the API I'd put together for developing new rules.

## January 2022 - April 2025: HelioGenomics
### Senior Software Engineer
Built an SMS appointment reminder service that patients could sign up for and receive appointment reminders at configured intervals.  The service used a simple FSM and scheduler to persist each patient's reminder status.

Built several services to integrate with various vendor APIs, spanning from payment systems like Chargebee to patient and doctor CRMs such as Kareo.

Built and deployed a payment batch processing system running on Fargate, Batch and EventBridge to handle scheduled ingestion of Excel files containing patient billing information into Oracle NetSuite.

Built a simple fuzzing application for testing UI features using Playwright

Integrated a Spring Boot application with HAPI, a Java HL7 implementation

Set up SSO and a VPN on AWS using Terraform for various environment authentication

Set up a small Spring Boot application to handle Office 365 authentication for company wide authentication

Built out test data generation service to allow users to populate various Salesforce based objects through Lockbox using REST

Managed design, planning and implementation of all previously mentioned projects almost completely independently with minimal instruction or feedback from superiors

Handled constant context switching and pivoting with very little in the way of structure or agile/scrum planning

## January 2021 - January 2022: Charter/Spectrum
### Senior Software Engineer Contractor

## June 2020 - December 2020: NASDAQ
### Software Consultant

## June 2019 - June 2020: TalentReef
### Senior Software Engineer

## September 2018 - June 2019: Charter/Spectrum
### Senior Software Engineer

## April 2018 - September 2018: Enlitic

### Senior Software Engineer 

## October 2016 - April 2018: Ancestry.com

### DNA Data Science Platform - Senior Software Engineer

### DNA Platform - Senior Software Engineer

## August 2012 - October 2016: Ancestry.com

### Devops - Software Developer

## April 2006  - August 2012: CodedRight

### Independent Contractor/Founder


## January 2012 - April 2012: Ionzero, LLC

### Software Engineer


### Programmer

## Education

### 2007-2010 Metropolitan State College of Denver Denver, CO

BS in Computer Security with a minor in Computer Science

Majored in Computer Security with a Computer Science minor Bachelor of Science in Computer Security and Crime

Participated in CANVAS - A network security exploitation convention/workshop two years in a row. Contributed to breaking into servers via multiple exploits, SQL injection, DCOM holes, etc. Placed 4th, and 3rd respectively.

### 2006-2007 University of Northern Colorado Greeley, CO

## Open Source Work

* http://github.com/dhoss

### Software I've written:

  * [GiantDad](https://github.com/dhoss/giant-dad) - A simple workout tracker written in Java using Micronaut and Postgres

  * [Juke](https://github.com/dhoss/juke) - An attempt to rewrite the ancient phpnuke cms in Java using Spring Boot 3 and Postgres

  * [Trayzn](https://github.com/dhoss/trayzn/) - A simple bookmarking service written in Java using Spring Boot 3 and Postgres.  Browser extension code is located here: [trayzn-chrome-extension](https://github.com/dhoss/trayzn-chrome-extension)

