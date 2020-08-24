 ## Employing Contribution and Quality Metrics for Quantifying the Software Development Process

## Authors
Themistoklis Diamantopoulos, Michail Papamichail , Thomas Karanikiotis, Kyriakos Chatzidimitriou , Andreas Symeonidis

### Date
 Tue 30 Jun 2020 10:52 - 11:00 at MSR:Zoom - Evolution Chair(s): Jürgen Cito

### Paper Link
https://issel.ee.auth.gr/wp-content/uploads/2020/05/MSR2020.pdf

## Descritption
we have designed and implemented a platform that analyzes data from GitHub in order to compute a series of metrics that quantify the contributions of project collaborators, both from a development as well as an operations (communication) perspective. We analyze contributions in an evolutionary manner throughout the projects’ lifecycle and track the number of coding violations generated, this way aspiring to identify cases of software development that need closer monitoring and (possibly) further actions to be taken. 

  
## Introduction
The emergence of the open-source initiative has changed the way
software is developed. Software development is now a collaborative
process, taking place in online code hosting facilities, such as
GitHub, Bitbucket or GitLab. And although software engineering
has always relied on effective teamwork, today more than ever we
are able to observe this process transparently and at such a massive
scale.

#### ARCHITECTURE AND TOOLS

      architecture of our platform, which comprises
      four modules: the Data Downloader, the MongoDB Management
      System, the Contributions Analyzer, and the Quality Analyzer. These
      modules are presented in detail in the following paragraphs.

      Data Downloader. It is a Python application that uses the GitHub
      API4 in order to retrieve all information offered for a given repository.
      This information includes commits, issues, commit comments,
      
      MongoDB Management System. We use MongoDB
      our database
      management system, which contains all the raw data retrieved
      from GitHub along with the results of the contributions and the
      quality analysis.

      Contributions Analyzer. It uses the information retrieved from
      GitHub in order to compute a series of metrics that quantify the
      activity of each contributor both in terms of development and
      operations.

      DATASET CONSTRUCTION

      In a development community that is continuously moving towards
      component reuse, online software repositories constitute an integral
      part of the software development process. While this poses a
      series of challenges in terms of managing software development, 

### Research
In this work, we have pursued this
research direction by creating a platform that can be employed to produce useful metrics. Furthermore, we have proposed a set of
metrics and built a large dataset that can be used to answer multiple
research questions. As future work, we plan to augment our dataset,
by adding more repositories and, most importantly, more metrics
that can cover additional development scenarios, such as supporting
various programming languages (e.g. Python, JavaScript).
