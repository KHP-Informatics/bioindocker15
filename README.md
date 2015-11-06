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

Please contribute.  

- An understanding of current uses of Docker in the Bio/Informatics world
- Index of Docker/VM Bioinformatics projetcs  
- F1000 Channel, Editorial and Slide Share (and perhaps a short paper documenting the presented work?)
- Bioinformatics Container Specification/API (e.g. [BioBoxes](http://bioboxes.org/))  
- Adapt/Adopt [CWL](https://github.com/common-workflow-language/common-workflow-language) for multi component Docker pipelines  
- RFC  
- ...

## F1000 Channel Launch: *Container Virtualization in Informatics*
Please join us for the launch of the new F1000 Channel:[Container Virtualization in Informatics](http://f1000research.com/channels/containers/about-this-channel). Official name TBC.

**About this Channel**

Technologies such as Docker are now establishing themselves as a lightweight solution to packaging applications together with their dependencies, solving a range of problems from reproducible research to simplifying deployment of complex code. This channel highlights literature in F1000Research on uses of containers, published container images, workflows and microservices.

## Mini-Hacks, Demos and Tutorials
I have made a start. Please contribute if you'd like to.

These are suggestions we have put together from our poll or attendees and some ideas myself and Steve had. We have requested one or more some of the speakers to run a session, we'll try and get an idea of who is interested in participating in which session before the end of the first day.  

###Hackday Resources
- [x] AWS EC2 VMs (available on request)
- [x] Intel Edison boards
- [x] Laptops BYOD (but the venue kindly asks that they are PAT-tested)
- [x] This git repository (but created others as needed and we'll link to them here)

TBA: List of potential ideas with [links to code](https://github.com/KHP-Informatics/bioindocker15/tree/master/hack/)
Clone, commit and push please.

### Hackday Topic 1: orchastration and multi-container workflows
(Paolo Di Tommaso, Nebojsa Tijanic, Brad Chapman, Yannick Wurm, Steven Newhouse, Amos Folarin)
- [Nextflow](http://www.nextflow.io/)
- [Rabix] (https://www.rabix.org/#/)
- [Common Workflow Language](https://github.com/common-workflow-language/common-workflow-language)

### Hackday Topic 2: specifications for bio/informatics containers
(Peter Belmann)
- [BioBoxes](http://bioboxes.org/)
- [rocker-org - "rocker": R in Docker](https://github.com/rocker-org/rocker)

## Hackday Topic 3: security and using Docker in multi-user environments
(Aanand Prassad? **Other volunteers**?)
- [#15187 User namespaces in experimental branch](https://github.com/docker/docker/wiki/Engine-1.9.0)
- [Docker security](https://docs.docker.com/articles/security/)  
- [Hypervisor-agnostic Docker Engine_](https://hyper.sh/)  
- ...

### Hackday Topic 4: bio/informatics Docker users community requirements
(Thomas Ingraham, Michael Markie)
- [Docker F1000 Channel for Docker publications](http://f1000research.com/channels/containers)
- If separation from DockerHub is needed (I don't think so myself) [Portus](https://github.com/SUSE/Portus)

### Hackday Tutorial 1: introduction to Docker
(Anand Prassad, Kai Davenport)
- [A hands-on introduction to Docker](https://github.com/ngs-docs/angus/blob/2015/week3/CTB_docker.rst)  
- [Training in Docker from Docker](https://training.docker.com/self-paced-training)  


### Hackday Tutorial 2: advanced Docker concepts
(Matt Bates, Matt Barker, Alfonso Acosta Kai Davenport)
- Docker: Compose, Machine, Swarm, Overlay Networking
- [Flocker by ClusterHQ](https://clusterhq.com/)
- [Jetstack](http://www.jetstack.io/)
- [kubernetes](http://kubernetes.io/)
- [weave](http://weave.works/)

### Hackday Tutorial 3: introduction to the NextflowWorkbench, its Docker IDE and its bioinformatics features
(Fabien Campagne) 

*The tutorial will demonstrate the interactive capabilities of the [NextflowWorkbench](http://workflow.campagnelab.org). The tutorial will use Docker, but assumes no prior knowledge of docker. I suggest to download the software and images prior to the start of the tutorial [[follow these instructions]](http://campagnelab.org/software/nextflow-workbench/instructions-for-workflow-tutorial/). If you are able to complete the installation instructions, you will be able to follow the tutorial and learn how to create or run workflows with docker.*
- **Mini-intro to the MPS platform** (5': plugins, solutions, models, languages and devkits)
- **Creating a workflow with NextflowWorkbench** (10': We will simple workflow to process a set of reads and simply print the filenames. This minimal example will illustrate the structure of workflows and demonstrate auto-completion, automatic type calculation and error detection)
- **Using bioinformatics resources in workflows** (15': We will continue and mofify the workflow to use Kallisto to estimate counts from each reads file. We are able to do this in 15' by reusing (1) automated installation of GobyWeb resources  (2) a docker image that provides all the software needed to install these resources (3) a frozen docker image that includes the pre-built Kallisto human transcriptome index).


###Other hackday Suggestions (**need fleshing out**)
- Intel: Hack using docker Intel Edison boards (we have some of these to distribute) if you want to participate in this. Intel are interested in applying this for stream processing NGS sequence data(?). **@elij to Elaborate**  
- Installing [ubilinux](http://www.emutexlabs.com/ubilinux) on Intel Edison
- [Upgrading Ubilinux Debian Wheezy to Jessie](https://github.com/catmaker/chippy/wiki/Upgrading-Ubilinux-Debian-Wheezy-to-Jessie)
  
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
- [Reproducibility in Science - Nextflow meets Docker](http://www.nextflow.io/blog/2014/nextflow-meets-docker.html)
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
- [Docker Ecosystem](https://www.mindmeister.com/389671722/docker-ecosystem)
- ...

## Participating Organizations
I have made a start. Please contribute  
- [NIHR BRC-MH Bioinformatics Group](https://github.com/KHP-Informatics)  
- ...

## Individual Contributors
I have made a start. Please contribute  
- Stephen J Newhouse <stephen.j.newhouse@gmail.com>  
- Amos Folarin <amosfolarin@gmail.com>
- Paolo Di Tommaso <paolo.ditommaso@gmail.com>
- ...

# Event Sponsors
- [Genomics England](http://www.genomicsengland.co.uk/)
- [Software Sustainability Institute](http://www.software.ac.uk/)
- [Intel](http://www.intel.com/)
- [Docker](https://www.docker.com/)

## Pipeline Pics...
**GATK** : [best-practices](https://www.broadinstitute.org/gatk/guide/best-practices)
![gatk-pipeline](https://github.com/KHP-Informatics/bioindocker15/blob/master/pictures/gatk-9565118b9a6fb66daba37d2d7a8527.png)
