help-animals
============

Animal shelter recordkeeping.

# Animal Shelter’s Best Friend (ASBF)

## Purpose:
ASBF is software to help animal shelters keep records important to them.  These records include animals and their health records and adoption histories, donations, volunteers, and official shelter documents among other things.
ASBF is open-source and free to any shelter that may want to use it.  It is my goal to have it used in many shelters.

## The Software: 
ASBF is written in Visual Basic using Visual Studio 2012.  It uses object-oriented programming techniques.  The database is MS Access 2007.  It runs on Windows computers.  It is currently just a single user system.   Each shelter has it on one laptop computer and a user must go to that computer to use it.   Obviously only one person can use it at a time and this is a limitation that needs overcoming.

## Contributors:
Currently, March of 2013, and throughout its development history there is, and has been, only one developer – myself.  Obviously, by making this project open source I hope that this will change and that you will want to contribute.
I started volunteering at an animal shelter and saw that their records were not in good shape.  And I saw where improvements could be made with some design and programming so that is what I started doing.  It has been a hobby that I’ve worked on, and off of, for about seven years now.
If you love animals and would like to help them and the people actively involved in their rescue, or if you just love software development, then you should consider becoming a contributor.

## Current Status – March 2013:
ASBF is being used in two animal shelters and the users are pleased with it.  It could be used in many shelters but currently there is no adequate delivery/installation process and there are no training mechanisms.   The shelters that it runs in are in my area and I can physically go to the shelter and install it and show folks how to use it.  However, since there is no download and install package if a shelter far removed from my physical location wanted to use it there is no way I could deliver it except to possibly mail a disk.  Also, I currently have no way to train users from a distance so this training needs to be developed.

## Contributor Guidelines:
### Desired features/improvements that you may be interested in working on:
* An install package deliverable from a website
* Inclusion of photos of the animals and their appearance on selected screens
* Program a query/report facility with drill-down capability, e. g., show me the dog adoptions for 2012
* Conversion from Access to SQL Server Express as SSE is distributable for free
* Possibly put in MS Azure to make it accessible from the cloud.  Security would be an issue because the database contains names and addresses and their donation history.
* Help with website development
* Code refactoring.

### Runtime requirements:
* The database, and other necessary files, reside in a folder ‘rescue’ that needs to be on the ‘C’ drive.  I can zip and email you this folder. 

### Coding Standards:
* The main code structure is behind each form with calls to modules for database access for inserts, deletions, and changes.  Classes exist for the primary objects (animals, people, donations, medicines, etc.)
* The name of the form appears at the top of each form.  This helps in debugging.
* I would like to keep the current look and feel for the foreseeable future.  It’s a little different, it uses list box navigation, but it’s easy to use and users like it.
* With your help we can develop some improved coding standards.

## Website:
I have a domain and hosting (www.animalsheltersbestfriend.org) and am in the process of developing a website.

