# [Bio in Docker] Symposium 2015

[![Join the chat at https://gitter.im/KHP-Informatics/bioindocker15](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/KHP-Informatics/bioindocker15?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

...work in progress..

Eventbrite: http://www.eventbrite.co.uk/e/bio-in-docker-symposium-2015-tickets-16296680811
Twitter: [@bioindocker15](https://twitter.com/bioindocker15)

Docker is now establishing itself as the de facto solution for containerization across a wide range of domains. The advantages are attractive, from reproducible research to simplifying deployment of complex code.
This event will bring together some notable cases to discuss how advantage of this new technology can best be achieved within the Bioinformatics space.  

Day one & two of the event will feature lightning talks from selected speakers.  
Day two will additionally include an afternoon mini-hackday to introduce, demonstrate, and invite participation using Docker on some interesting and well scoped problems (you are encouraged to make suggestions for the hackday topics).

Throughout the course of the event we would like to identify where common goals exist in the bioinformatics arena and explore how efforts in containerized solutions could be aligned by establishing a community of Docker users and resources (with a similar function to that of Bioconductor for R). This could include:  

- Communal repositories  
- Documentation and tutorials  
- Forums  

Join us for the first exclusive event that brings together discussions on dockers within Bioinformatics!

**Group Webpage:**http://goo.gl/LuNWKa

**Flyer:**https://goo.gl/ntC7aK

**Getting There:**http://wellcomecollection.org/visit-us/getting-here

**Latest Conference Agenda:**https://goo.gl/LpH07s

****

## Aims (what we want to get out of the meeting)
There is a BioInDocker15 team which you can request access to [https://github.com/orgs/KHP-Informatics/teams/bioindocker15](https://github.com/orgs/KHP-Informatics/teams/bioindocker15)

Placeholder of my (snewhouse) current thoughts. Please contribute.  

- An understanding of current uses of Docker in the Bio/Informatics world
- Index of Docker/VM Bioinformatics projetcs  
- F1000 Channel, Editorial and Slide Share (and perhaps a short paper documenting the presented work?)
- Bioinformatics Container Specification/API (e.g. [BioBoxes](http://bioboxes.org/))  
- Adapt/Adopt [CWL](https://github.com/common-workflow-language/common-workflow-language) for multi component Docker pipelines  
- RFC  
- ...

## Mini-Hacks, Demos and Tutorials
I have made a start. Please contribute if you'd like to .

TBA: List of potential ideas with [links to code](https://github.com/KHP-Informatics/bioindocker15/tree/master/hack/)
Clone, commit and push please.

### Hackday Topic 1: Orchastration and Multi-container Workflows 
(Paolo Di Tommasso, Nebojsa Tijanic, Brad Chapman, Yannick Wurm, Steven Newhouse, Amos Folarin)
- [nextflow](http://www.nextflow.io/)
- [Rabix] (https://www.rabix.org/#/)
- [Common Workflow Language](https://github.com/common-workflow-language/common-workflow-language)

### Hackday Topic 2: Specifications For Bio/Informatics Containers
(Peter Belmann)
- [BioBoxes](http://bioboxes.org/)
- [rocker-org - "rocker": R in Docker](https://github.com/rocker-org/rocker) 

## Hackday Topic 3: Security and Using Docker in Multi-user environments
(Aanand Prassad? **Other volunteers**?)
- [#15187 User namespaces in experimental branch](https://github.com/docker/docker/wiki/Engine-1.9.0)
- [Docker security](https://docs.docker.com/articles/security/)  
- [Hypervisor-agnostic Docker Engine_](https://hyper.sh/)  
- ...

### Hackday Topic 4: Community requirements
(Thomas Ingraham, Michael Markie)
- [Docker F1000 Channel for Docker publications](http://f1000research.com/channels/containers)
- If separation from DockerHub is needed (I don't think so myself) [Portus](https://github.com/SUSE/Portus)

### Hackday Dojo 1: Introduction to Docker
(Anand Prassad, Kai Davenport)
- [A hands-on introduction to Docker](https://github.com/ngs-docs/angus/blob/2015/week3/CTB_docker.rst)  
- [Training in Docker from Docker](https://training.docker.com/self-paced-training)  
 

### Hackday Dojo 2: Advanced Docker Concepts Dojo
(Matt Bates, Matt Barker, Alfonso Acosta Kai Davenport)
- [Flocker by ClusterHQ](https://clusterhq.com/)
- [Jetstack](http://www.jetstack.io/)
- [kubernetes](http://kubernetes.io/) 
- [weave](http://weave.works/) 


###Other hackday Suggestions (**need fleshing out**)
- Intel: Hack using docker on arduino for stream processing NGS sequence data.  
- [Jetbrains MPS, nextflow, docker integration demo and tutorial, Fabien Campagne](http://campagnelab.org/pi-contact/))      
- ...

## The problem with Informatic pipelines  
I have made a start. Please contribute.
- Reproducible ?
- Mutli-component  
- Each component has different dependencies (eg Python2.7 v Python3.0)
- Each component written in a different Language  (python, java etc etc)
- Each component has multiple options for tweaking the input and output  
- Each component requires multiple inputs
- Each component produces multiple outputs   
- Disk I/O (pipes)  
- Large files eg. for NGS  10's-100's GB per input/output  
- Pipeline components often require access to large shared data and databases (eg NGS Reference Genomes and annotation files)
- Binaries not often available, requires build from source  
- Not easy to set up and reproduce for non-informaticians  
- *Can be hard for informaticians if code is bad, dependency heavy, undocumented or requires very specific versions of OS's and software etc*
- Often Suffers from: *"But It works on my Machine??"*  



Some random thoughts...  
**Only trusted users should be allowed 1) Access to HPC and 2) To control your Docker daemon**.  
Who is the malicious Hacker that will delete all files and take down your system or make it all public?
Lets make breaches of security a criminal offence.
In the Academic (Bio)Informatic world, most users are basic or clinician scientists with little computer skill.
We the sys. admins and trusted informaticians should set up the pipelines and provide users with push button solutions. We should control what gets run and when, so that all a user has to do is log in and select a pipeline to run on their data.

## Index of Dockered & Related Projects for Informatics  
I have made a start. Please contribute your own repositories and knowledge.  

- [Docker on GitHub](https://github.com/docker/docker)  
- [BioDocker - BioDocker.github.io](https://github.com/BioDocker/BioDocker.github.io)  
- [Common Workflow Language](https://github.com/common-workflow-language/common-workflow-language)  
- [bioboxes](https://github.com/bioboxes)  
- [Campagne Laboratory](https://github.com/CampagneLaboratory)  
- [Björn Grüning - Dockerfiles for Bio- & Cheminformatics & Galaxy ](https://github.com/bgruening)  
- [rocker-org - "rocker": R in Docker](https://github.com/rocker-org/rocker)  
- [CloudBioLinux: configure virtual (or real) machines with tools for biological analyses](https://github.com/chapmanb/cloudbiolinux)  
- [bcbio-nextgen - community developed variant calling and RNA-seq analysis](https://github.com/chapmanb/bcbio-nextgen)  
- [2015-09-04-Building-a-secure-multi-tenant-Docker-based-Platform-as-a-Service-Part-1-Design-Considerations](https://github.com/catalyzeio/engineering-blog/blob/master/source/2015-09-04-Building-a-secure-multi-tenant-Docker-based-Platform-as-a-Service-Part-1-Design-Considerations.html.markdown)
- [2015-09-18-Building-a-secure-multi-tenant-Docker-based-Platform-as-a-Service-Part-2-Implementation](https://github.com/catalyzeio/engineering-blog/blob/master/source/2015-09-18-Building-a-secure-multi-tenant-Docker-based-Platform-as-a-Service-Part-2-Implementation.html.markdown)  
- ...

## Docker Related stuff and Other Geeky-type Fun
- [Great visual overview of Docker's inner workings](http://merrigrove.blogspot.co.uk/2015/10/visualizing-docker-containers-and-images.html?m=1)
- [Docker Cheat Sheet](https://github.com/wsargent/docker-cheat-sheet)
- [Jess Frazelle (jfrazelle) - Dockerfiles ](https://github.com/jfrazelle/dockerfiles)  
- [Mac OS X Dev Setup (jfrazelle)](https://github.com/jfrazelle/mac-dev-setup)  
- [Too Much Fun With Docker](http://www.carlboettiger.info/2014/08/07/too-much-fun-with-docker.html)  
- [Autocode  - open source code generator for every language and framework.](http://crystal.sh/#intro)
- [Best Practices for Scientific Computing](http://www.plosbiology.org/article/fetchObject.action?uri=info:doi/10.1371/journal.pbio.1001745&representation=PDF)   
- [A Quick Guide to Organizing Computational Biology Projects](http://www.ploscompbiol.org/article/fetchObject.action?uri=info:doi/10.1371/journal.pcbi.1000424&representation=PDF)  
- [Ten Simple Rules for Reproducible Computational Research](http://www.ploscompbiol.org/article/fetchObject.action?uri=info:doi/10.1371/journal.pcbi.1003285&representation=PDF)    
- ...

## Participating Organizations
I have made a start. Please contribute  
- [NIHR BRC-MH Bioinformatics Group](https://github.com/KHP-Informatics)  
- ...

## Individual Contributors
I have made a start. Please contribute  
- Stephen J Newhouse <stephen.j.newhouse@gmail.com>  
- ...
