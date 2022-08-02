# Storage & Analysis(& Security)

<span style="color:#1E1E1E">What a</span> re my optio <span style="color:#1E1E1E">ns for effectively organizing\, storing\, securing\, computing\, and analyzing my research data?</span>

_Goals:_

_Know what resources are available_

_Understand best practices_

_Know where to get help_

# Storage & Analysis: Questions

What speaks to you about Data Security?

What storage resources are available at HBS?

How might you collaborate with other when using data?

What compute resources do you have to use??

# Storage & Analysis

* This is the most difficult & time\-consuming RDM stage
* Likely need to perform\, rinse\, & repeat
* _So\.\._
* Should be effortless if one has planned well…
  * 5Ps:  _Proper Planning Prevents Poor Performance_
* …and if done well 1st time around
* Security is just as important during these steps\!

![](images/RDM%20workshop%20slides13.png)

# Resources for Storage

* This will vary based on data sensitive data level and indicated by DUA\, IRB\, or Data Security plan
* See IT Security handout for appropriate considerations
* May often be directed by faculty or RC Center member
* Consult local research computing center / environment
  * Research storage associated with a compute cluster
  * Database server
  * School and HU collaboration tools \(E\.g\. SharePoint\, OneNote\)

* HBS:
* IT\-issued desktops / laptops storage \(usually SSD\)
* _Collaboration_  or  _project folders_  on research storage for group work
  * Associated with HBSGrid cluster
  * \\\\hbsfiles storage
* Other schools:
* Lab folders offer equivalent functionality

[https://](https://researchdatamanagement.harvard.edu/storage-analysis-computation)[researchdatamanagement\.harvard\.edu](https://researchdatamanagement.harvard.edu/storage-analysis-computation)[/storage\-analysis\-computation](https://researchdatamanagement.harvard.edu/storage-analysis-computation)

# Other storage resources?

* FASRC's compute environment\*
* IQSS' compute environment
* Cloud providers: Mass OpenCloud\, AWS\, Azure\, GCP\, etc\*
* 3rd party\-licensed providers
  * Qualtrics\, Zotero\, etc
  * DropBox\, OneDrive\, Box\, etc
* See websites for data transfer options:
  * [https://grid\.rcs\.hbs\.org/transferring\-data](https://grid.rcs.hbs.org/transferring-data)
  * [https://security\.harvard\.edu/secure\-file\-transfer](https://security.harvard.edu/secure-file-transfer)

\*Some costs may be associated with use\. Please contact RCS first

# Collaboration Tools: Data Security & Privacy

![](images/RDM%20workshop%20slides14.png)

The University has determined that the Zoom cloud does not have the appropriate controls to protect Level 4 data\. This means that it cannot be used to record research interviews\, as recordings include conversations which could cause social harm to the participants should they be obtained by individuals with ill intent\,  __which is considered to be Level 4 data even if the full scope of the video is not intended to be used__ \. Unfortunately\, at this time\, the University has not approved any cloud\-based solutions for video recording research interviews\.

![](images/RDM%20workshop%20slides15.png)

__What does "consumer" mean?__  A "consumer" account is a service which you have signed up for on your own\. Even if it is being paid for with a Harvard credit card\, it is considered a consumer account\, unless it is protected by a Harvard contract\. Consumer Versions of cloud software not recommended for University business\.

[https://security\.harvard\.edu/collaboration\-tools\-matrix](https://security.harvard.edu/collaboration-tools-matrix)

# Resources for Analysis

* Local computing environment:
  * HBS\-issued desktop / laptops \(data\-intensive work – please talk to RCS/RSS\)
  * Home computer\, with appropriate security measures
* Remote environments
  * HBSGrid compute cluster \, FASRC Cannon\* cluster\, IQSS' RCE\, HMS O2
  * Be thoughtful and strategic about use and efficiency
    * Offload long\-running work to the compute cluster
    * If something isn't running as expected\, troubleshoot or ask for help

* Cloud commercial vendors\*:
  * Amazon Web Services \(AWS\)\, Google Cloud\, Microsoft Azure
  * Please sign\-up under Harvard contract \(tenant\)
  * They provide support for secure storage & compute\, BUT ensure they meet your security requirements \(storage location\, sufficient security\)
* Open\-source Cloud systems \(not vetted\)
  * OpenStack\, OpenNebula\, Mass\. OpenCloud
* National Supercomputing Centers
  * XSEDE umbrella of compute resources

\*some costs may be associated with use

[https://](https://researchdatamanagement.harvard.edu/storage-analysis-computation)[researchdatamanagement\.harvard\.edu](https://researchdatamanagement.harvard.edu/storage-analysis-computation)[/storage\-analysis\-computation](https://researchdatamanagement.harvard.edu/storage-analysis-computation)

# Storage and Analysis

![](images/RDM%20workshop%20slides16.png)

# Storage & Analysis: Questions

How might one use Version Control?

Describe an example of good project organization?

Why are workflow tools important?

# Doing the work…

![](images/RDM%20workshop%20slides17.wmf)

We organize our recommendations into the following topics \( <span style="color:#2B5BF9">Box 1</span> \):

Data management: saving both raw and intermediate forms\, documenting all steps\, creating

tidy data amenable to analysis\.

Software: writing\, organizing\, and sharing scripts and programs used in an analysis\.

Collaboration: making it easy for existing and new collaborators to understand and contribute to a project\.

Project organization: organizing the digital artifacts of a project to ease discovery and understanding\.

Tracking changes: recording how various components of your project change over time\.

Manuscripts: writing manuscripts in a way that leaves an audit trail and minimizes manual merging of conflicts\.

<span style="color:#2B5BF9">[https://doi\.org/10\.1371/ journal\.pcbi\.1005510 ](https://doi.org/10.1371/%20journal.pcbi.1005510)</span>

![](images/RDM%20workshop%20slides18.png)

[https://drivendata\.github\.io/cookiecutter\-data\-science/](https://drivendata.github.io/cookiecutter-data-science/)

# Project Setup & Organization, part 1

| Put each project in its own directory, which is named after the project |
| :-: |
| Create folders that will separate your code and data<br /><br /> |
| <br />In your data folder, ensure that your raw data are separated from any data you have processed (i.e., your clean datasets)<br /> |

![](images/RDM%20workshop%20slides19.png)

![](images/RDM%20workshop%20slides20.png)

![](images/RDM%20workshop%20slides21.png)

| Create additional folders as needed for project. E.g., report folder for output; references folder for reference material such as survey instrument.<br />Create a "README" file that outlines basic information about the project and the folder/file structure.<br /><br />Name files in a way that their content or function can be easily identified. <br />Use relative addressing to make the project portable |
| :-: |


![](images/RDM%20workshop%20slides22.png)

![](images/RDM%20workshop%20slides23.png)

# Languages & Tools Recommendations*

* Programming languages for processing and analyzing data in research:
  * Most used: Python \(Spyder as editor\) and R \(RStudio as editor\)
  * Others: Scala\, Java\, Julia
* Statistical packages:
  * Stata\, R\, SAS\, & SPSS
* Big Data tools:
  * Spark \(Hadoop\)\, Kubernetes/containers
* Data Visualization tools:
  * ggplot2\, Tableau\, D3\, Shiny\, Plotly\, Pandas\, WorldMap \(from HU's CGA\)

\*This list is not meant to be exhaustive\!

# Documenting workflows & analyses

* Whatever tool you use\,  __document all steps__  in your analysis and data transformations\. Some tools to help with that:
* RMarkdown and RMarkdown Notebooks \(used with R\)
* Jupyter Notebooks: support for most languages \(Python\, R\, Stata\, MATLAB\)
* Dyndoc \(notebook for Stata\)
* Templates with OneNote \(or EverNote\)
* Workflow/Pipeline Tools
  * These help document and track process order:
  * Consider Drake \(R\); SnakeMake\, doit or py\-Make \(Python\); and make for other systems
  * See [https://github\.com/pditommaso/awesome\-pipeline](https://github.com/pditommaso/awesome-pipeline) for a full list of options
* Be sure to update your data dictionary/codebook as you make changes to your data
* Your future self will thank you\!

# Versioning and version control

* Incredibly important given the duration and lifespan of projects
* What may start out as small\, test idea may grow organically into multi\-person and multi\-site research project
* Two approaches given\, for small to large…
* Manual versioning
  * In most cases\, data will be organized in files under directories:
    * Use phase title\, unique identifiers\, and descriptive filenames
    * Prefix by date \(yyyy\, yyyy\.mm\.dd\, yyyy\_mmdd\, yymmdd\)
    * Reserve / display 3\-letter file extension for file format\, such as \.txt\, \.pdf\, or \.csv\.
  * Note all changes in a ReadMe\.txt or Changes\.txt document
* Use a version control system via Git or Github\.com
  * Use your judgement\, and talk to your faculty advisor; BUT their non\-use does not prevent your use
  * Utilize Github\.com web interface for external \(non\-HU\) collaboration\, and code\.harvard\.edu for internal\-only use
  * Command\-line \(terminal/shell\) Git or Git\-GUI like GitKraken
* _NB_ \! HBS/IQSS Version Control Class offered each semester

![](images/RDM%20workshop%20slides24.png)

__Source__ : PHD Comics\. 2012\.  __Piled Higher and Deeper\. __  _[http://phdcomics\.com/comics/archive\.php?comicid=1531](http://phdcomics.com/comics/archive.php?comicid=1531)_

# Databases for (un)structured data

* Storing and use data in a database for easy\, fast queries\!
* When data contain complex relationships or relating data to multiple sets of files
* "Structured" data: SQL databases \(MySQL\, PostgreSQL\, MariaDB\)
* Textual/"unstructured" data: Non\-SQL databases \(MongoDB\, Cassandra\)
* Benefit: data is read\-only\, unless explicitly changed
* Consider versioning the data / databases also
* Update your data dictionary describing data\, types\, use\, etc\.
  * Consider storing it\, as well as change information\, as a part of the database

* HBS RCS provides MariaDB as a part of the RC environment:
  * Provision and guidance on data modeling and DB development
  * Advise on best practices and performance tuning
* FASRC & HMS offer equivalent resources
* Cloud vendors have similar offerings

# Training Opportunities

![](images/RDM%20workshop%20slides25.jpg)

* RC Centers & HU Libraries offers tool & analysis environment training\, both on\-campus and remote
  * E\.g\. Intro to R / Python\, Automating Work\, Version Control\, etc\.
* Data collections & analytical methods
  * Web scraping\, causal inference\, natural language processing
* Offered fall and spring\, and announced through newsletters\, websites\, and Harvard Training Portal \(Category: [Research Computing](https://trainingportal.harvard.edu/Saba/Web_spf/NA1PRD0068/app/shared;spf-url=common%2Fcategorydetail%2Fcateg000000000005221%2Fxxemptyxx%2Fxxemptyxx%2FALL)\)

# Storage, Security, & Analysis Exercise

![](images/RDM%20workshop%20slides26.png)

_You have transferred the data and are storing it on the _  _HBSGrid_  _ along with the older data\. You notice that the data and code from five years ago are a bit\.\.\.disorganized\._

Recall that project materials will need to be easily accessible to a collaborator from USC\. Who could you contact to ensure that a collaborator can access the data and code?

How would you go about organizing and documenting the previous files?

How will you organize the new code and files?

How will you document your processes?

What type of version control system will you employ?

# Storage, Security, & Analysis: Recap

Many resources are available for storage and computation \(desktop\, laptop\, HBS grid\, cloud\)\, but the storage must be appropriate for the security level\.

Important to organize code/files and document processes

RCS offers consultations and trainings on storage and analysis\.

__References:__

Baker Library Research Data Program: [https://www\.library\.hbs\.edu/Services/Research\-Data\-Program](https://www.library.hbs.edu/Services/Research-Data-Program)

HU Libraries Data Networks: [https://](https://hlrdm.library.harvard.edu/network)[hlrdm\.library\.harvard\.edu](https://hlrdm.library.harvard.edu/network)[/network](https://hlrdm.library.harvard.edu/network)

HU Working Remotely: [https://](https://www.harvard.edu/coronavirus/work-remotely)[www\.harvard\.edu](https://www.harvard.edu/coronavirus/work-remotely)[/coronavirus/work\-remotely](https://www.harvard.edu/coronavirus/work-remotely)

_[http://security\.harvard\.edu/dct](http://security.harvard.edu/dct)_

_[https://github\.com/pditommaso/awesome\-pipeline](https://github.com/pditommaso/awesome-pipeline)_

Github\.com

Github Enterprise @ Harvard: [http://code\.harvard\.edu](http://code.harvard.edu/)

Cookie Cutter Data Science: [https://bit\.ly/2NXTVGI](https://bit.ly/2NXTVGI)

Wilson G\, Bryan J\, Cranston K\, Kitzes J\, Nederbragt L\, Teal TK \(2017\) Good enough practices in scientific computing\. PLoS Comput Biol 13\(6\): e1005510\. [https://doi\.org/10\.1371/journal\.pcbi\.1005510](https://doi.org/10.1371/journal.pcbi.1005510)

[https://researchdatamanagement\.harvard\.edu/storage\-analysis\-computation](https://researchdatamanagement.harvard.edu/storage-analysis-computation)

Harvard Training Portal: [Research Computing](https://researchdatamanagement.harvard.edu/storage-analysis-computation)

# Storage and Analysis

![](images/RDM%20workshop%20slides27.png)

