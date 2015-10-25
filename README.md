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

- Communal resopositories  
- Documentation and tutorials  
- Forums  

Join us for the first exclusive event that brings together discussions on dockers within Bioinformatics!

**Group Webpage:**http://goo.gl/LuNWKa

**Flyer:**https://goo.gl/ntC7aK

**Getting There:**http://wellcomecollection.org/visit-us/getting-here

**Latest Conference Agenda:**https://goo.gl/LpH07s

****

## Aims (what we want to get out of the meeting)
Placeholder of my (snewhouse) current thoughts. Please contribute.  

- Index of Docker/VM Bioinformatics projetcs  
- F1000 Channel, Editorial and Slide Share    
- API  
- Adapt/Adopt [CWL](https://github.com/common-workflow-language/common-workflow-language) for multi component Docker pipelines  
- RFC  
- ...

## Mini-Hacks, Demos and Tutorials
I have made a start. Please contribute.

TBA: List of potential ideas with [links to code](https://github.com/KHP-Informatics/bioindocker15/tree/master/hack/)
Clone, commit and push please.

- [A hands-on introduction to Docker](https://github.com/ngs-docs/angus/blob/2015/week3/CTB_docker.rst)  
- [Training in Docker from Docker](https://training.docker.com/self-paced-training)  
- [rocker-org - "rocker": R in Docker](https://github.com/rocker-org/rocker)  
- http://www.nextflow.io/  
- http://kubernetes.io/    
- Jetbrains MPS, nextflow, docker integration demo and tutorial ([Fabien Campagne](http://campagnelab.org/pi-contact/))      
- Flocker by https://clusterhq.com/  
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

## Index of Dockered & Related Projects for Informatics  
I have made a start. Please contribute your own repositories and knowledge.  

- [BioDocker - BioDocker.github.io](https://github.com/BioDocker/BioDocker.github.io)  
- [Common Workflow Language](https://github.com/common-workflow-language/common-workflow-language)  
- [bioboxes](https://github.com/bioboxes)  
- [Campagne Laboratory](https://github.com/CampagneLaboratory)  
- [Björn Grüning - Dockerfiles for Bio- & Cheminformatics & Galaxy ](https://github.com/bgruening)  
- [rocker-org - "rocker": R in Docker](https://github.com/rocker-org/rocker)  
- [CloudBioLinux: configure virtual (or real) machines with tools for biological analyses](https://github.com/chapmanb/cloudbiolinux)  
- [bcbio-nextgen - community developed variant calling and RNA-seq analysis](https://github.com/chapmanb/bcbio-nextgen)  
- ...

## Docker Related stuff and Other Geeky-type Fun
- [Jess Frazelle (jfrazelle) - Dockerfiles ](https://github.com/jfrazelle/dockerfiles)  
- [Mac OS X Dev Setup (jfrazelle)](https://github.com/jfrazelle/mac-dev-setup)  
- [Too Much Fun With Docker](http://www.carlboettiger.info/2014/08/07/too-much-fun-with-docker.html)  
- [Autocode  - open source code generator for every language and framework.](http://crystal.sh/#intro)  
- ...

## Participating Organizations
I have made a start. Please contribute  
- [NIHR BRC-MH Bioinformatics Group](https://github.com/KHP-Informatics)  
- ...

## Individual Contributors
I have made a start. Please contribute  
- Stephen J Newhouse <stephen.j.newhouse@gmail.com>  
- ...
