# Resume/CV

## Devin Austin

devin.austin@gmail.com

970-290-6669


## Summary: I am a web software developer.

I build web applications and have experience with many common frameworks in several different languages, including Java, Go, and Ruby.

I learn very well, and am extremely tenacious when it comes to getting things done and figuring things out.  I've had a good deal of experience with high pressure situations
that require fast action, precise movements, and critical thinking skills in order to get something done, or fixed.  In my experience, good software is developed by combining research, planning, quick and iterative development cycles, testing and communication.  I spend my time making sure I have the information required to build the best product that I can in the time given, and I make sure I have the tools and knowledge to do so.

In summation, you give me a specification, and I'm going to do everything in my power to produce a reusable, extensible, fast and efficient solution for you, on time, and with a smile.

# Skills

## Languages

* Java
  * jooq
  * Spark Web
  * Maven
  * Gradle
  * Flwaydb
  * Spring Boot
* Go
* C#
* Ruby
  * Web Frameworks/Technologies
    * Ruby on Rails
    * Rack
    * Unicorn
    * Puma
    * Rspec
    * MiniTest
    * Sinatra
  * Database/ORMs
    * ActiveRecord
    * Sequel
  * Search
    * Tire (elasticsearch)
    * PgSearch (postgresql tsearch)
  * Worker Queues
    * Resque

* Javascript
  * Frameworks
    * Reactjs
    * webpack
    * jQuery
    * CoffeeScript
* Scala
  * Play! Framework
  * Slick FRM

## Applications/Technologies

* PostgreSQL
* Ansible
* Jenkins
* RabbitMQ
* Nagios
* Redis
* Varnish
* Memcached
* ElasticSearch
* Solr
* Resque
* LESS
* SASS
* AWS
* SQL Server 2008
* MySQL
* Chef

# Professional Experience

## August 2012 - Present Ancestry.com

Currently working on the Ancestry devops team.  Day to day tasks include configuration management through custom built tools, managing go.cd pipelines, diagnosing issues with servers, 
and building VMs through custom built tools.

Longer term projects involve maintaining and contributing to an inherited Java codebase for provisioning and bootstrapping VMs, and writing an app to index application configuration for searching
using python and Postgres and tsearch2.

Prior to that, I managed and made major changes to a legacy Perl application written using severely outdated technologies and techniques that ran on AWS and acted as an image service for archives.com and the 1940s Census NARA website.  The application dealt with upwards of 20 million database records stored in MySQL containing image metadata, and at one point 80 terabytes of images, thumbnails and image tiles.
I was able to polish a clean up technique using a Perl script and S3 object expiration to stand in for the unsalvageable existing clean up process and bring the AWS storage and computing costs down by approximately 50%.

I have written several small tools for myself and others to alleviate a range of tasks including generating mapping files and the SQL to go along with them for missing or incorrectly mapped database records for various archives.com image collections, and a small daemon to kick off credit card charge service jobs and notify various users of failures ([nudge](https://github.com/dhoss/nudge)).

## April 2006  - August 2012 CodedRight.net

### Independent Contractor/Founder

Developed Catalyst and Ruby on Rails codebase that emphasized a JSON API to pass messages between 
applications.  Used CoffeeScript and LESS for UX components.  Client has been happy with deliverables produced on time and 
to their specifications.

Submitted a patch to the MojoMojo wiki that allows users to switch between Textile and Markdown wiki markup.

Created a web crawler to index all electrical engineers from Australia's YellowPages using Web::Scraper. The time constraint was great on this, less than 36 hours, and the client was very happy with the result.

## January 2012 - April 2012 Ionzero, LLC

### Software Engineer

Worked on a large, legacy Perl application that deals with airline flights locally and internationally.

## September 2011 - December 2011 ExposureManager, LLC

### Senior Software Developer

Worked on a Perl+MySQL backed web application with a heavily jQuery oriented front end that dealt with large numbers (15k photo batches in some instances) of photographs.
Worked on building a Catalyst application backed by PostgreSQL using DBIx::Class, Bread::Board, and Message::Stack.

Main highlights include architecting a sane git workflow for users who weren't familiar with git, as well as building a well rounded infrastructure for PostgreSQL database schemata,
and the Catalyst web application.  Also created a simple, but flexible JSON API that allowed for easy interfacing with Ajax requests and providing a scalable and easy to use internal application
API, while remaining extensible and decoupled. Built a Facebook style "infinite scroller" for photo galleries using jQuery.

## February 2011 - September 2011 SocialFlow, LLC

### Product Engineer

## May 2009 - February 2011 Ionzero, LLC

### IT Consultant

## January 2010 - April 2010 Nasa Pro Racing

### IT Consultant

## April 2009-September 2009 Google Summer of Code

### Programmer

## Education

### 2007-2010 Metropolitan State College of Denver Denver, CO

BS in Computer Security with a minor in Computer Science

Majored in Computer Security with a Computer Science minor Bachelor of Science in Computer Security and Crime

Participated in CANVAS - A network security exploitation convention/workshop two years in a row. Contributed to breaking into servers via multiple exploits, SQL injection, DCOM holes, etc. Placed 4th, and 3rd respectively.

### 2006-2007 University of Northern Colorado Greeley, CO

## Open Source Work

* http://github.com/dhoss
* 
### Software I've written:

  * [ceramiccatepottery.com](http://www.ceramiccatepottery.com) - An image gallery and administrative interface for my wife's pottery business.  
                                                                  Built using Java (Spark Web framework + jooq), Postgresql 9.4, Varnish, Cloudflare CDN, Nginx and Ansible.  Using webpack to manage static assets.
                                                                  
  * [Steel](https://github.com/dhoss/steel) - An excuse to learn Scala, and initially a work out tracker web application built using the Play! web framework and the Slick FRM for database access.

  * [Treeify](https://rubygems.org/gems/treeify) - A gem to allow you to make recursive queries using Postgres and CTE (WITH RECURSIVE, to be more precise) and get a tree-like data structure in return.

  * [Fluorescent](https://rubygems.org/gems/fluorescent) - A small gem to highlight search terms in search results.
  
  * [Kodiak](https://github.com/dhoss/Kodiak) - A Ruby on Rails CMS under development with an emphasis on threaded discussions, photo galleries, and being easily managed.


## Identities and resources

Writing

Published many articles regarding perl, a few of which are listed here:

[Playing With Scala, part 1](http://stonecolddev.in/posts/playing-with-scala-building-a-small-web-app-with-play-2-4-play-slick-and-postgres) and [part 2](http://stonecolddev.in/posts/playing-with-scala-building-a-small-web-app-with-play-2-4-play-slick-and-postgres-part-2-testing) - A tutorial on how to get the Scala version of the Play! framework set up under Postgres specs2 for testing, using travis-ci for continuous integration testing.  It was generally well received on the scala subreddit on reddit.com, and I actually received some email correspondence and comments on the article from the Slick author himself with some advice and praise on the article.

[Simple Photo Gallery in Catalyst](http://www.catalystframework.org/calendar/2008/5)

[Next Page Redirect after Login](http://dev.catalyst.perl.org/wiki/wikicookbook/nextpageredirect)

[Plack and Catalyst](thttp://www.catalystframework.org/calendar/2009/23)

[Trees in SQL with Catalyst](http://www.catalystframework.org/calendar/2009/13)

[The New Catalyst ScriptRunner API](http://www.catalystframework.org/calendar/2009/7)

