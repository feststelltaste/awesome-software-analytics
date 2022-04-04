# Awesome Software Analytics [![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re)


Curated list of awesome resources and links about Software Analytics.

*This list is an open community project. Feel free to [contribute your ideas](contributing.md) to it.*

**What is "Software Analytics"?**  

> Software analytics is analytics on software data for managers and software engineers with the aim of empowering software development individuals and teams to gain and share insight from their data to make better decisions. 
>
> -- <cite>Tim Menzies, Thomas Zimmermann</cite>

## Contents

_ordered by "from theory to practice"_

- [Influential Papers](#influential-papers)
- [Systematic Literature Reviews](#systematic-literature-reviews)
- [Academic Courses](#academic-courses)
- [Books](#books)
- [Blog Posts](#blog-posts)
- [Podcasts](#podcasts)
- [Talks](#talks)
- [Hands-Ons](#hands-ons)
- [Lists of Tools](#lists-of-tools)
- [Related Awesome Lists](#related-awesome-lists)

## Influential Papers

This section lists important papers from which Software Analytics has emerged.

- [Thomas Zimmermann, Peter Weisgerber, Stephan Diehl, and Andreas Zeller: Mining Version Histories to Guide Software Changes (2004)](https://www.st.uni-trier.de/~diehl/pubs/icse04.pdf) - A real classic about the idea of using software version control systems to guide software changes (awarded with the ICSE 10 Years Most Influential Paper Award 2014).
- [Tim Menzies, Christian Bird, Thomas Zimmermann, Wolfram Schulte, and Ekrem Kocaganeli: The inductive software engineering manifesto: principles for industrial data mining (2011)](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.352.9342&rep=rep1&type=pdf) - Makes you aware of various aspects that you have to consider if you want to implement Software Analytics in the industry.
- [Andrew Begel and Thomas Zimmermann: Analyze this! 145 questions for data scientists in software engineering (2013)](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/02/MSR-TR-2013-111.pdf) - a kind of meta-level paper about the questions that arise during software development which may be answered with Software Analytics.
- [Ahmed E. Hassan and Tao Xie: Software intelligence: the future of mining software engineering data (2010)](https://www.researchgate.net/publication/221560786_Software_Intelligence_The_Future_of_Mining_Software_Engineering_Data_ABSTRACT) - discusses (among other topics) which types of software data can be used with existing data mining techniques.
- [Tim Menzies and Thomas Zimmermann. Software Analytics: So What? (2013)](https://www.researchgate.net/publication/260649759_Software_Analytics_So_What) - contains a critical discussion on how far has Software Analytics got in the recent years. Includes a short overview of influential papers as well.

## Systematic Literature Reviews

These meta research papers give an overview of existing papers and/or studies in the area of Software Analytics.

- [Tamer Mohamed Abdellatif, Luiz Fernando Capretz, Danny Ho: Software Analytics to Software Practice - A Systematic Literature Review (2015)](https://arxiv.org/ftp/arxiv/papers/1511/1511.04109.pdf) - looks at past papers that applied Software Analytics in practice.
- [João Caldeiraa, Fernando Brito e Abreua, Jorge Cardosob, Toacy Oliveira: Software Development Analytics in Practice - A Systematic Literature Review (2020)](https://arxiv.org/pdf/2007.10213) - provides an aggregate view of Software Development Analytics studies from 2010 to 2019.

## Academic Courses

Courses from the academic world that lecture Software Analytics in-depth.

- [Canadian Summer School on Practical Analyses of Software Engineering Data (2011)](https://web.archive.org/web/20191222030415/http://pased.soccerlab.polymtl.ca/schedule.php) - a collection of talks about early adoptions of Software Analytics in practice. _February 2022: unfortunately, this site is gone now. Link leads to archive.org._
- [Prof. Dr. Jürgen Döllner: Automated Visual Software Analytics (2015)](https://open.hpi.de/courses/softwareanalytics2015) - Very detailed and precise explanations with focus on the visualization of software analyses.

## Books

- [Christian Bird, Tim Menzies, Thomas Zimmermann: The Art and Science of Analyzing Software Data. Morgan Kaufmann (2015)](https://github.com/ds4se/chapters) - a comprehensive work by some Software Analytics luminaries providing a good fundament for Software Analytics.
- [Tim Menzies, Laurie Williams, Thomas Zimmermann: Perspectives on Data Science for Software Engineering. Morgan Kaufmann (2016)](https://www.elsevier.com/books/perspectives-on-data-science-for-software-engineering/menzies/978-0-12-804206-9) - a collection of short articles in the area of Software Analytics. Good and neutral discussion of the advances in the field and the limits of data-driven approaches.
- [Adam Tornhill: Software X-Ray. Pragmatic Programmers (2018)](https://pragprog.com/book/atevol/software-design-x-rays) - a book full of great software analysis on real code bases.

## Blog Posts

- [Greg Wilson: Using Data Science to Explore Software Development (2017)](https://www.datacamp.com/community/blog/data-science-software-engineering) - discusses the application of Data Science onto software data to answer questions that arise in software development projects.
- [Prof. Dr. Rainer Koschke: Software Analytics in komplexen Software-Projekten](https://www.embedded-software-engineering.de/software-analytics-in-komplexen-software-projekten-a-837834/) - introductory article on Software Analytics (written in German).

## Podcasts

- [Thomas Zimmermann: The productive software engineer (2019)](https://www.microsoft.com/en-us/research/podcast/the-productive-software-engineer-with-dr-tom-zimmermann/) - an interview with Thomas Zimmermann about his current work on software analysis at Microsoft.

## Talks

Experience shared by people who applied Software Analytics in practice.

- [Elmar Juergens: Mining Repository Data to Debug Software Development Teams (2016)](https://www.youtube.com/watch?v=HJg5l9KTLBk) - shows how version control systems can reveal communication problems in development teams.
- [Dirk Mahler: Yes We Scan! Software Analysis Using jQAssistant (2015)](https://www.youtube.com/watch?v=6jDdhW1Wu6A) - software analysis of industry software projects using a graph database.
- [Nicolas Mervaillie: Fix Your Microservice Architecture Using Graph Analysis (2019)](https://www.youtube.com/watch?v=EVtD7OCUIac) - graph-based software analysis is used to analyze a distributed system.
- [Margaret-Anne Storey: Lies, Damned Lies and Software Analytics (2015)](https://www.youtube.com/watch?v=Ujm4G7ayRQQ) - an overview of the history and goals of Software Analytics. I especially like the part where Margaret talks about the risks of Software Analytics like data quality issues, missing trustworthiness of results, and ethical concerns.
- [Oliver Tigges, Philipp Haußleiter: Software Dependency Analysis with Graph Databases (2015)](https://www.youtube.com/watch?v=LpmWgCOP4kQ) - software libraries dependency analysis by using a graph database
- [Adam Tornhill: Prioritizing Technical Debt as if Time and Money Matters (2019)](https://www.youtube.com/watch?v=fl4aZ2KXBsQ) - a fresh look at version control data mining to uncover behavioral patterns of development organizations.
- [Nicki Watt: Explore your Microservices Architecture with Graph Theory & Network Science (2020)](https://www.youtube.com/watch?v=0G5O1ffYIPI) - usage of graph-based algorithms to spot problems in large distrubuted software systems.
- [Thomas Zimmermann: Software Productivity Decoded: How Data Science helps to Achieve More (2018)](https://youtube.com/watch?v=I_AVRfAS7Eg) - talk with an introduction to Software Analytics and its application in Microsoft.



## Hands-Ons

Activities that let you experience Software Analytics all by yourself.

- [Markus Harrer: Software Analytics Workshop (2019)](https://github.com/feststelltaste/software-analytics-workshop-guided) - a repository with a guided tour through first software analysis using Data Science approaches und tools.
- [Markus Harrer: Software Analytics Katas (2021)](https://github.com/feststelltaste/software-analytics-katas) - small challenges designed to train analytical thinking and the use of data-driven software analysis techniques.

## Lists of Tools

There are plenty of tools out there that can support answering your questions in a data-driven way. This section lists existing lists so that you can find your tool that fit your specific needs:

* [Analysis-Tools.dev](https://analysis-tools.dev/) - static analysis tools for many programming languages, build tools, config files and more.
* [Awesome Open Source - Profilers](https://awesomeopensource.com/projects/profiler) - tools for in-depth runtime analysis.
* [OpenAPM](https://openapm.io/landscape) - lists various Application Performance Management tools that can help you to find performance problems.

## Related Awesome Lists

This section lists other awesome lists in the area of data analysis in software development.

* [Awesome Empirical Software Engineering](https://github.com/dspinellis/awesome-msr) - a curated repository of software engineering repository mining data sets.
* [Awesome Machine Learning On Source Code](https://github.com/src-d/awesome-machine-learning-on-source-code) - cool links & research papers related to Machine Learning applied to source code (MLonCode).

## Contribute

Did you like this list? Contributions are very welcome! Read the [contribution guidelines](contributing.md) first and add your ideas!
