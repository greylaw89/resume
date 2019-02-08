<link rel="stylesheet" type="text/css" href="style.css">

<div id="title">Kristoffer Law</div>

<div id="contact">
<span id="email">klaw@kslaw.me</span>
</div>

# General Attributes

## Interpersonal

+ Highly amicable and fun to work with (or so I have been told)
+ Willing to accept and will ask for criticism on any domain of my job
+ Seeks to understand information, not just to know about it
+ Capable of analyzing various economic and technical trade offs for a given solution
+ Ability to work with various contractors or consultants, network and monitor their progress on a given task
+ Picked up various industry information over the years from Biologists, Planners, Engineers, Consultants, etc.
+ Assisted in the hiring process for my replacement multiple times
	- Last time directly responsible for the hiring of a suitable candidate
+ Willing to teach technical knowledge to any coworkers who would like to learn
	- Trained a coworker in Python for ArcGIS
	- Assisted numerous employees with IT problems
	- Capable of communicating high level concepts via simplified terms
+ Able to empathize with and understand multiple sections of the business domain
	- Have some experience as a small business owner
+ Willing to perform tasks outside of my job description
	- Includes physically intensive labor
	- Includes travel over large distances

## Technical

+ Both broad and deep knowledge of a variety of technical topics in the GIS/IT/Development arenas
+ Capable and very excited to learn any technical or logical topic, keeping pace with the evolving technology
+ Capable of researching topics without assistance, as well as taking initiative to learn about various technical and business processes
+ Able to pick up business processes relatively quickly from coworkers and managers, with a few repetitions
+ In the past, been able to automate some repetitive tasks
+ Basic office products like Word, open source equivalents, and various formulas, queries, style sheets, etc.
+ Familiar with various licensing requirements, for software and other intellectual property
+ Capable of assessing interoperability between various software and file types
+ Enjoy tinkering on my own time with products and will find new means to achieve a given task
	- This resume is written with Markdown, transformed into HTML, and turned into a PDF with Chrome
	- Completely separates formating from content, a highly applicable concept to GIS, IT and Development
	- All the power of the web's CSS style system, capable of being applied to it (I can do this in MS Word, but why not)

# Work Experience

## GIS
+ 10 years of GIS experience, starting with a local government agency in 2009
+ Heavy ArcGIS Server / ArcGIS Online (AGOL) experience
	- Setup, administration, use, and as a development environment
	- Includes knowledge about Portal
	- Includes WebAdapter, IIS, and certificate configuration
	- Database versioning with Esri's system (setup, administration and use)
	- Knowledge of the various features, service types, and technologies, and where best to apply them
+ Heavy ArcMap and ArcGIS Pro experience
	- Already migrated personally to ArcGIS Pro for Python 3
	- Advanced geoprocessing (not just the tools, the Python API as well)
	- Ability to script practically anything in these programs
	- Ability to integrate other applications with ArcGIS or AGOL (depending on application and request)
+ Heavy ArcGIS Collector, and Survey123 experience
	- From a development, administrative and user standpoint
	- Capable of designing and maintaining a wizard form based collection system in Survey123, or alternative Xforms implementations
	- Administration of a multi-editor environment, and updating AGOL information online via scripts and/or ArcGIS Pro
+ Basic networking and Raster analysis
	- While not a heavy focus of mine, I'm familiar enough with the underlying concepts enough to adapt in a couple hours
	- This would include things like utility or road networking, and the specific operations performed on an type of network (at least in an abstract sense)
	- Able to use 3rd party Python packages as well, if certain extensions are unavailable
+ Familiarity with various projection systems
	- Using them for measurements / analysis (got burned once, never again)
	- Using them for web service deployment
	- Knowledge of the location, unit, and use of them (including WKID codes, useful for coding or third party GIS)
+ Frustration management when stuck with a basic ArcGIS license
	- Wrote custom geoprocessing tools that performed Near and Erase operations using the ArcPy API
	- Various work flows to manage license restrictions
+ Open Source / Freeware GIS solutions, mainly Google Earth, QGIS, PostGIS, and various Python libraries.
	- Can create static maps (Paper, PDF, PNG, etc) with equal ability in QGIS as with ArcMap or ArcGIS Pro
	- Can perform basic to mid-range analysis with open source tools
	- Includes knowledge of GeoJSON (both the open and Esri variants), Leaflet, OpenLayers as well as their integration with Esri and AGOL
	- Possess knowledge of Esri's open open source efforts and API (given enough time and resources, could write a basic "ArcGIS" server)

## IT
+ 20 years of IT experience, starting from childhood performing basic tasks such as reinstalling Windows
+ Established good relationships with IT in all prior jobs
+ Basic help desk assistance, Outlook, Printer, and basic troubleshooting, etc.
+ Virtualization experience though VmWare / VirtualBox
	- Setup and maintained VmWare Esxi hosts and Vsphere management console, as well as deploying and maintaining VMs, taking snapshots, etc.
	- Heavy personal use of VirtualBox to test applications and alternative operating systems
+ Setup and management of various servers
	- Windows or Linux
	- Web (IIS / Nginx)
	- Syslog and log analysis tools
	- Print and file servers
	- Phone and voice mail systems (CUCM / FreePBX / Asterisk)
	- Understanding of port configuration, TLS/SSL certs, etc.
+ Active Directory knowledge and administration
	- User account creation, deletion, integration with Office365, etc
	- Includes knowledge of LDAP integration and some other authentication platforms, as well as Kerberos
+ Office365 administration and use
	- Word, Excel, Access, etc. Online versions as well
	- Can stand up Sharepoint sites, OneDrive admin and space allocation, etc.
+ Various networking knowledge
	- Firewall port management and IP assignment
	- Basic cabling, punch-down, testing, etc.
	- Knowledge of the OSI model and various pieces of equipment on it

## Development
+ Large amount of disparate experience, mostly scripts with a bit of development. Not really a full programmer, but I can understand them easily.
+ Familiarity with VirtualBox, Chrome Development Tools, Fiddler, Docker, Notepad++, Linux Make/Compile, etc.
+ Familiarity with a decent number of algorithms and development patterns, independent of technologies used.
+ Average SQL knowledge, with a decent amount of experience working with SQL Server, PostgreSQL, SQLite, and Access
+ Average Python 2 & 3, with a focus on GIS capabilities, specifically the ArcPy and ArcGIS Online APIs
+ Average familiarity with Regex and pattern recognition
+ Decent HTML, CSS, and Javascript (Browser and NodeJS)
+ Very basic knowledge of PostgreSQL programming
+ Very basic C, C++, and Lua knowledge

## Project Samples

### SCE Service Area Mapping
+ Creation of a large set of labeled maps for SCE's line maintenance and service area management
+ Massive labeling and stylization requirements per map. (forced ArcMap to 100% CPU and crashed!)
+ Automated the creation of MXDs, and managed the manual labeling process.
+ Created a scope for potentially automating or upgrading the map system (labels in this case where originally stored in the MXD, rather than a database), this was declined and SCE upgraded later.
+ Drafted the development process for automating labels and stylization for SCE's lines, this was discarded for economic reasons however.

### Vector Control Survey123 Form
+ Used for collection of Mosquito abatement visitations
+ Tracked various information, such as the type of mosquito and chemicals used to combat it.
+ Utilized Xform logic to control the flow of data entry (think less spreadsheet and more wizard)
+ Solution allowed vector control to rapidly and quickly on board seasonal staff members.

### BioGDB Feature Service / ArcGIS Collector
+ Used for collection of various biological data
+ Collected information from biologists and project managers about how the data would be collected and utilized
+ Developed a set of tables and relationships to create the best collection system possible for the existing work flow
+ Feed into an automated system for generating maps
+ Trained biologists in its use, and pushed them from placing all data in the "Notes" field

### RapidMapper ArcGIS Server Geoprocessing Service
+ Used for generation of various project specific maps
+ Generated Soil, farmland, parcel, street, aerial, CNDDB, etc maps for a given project area.
+ Project area consisted of a simple parcel click on ArcGIS Online, or a drawn area, followed by "Printing" the map.
+ Saved 4-6 hours on average of Analyst time. This did result in some interesting discussions about how billable my time was.
+ Designed and created on my own initiative, when there was a lull in billable work to be done.

### Gas Pipeline Classification Model ArcGIS Desktop Python Model
+ Used for regulatory classification of pipelines
+ Utilized linear referencing and near analysis to determine if occupied structures were present in the surrounding area
+ Output a table based on that information, containing the pipeline segments and why they each were classified as such.
+ In this process I trained a coworker from model builder to Python use.

## Employer List
### Kern Council of Governments, Bakersfield CA
+ Kern County transportation funding clearinghouse
+ Basic GIS / IT tasks
+ Job title and length of employment
	- GIS Intern 
	- 2009 - 2010
### NAVFAC Southwest, NAWS China Lake
+ Navy military base, planning department
+ Basic GIS tasks and data collection, database management
+ Job title and length of employment
	- Community Planning Technician (Intern)
	- 2010 - 2011
### Epsilon System Solutions, Ridgecrest CA, Barstow CA
+ Military contractor
+ Various tasks, GIS, IT, and Development related
+ Job title and length of employment
	- GIS Developer I
	- 2011 - 2014
### QK Inc, Bakersfield CA
+ Professional services provider
+ Various tasks, GIS and IT related
+ Job title and length of employment
	- GIS Administrator
	- 2014 - 2018
### Azimuth Development, Bakersfield CA
+ Small business GIS consultant
+ Various GIS tasks for public and private agencies
+ Job title and length of employment
	- GIS Developer
	- 2018 - Present

## Presentations / Credentials
+ NWGIS 2018 - Presentation for a form logic driven deployment of Survey123
+ CalGIS 2016 - Presentation for clustering of features based on size with a machine learning system
+ Central Cal URISA - Presentation for RapidMapper
+ DOD secret level clearance (helpful for reestablishing if necessary)
+ CompTIA Net+, Sec+, A+ Certs (not renewed)

## Credits
+ [CSS Zen Garden](http://www.csszengarden.com)
	- Used for styling this resume "webpage"
	- Modified later for custom bullet points
	- Icons modified via [Inkscape (alternative to Adobe Illustrator)](https://inkscape.org)
+ [The Noun Project](https://thenounproject.com)
	- SVG icons for custom bullets
	- Royalty-free licenses acquired, cheap and effective
	- Used this in the past for SVGs to create custom thumbnails for AGOL / Collector / Survey123 apps, using Inkscape SVG editing
