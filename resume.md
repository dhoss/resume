# Resume/CV

## Devin Austin

devin.austin@gmail.com

970-290-6669


## Summary: I am a web software developer.

I build web applications. I learn quickly. I'm extremely tenacious when it comes to getting things done and figuring things out.  I have experience with high pressure situations that require fast action, precise movements and critical thinking skills. Good software is developed by combining research, planning, quick iterations, testing, and communication.  I build the best product that is possible, in the time given. I make sure I have the tools and knowledge required to do so.

Give me a specification, I will do everything in my power to produce a reusable, extensible, fast, and efficient solution; on time, and with a smile.

# Skills

## Languages

* Scala
* Java
* Go
* Python
* Ruby

## Applications/Technologies

* AWS
   * S3, RDS/Aurora, IAM policies, SSM documents, EC2, KMS secrets, Cloudformation, Glue, Athena
* Various SQL database flavors (Postgres, MySQL, SQL Server)
* Cassandra
* Kafka
* Akka
* Kubernetes
* Ansible
* Terraform


# Professional Experience

## January 2022 - Present: HelioHealth

## January 2021 - January 2022: Charter/Spectrum
### Senior Software Engineer Contractor
Built REST service to create generic mock service request/response definitions for the QA/testing team that allowed them to mock various test scenarios while testing.  There was nothing that did what the testing team was looking for, and existing integration tests were tightly coupled with legacy code, so I proposed a solution and was able to implement a cost effective solution using DynamoDB as a data store that was cheaper than the Mongo data store that was already in place.  The resulting service was small, clean, flexible, fast (upwards of 1000 requests/second with reads) and cheap.

Added REST client integrations to consume multiple, separate internal APIs for various subscriber package entitlements.

Refactored existing entitlement calls that obtain various subscriber entitlement codes to use new internal API endpoints and fall through gracefully depending on the initial API call response.

## June 2020 - December 2020: NASDAQ
### Software Consultant
Worked on a Spring Boot application that read trading data messages from a Kafka stream and wrote them out as parquet files to S3 and inserted records into a Glue catalogue.  

Main contributions consisted of implementing a data transformation layer to globally (all messages encountered) flatten nested Avro arrays and structs/maps, trim whitespace, and then handle transformations for specific message types which included converting binary field values into their string hex representation, and manage Avro schema versions on a per message type basis, tracking down insufficient retry logic for connecting to Glue, and various day to day Kubernetes configuration changes and administration pertaining to the parquet writer application.

## June 2019 - June 2020: TalentReef
### Senior Software Engineer
Contributed to bringing up test coverage for several legacy Scala Play applications that were built in a manner not very conducive to testing (no dependency injection, cake pattern, etc)

Added features across several CQRS based Scala microservices, using Akka, Kafka, SQL Server, and Cassandra, running on AWS EKS.

Wrote a small tool to migrate from our version of Kong API gateway to the newest version.  Included in this was functionality to interact with our Kong service registration application to automate the process.


Worked on solving application issues related to memory leaks and long standing timezone problems when sending out calendar invites through our application

Wrote several critical features under strict time constraints including:
* an everify API proxy to handle applicant employment verification requests
* an Akka based user provisioning retry feature for a high profile client that allows onboarders to retry user provisioning if requests fail between the two systems.  

Advised on several tech decisions, including incorporating the usage of terraform for infrastructure changes, and using flywaydb for database migrations.

Took charge of developing a new greenfield Java service to manage and orchestrate client data replication across environments.  Handled the vast majority of design and implementation for the API contracts, code reviews, sustainable code development and design practices, organized testing (including the use of data fixtures across tests using common data and objects).  Rewrote large portions of the code that were done hastily in an unsustainable fashion and ran daily sync up meetings between the other developer working on the project.

Contributed to making sure stories in grooming meetings were clear and concise, and got the team started on breaking out stories into smaller, decoupled pieces that helped developers work asynchronously and not duplicate work, as well as organizing work into smaller, more manageable chunks.

## September 2018 - June 2019: Charter/Spectrum
### Senior Software Engineer
Benchmarked Protocol Buffer serialization for Kafka interaction in Scala.

Wrote the majority of the Protocol Buffer implementation in our code base and have been an authoratative resource for other team mates.

Worked on system to reconcile entitlements to customers using CQRS.  Most data is held in memory and persisted to various mongo databases.  Interservice communication is done using Kafka and Protocol Buffers.  

Wrote an in-memory service to normalize various pieces of customer to short integers to make transmitting data over Protocol Buffers leaner.

Implemented various REST endpoints and an HTTP client to take requests from various clients and pass them to a service that retrieves customer account information and entitlements and compare the response with my team's current dataset and send out various notifications respective of any differences.

## April 2018 - September 2018: Enlitic

### Senior Software Engineer 
Architected, planned and built out tooling to help data scientists manage deep learning modeling code snapshots

Consulted and improved build and deploy processes for various applications

Advised on AWS practices

## October 2016 - April 2018: Ancestry.com

### DNA Data Science Platform - Senior Software Engineer
Extracted EC2 orchestration functionality from a Spring Boot application into its own application and extended its functionality

Set up a build system using Jenkins 2 Pipelines to deploy the application to EC2 instances running Docker on CoreOS

Used Terraform to set up all required IAM roles, policies, and other resources (S3 buckets, Aurora clusters, SSM documents)

Handled every aspect of the aforementioned application from designing and implementing both application and infrastructure architecture

Successfully launched beta version of orchestration application to a select group of scientists after overcoming a lot of infrastructure adversity with minimal support

### DNA Platform - Senior Software Engineer
Designed and implemented a Spring Boot Java application to manage provisioning EC2 instances for DNA scientists, saving the team
about 3 months of training and development time.  

Set up a more robust build system for an existing application that helped through numerous deployments and disasters.

Mentored junior and less experienced developers through various application development systems, deployment procedures and coding best practices.  

Built out and configured several build and deploy environments using Jenkins pipelines, EC2, git, Docker and bash.

Wrote a blue/green deployment script in bash to handle deployments in AWS

## August 2012 - October 2016: Ancestry.com

### Devops - Software Developer
Worked on maintaining configuration for DNA application stacks through Chef

Built various data migration scripts, data transformation scripts, and a small Go cron job that handled kicking off recurring billing jobs.

Built a tool in go to handle a massive SQL Server data transformation and migration

Wrote several tools to handle several large image imports and mysql data migrations for an image service that handled several terabytes of image data

Maintained and added several features to an existing, large, legacy, high traffic image service written in Perl, running on AWS, using MySQL as the metadata backend and S3 for image storage.  

Worked on building a testing framework for a large .NET application using C#, Selenium, Fitnesse and Jenkins.

Managed configuration, build, and deployment for several applications spanning across Linux, Windows and various different application frameworks.  Since there was only a manual process to handle these deployments, I wrote several tools to help make things more stable.

Deployed Nagios to several disparate systems using Ansible.

## April 2006  - August 2012: CodedRight

### Independent Contractor/Founder

Built several small web applications for various clients' websites using Perl 

Built a document storage web application that was intended to serve as a document sharing website for various businesses in Perl, running on AWS

Managed and wrote a database and file data migration script in Perl to move data from a previously used
OpenInteract application to a new Catalyst+DBIx::Class web application backed by MySQL and MogileFS.

Built a search engine feature that uses Data::SearchEngine and DBIx::Class to search based on racing class
types, race tracks, and other such race track and car class based data. (Perl)

Wrote a geocoding feature that calculates the distance of a track from a given city name or zip code and
returns tracks within a chosen radius (5, 10, 15 miles etc) of city/zip code based on Geo::Coder and
DBIx::Class (Perl)

Implemented a materialized path structure for managing virtual directories for website assets and file data in
the database based upon DBIx::Class::Tree::Ordered::MaterializedPath, allowing administrators to have a file
system view of website assets. (Perl)

Developed Catalyst and Ruby on Rails codebase that used a JSON API to pass messages between
applications

## January 2012 - April 2012: Ionzero, LLC

### Software Engineer

Worked on a large, legacy Perl application that deals with airline flights locally and internationally.

Built out features dealing with parsing data coming from airline flight systems such as Sabre.

Worked on designing and building a metadata storage application for an ad audit service 

Built an application to act as a proxy between a front facing php web application and a storage file system that
handles upwards of 6,000 file uploads a day via the API that handles XML, JSON and plain HTTP data. Built
using Catalyst and Plack

Built and designed a proof of concept application for ChannelMeter.com, a YouTube analytics website

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

  * [Smough](https://github.com/dhoss/smough) - A blog written in Scala, very pre-alpha.

  * [Treeify](https://rubygems.org/gems/treeify) - A gem to allow you to make recursive queries using Postgres and CTE (WITH RECURSIVE, to be more precise) and get a tree-like data structure in return.

  * [Fluorescent](https://rubygems.org/gems/fluorescent) - A small gem to highlight search terms in search results.

## Identities and resources

Writing

Published many articles regarding perl, a few of which are listed here:

[Playing With Scala, part 1](http://stonecolddev.in/posts/playing-with-scala-building-a-small-web-app-with-play-2-4-play-slick-and-postgres) and [part 2](http://stonecolddev.in/posts/playing-with-scala-building-a-small-web-app-with-play-2-4-play-slick-and-postgres-part-2-testing) - A tutorial on how to get the Scala version of the Play! framework set up under Postgres specs2 for testing, using travis-ci for continuous integration testing.  It was generally well received on the scala subreddit on reddit.com, and I actually received some email correspondence and comments on the article from the Slick author himself with some advice and praise on the article.

[Simple Photo Gallery in Catalyst](http://www.catalystframework.org/calendar/2008/5)

[Next Page Redirect after Login](http://dev.catalyst.perl.org/wiki/wikicookbook/nextpageredirect)

[Plack and Catalyst](http://www.catalystframework.org/calendar/2009/23)

[Trees in SQL with Catalyst](http://www.catalystframework.org/calendar/2009/13)

[The New Catalyst ScriptRunner API](http://www.catalystframework.org/calendar/2009/7)


