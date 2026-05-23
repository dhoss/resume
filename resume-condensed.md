# Resume/CV

## Devin Austin

devin.austin@gmail.com

970-290-6669


## Summary: 

I've been doing this for 15~ years.  I love crafting code, solving problems and being challenged.  Writing code is a hobby of mine and I really don't like leaving problems unsolved.

I'm a firm believer that if you hit your head against the wall long enough, you'll get through it.

# Skills

## Languages

* Java
* Scala
* Python

## Applications/Technologies

* AWS service (enumeration available upon request)
* Various SQL database flavors (Postgres, MySQL, SQL Server)
* Kubernetes
* Terraform


# Professional Experience

## June 2025 - Present: Empower
### Senior Software Engineer

Inherited and made thorough enhancements to an ANTLR4 based Java code validation project created to validate code from projects being migrated from 1990's ProC code to Spring Boot 3 Rest services.

Developed a maven plugin around said validation project that allowed developers to run it against their codebase and get a report detailing violations against the company coding standards defined to maintain parity between the new java codebases and the ProC modules they were being converted from.

Developed code based rule definitions and a rule execution engine that allowed for reasonably flexible code standard rule implementations to parse and detect things like Spring annotations being used where required, POM dependencies meeting version requirements using Maven version ranges, transaction related method call counts, querying Oracle databases to verify per service error messages are populated, and ensuring DAO implementation classes have configuration dependencies injected that have the correct configuration annotations.

Optimized slow, serial Java file parsing by refactoring to a multi threaded implementation.  Dealt with code that wasn't thread safe, and refactoring an initial multi threaded work stealing pool + blocking queue implementation into a much more simple parallel stream implementation.

Mentored a junior developer that contributed changes to the project.  Paired, code reviewed and assigned tasks aimed at onboarding him onto the application and becoming familiar enough to make consistent changes.  Gathered feedback as well regarding the ergonomics of the API I'd put together for developing new rules.

## January 2022 - April 2025: HelioGenomics
### Senior Software Engineer
Built an SMS appointment reminder service that patients could sign up for and receive appointment reminders at configured intervals.  The service used a simple FSM and scheduler to persist each patient's reminder status.

Built and deployed a payment batch processing system running on Fargate, Batch and EventBridge to handle scheduled ingestion of Excel files containing patient billing information into Oracle NetSuite.

Built a simple fuzzing application for testing UI features using Playwright

Set up SSO and a VPN on AWS using Terraform for various environment authentication

Built out test data generation service to allow users to populate various Salesforce based objects through Lockbox using REST

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

### 2006-2007 University of Northern Colorado Greeley, CO

## Open Source Work

* http://github.com/dhoss

### Software I've written:

  * [GiantDad](https://github.com/dhoss/giant-dad) - A simple workout tracker written in Java using Micronaut and Postgres

  * [Juke](https://github.com/dhoss/juke) - An attempt to rewrite the ancient phpnuke cms in Java using Spring Boot 3 and Postgres

  * [Trayzn](https://github.com/dhoss/trayzn/) - A simple bookmarking service written in Java using Spring Boot 3 and Postgres.  Browser extension code is located here: [trayzn-chrome-extension](https://github.com/dhoss/trayzn-chrome-extension)

