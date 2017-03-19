+++
date = "2016-11-05T21:05:33+05:30"
title = "About DataOps.info"
+++

DataOps.info is a website created in 2016 to start the sharing of resources aabout DataOps.

Anyone can contirbute a Pull Request that addsa a resource, or you can provide us the info via our [Contact Us](../contact) page.

## What is DataOps?
The following excerpt is from [DataOps - It's a thing (honest)](https://itsalocke.com/dataops-its-a-thing-honest/)

### What is DevOps?
For folks not up on the DevOps side of things, DevOps is bridging the gap between different teams, both culturally and technologically, to reduce the risk and cost of software development in an organisation. Culturally, it means things like ownership of changes, “left-shifting” responsibility for testing, and lower manual approvals. Technologically, it means things like unit testing, immutable architecture, Continuous Integration (CI), Continuous Delivery (CD), real-time application monitoring and alerting.
### So what is DataOps?
The first part of DataOps is perhaps the most obvious - the database! [Database Lifecycle Management (DLM)](http://www.red-gate.com/blog/long-live-revolution) is the work Microsoft & Redgate are doing to facilitate [unit testing](http://artofunittesting.com/definition-of-a-unit-test/), CI &amp; CD, and pipeline management for databases. DLM has been primarily used to improve the development &amp; maintenance of application databases. As such it should be a significant component for a DevOps team. *But* OLTP is not the only database use case in town - data warehouses and data marts need some love too. DLM can work well with these, but few devs want to build data warehouses so DLM cannot be solely under the purview of DevOps. So for the developers/analysts building data warehouses, please embrace DLM, and for the tool makers, please help cater to the needs of people who aren't always the most comfy with code.

The next aspect is "traditional BI" a.k.a data transformation and loading (ETL), cubes, and reporting. These are historically developed using GUIs with limited tooling and support for the sort of practices we could expect in a DevOps environment. It is getting better with BIML, some [unit testing facilities](http://itsalocke.com/database-bi-related-unit-testing-options/), and MS Build but it's still not there. It should be. Yeah, applications are the thing which make money, but the insight from BI is what helps people direct the resources into improving said applications and managing the company generally. You need these things, and you need them to be right - so we should be adding as many facilities to check that things are right as possible.

The final major area is analytics aka data science, statistics, data mining, machine learning. In BI correctness is key – but we’re only ever aiming for correctness at the point of presentation. Analytics is aiming to be reasonably accurate consistently over people and time. That’s a really hard thing since when you start changing things, you can’t tell what would have happened if you hadn’t, unless you experiment. You need to be able to account for changing behaviour over time, and changes to data capture etc. This means your modelling has to be update-able and refinements easy to deploy, and at the same time remaining robust and auditable. Coded analysis, regular retraining, testing, and a validation and deployment pipeline are all needed to facilitate on-going analytics. Analytics has to be automated to be able to cope so incorporating the techniques of DevOps into the area is vital.

So folks, DataOps is a thing and it is the application of DevOps principals to data-centric applications. Enjoy!

<iframe width="560" height="315" src="https://www.youtube.com/embed/64PIa9gcuh0" frameborder="0" allowfullscreen></iframe>