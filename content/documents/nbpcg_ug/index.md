title=NBPCG User Guide
date=2022-05-21
type=document
tags=NBPCG,NetBeans_Plugins
status=published
nextpage=project
sectionlistname=nbpcg_ug
~~~~~~

## Introduction ##

The Netbeans Platform Application Code generator is a Netbeans plug-in which creates
a set of artifacts to speed up creation of a NetBeans Platform Application.  These artifacts can
include:

* Database creation scripts
* Other utility scripts
* Entity classes and their associated Entity Managers
* Node class for all entities
* Explorer Views for all entities
* Editors for all entities

## The NBPCG script ##

The generation of these artifacts is controlled by a single NBPCG script which describes the necessary
build details, entities details and also the node relationships.  The NBPCG script is an XML document.
A template is available - using the New... entry, the template can be selected 
from the other category with file type NBPCG Definition file

![script template selection](resources/newfile.jpg)

For full details of the content and syntax of the script file can be found [here](script.html).

## Feedback/Support ##

The author would be interested in any feedback on this project
from users of the plug-in.  Issues (bugs or possible
enhancements) can be logged using the project
[issue tracker](https://github.com/The-Retired-Programmer/nbpcg/issues)