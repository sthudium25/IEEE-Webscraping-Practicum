# IEEE-Webscraping-Practicum
An overview presentation of work in collaboration with the Institute for Electrical and Electronics Engineers (IEEE) 

Under the guidance of a data science team at IEEE, the UPenn team (myself and four others) set out this semester to build an intelligent web scraping model capable of identifying “scholarly entities” of interest using seed information related to an author. For our purposes, scholarly entities refers to active web pages online that contain data or information directly related to an author’s professional work; examples include professional profiles like Google Scholar and LinkedIn, news articles about a component of the author’s work, and GitHub repositories that store code for or build off of an author’s research, among others.

Seed information is defined as data gathered from the IEEE data lake that provide context about a given author; examples include the author’s name, their most recent affiliation, and the names of their publications.

To this end, we have developed a python package, scholarscraper. This package is an API allowing access to an end-to-end pipeline that efficiently combs the web for links relevant to authors of interest. We designed this innovative tool from scratch to utilize machine learning (ML) and advanced natural language processing (NLP) techniques for scraping, sorting, and classifying the collected data into predefined categories. We developed two parallel approaches to solve this problem; these strategies are: Top-Down and Bottom-Up. The Top-Down approach leverages Common Crawl, which is a vast repository of web pages scraped since 2008. The Bottom-Up approach harnesses the power of Google to perform a targeted search based on author seed data.

IEEE owns all work conducted for this project so the full package cannot be made public. However, I hope that the presentation and technical report above give some insight into the hard work that we put into this deliverable.
