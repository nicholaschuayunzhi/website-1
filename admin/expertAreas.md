<frontmatter>
title: "CS3281 Expert Areas"
keywords: Languages, Tools, Tech Topics, Code Quality, Dev Ops, Desktop, Documentation, Fault Tolerance, Performance, Scalability, Security, Testing, UIX, Web
</frontmatter>

<link rel="stylesheet" href="{{baseUrl}}/css/main.css">

<include src="../common/header.md" />

<div class="website-content">

# Expert Areas

Given below are some areas that have overlaps with internal projects that you'll be working in CS3282. Picking these will have the advantage that your work in the internal projects can increase your expertise in the chosen areas (i.e. your work in CS3282 can help you earn more credit in CS3281).

## Languages

Here are the main languages used in the three projects (`MB` : MarkBind, `PL` : PowerPointLabs, `SE` : SE-EDU, `TM` : TEAMMATES). 

Language   | Projects
-----------|-----
Java       | `SE` `TM`
HTML       | `MB` `TM`
CSS        | `MB` `TM`
JavaScript | `MB` `TM`
C#         | `PL`


## Tools, Tech Topics

The aspects, tools, topics given below can help you to pick an aspect and a topic to study.

### Code Quality

* Static analysis 
  * Checkstyle `TM` `SE`
  * Codacy `SE`
  * ESLint `TM`
  * FindBugs `TM` `SE` 
  * PMD `TM` `SE`
  * Stylelint `TM`
  * StyleCop `PL`

### Dev Ops

* Build 
  * Gradle `TM` `SE`
  * MSBuild `PL`
  * npm `MB` `TM`

* CI
  * AppVeyor `SE` `PL`
  * Travis `TM` `SE`

* Process 
  * Workflow `MB` `TM` `SE` `PL`
  * Dev community management `TM` `SE` `PL`
  * Release management `TM` `SE` `PL`


### Desktop

* GUI
  * JavaFx, ControlsFx `SE`
  * Windows Presentation Foundation (WPF), Winform `PL`

* Installers `SE` `PL`

* Portability `SE` (ensuring the apps can run an all major OS'es)

### Documentation

Generating and maintaining user/developer docs require good writing skills as well and various tools.

* UML `TM` `SE` `PL`
* Document generation `MB` `TM` `SE` `PL` 
  * Jekyll `MB` `PL`
  * AsciiDoc `MB` `SE`
  * Markdown `MB` 

### Fault Tolerance

This is especially important to `TM` because Web apps are vulnerable to all sorts of intermittent faults. For example, one problem it faces is called 'eventual consistency' where new data requires some time to propagate through all nodes of the distributed database during which time the app has to deal with data in an inconsistent state.

* Logging `MB` `TM` `SE` `PL`
* Error reporting `MB` `TM` `SE` `PL`
* Backup and restore `TM`

### Performance and Scalability

This affects all projects:

* `MB` : Rendering content takes far too long for big websites at the moment
* `PL` : Users don't like their PowerPoint to slow down due to our plugin
* `SE` : We want the app to be very fast and to be able to handle lot of data (especially when connected to third party backends such as Google calendar) 
* `TM` : 1. It has to deal with spikes in load. 2. Every CPU cycle or byte of data transfer costs us money.

Sub areas: 

* Multi-threading `TM` `SE`  
* Profiling `MB` `TM` `SE` `PL` : To find performance bottlenecks
* Scalability testing `MB` `TM` `SE`

### Security

* Vulnerabilities `TM`: SQL injection, cross site scripting
* Access control `TM`

### Testing

* Code coverage 
  * Blanket.js `TM`
  * Coveralls `TM` `SE`
  * EclEmma `TM` `SE`
  * JaCoCo `TM`
  * MSTest code coverage `PL`

* Testing frameworks
  * JUnit `SE`
  * MS Test `PL`
  * TestNG `TM`
  * QUnit `TM`

* UI testing
  * MS Test `PL`
  * Selenium `TM`
  * TestFx `SE`
  
* Mocking
  * Mockito, PowerMock `SE`
  * Moq `PL`

### UIX

* Usability `MB` `TM` `SE` `PL`
* Accessibility `TM` : Some students who access `TM` may have accessibility needs
* Responsiveness `TM` : The app can be accessed using a variety of devices

### Web (Frontend)

* Front End frameworks: 
  * Bootstrap `TM`
  * Vuestrap `MB`
  * JQuery `TM`

* Dynamic page generation
  * JSP `TM`
  * JSTL `TM`

### Web (Backend)

* Google App Engine `TM`
* Servlets `TM`
* Node.js `MB`
* Persistence
  * JDO, JPA, GAE DataStore: `TM`
  
<tip-box> 

:information_source: Information in this page can get outdated as the projects evolve. PRs to update this page are welcome.

</tip-box> 
  
</div>