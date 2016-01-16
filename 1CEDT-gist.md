#### «1C: Enterprise Development Tools» - is a tool for the development of a new generation of business applications software systems "1C: Enterprise 8".

This format developed applications will fully comply with the current versions of the 1C: Enterprise 8.

##### The advantages of the new tool development are: 
* an integrated development environment (compliance with modern trends and requirements) 
* the rapid development of development tools
* the ability to expand the development tools

The DT laid fundamentally new architecture, which provides a large supply of various mechanisms for the implementation of the automation design and improve ease of development. 
The trial version features of this architecture are involved only in a small part. 

### At the moment, it is important to implement the same functionality as configurator, but the main purpose of DT in the possibility of creating a powerful new tools for developers.

DT is developed using an open platform [Eclipse](www.eclipse.org)

Due to this integration of technology, the tool combines the advantages of both development tools "1C: Enterprise" and the standard features of Eclipse.

### Scheme of «1C: Enterprise Development Tools»

#### DT offers a fundamentally different scheme of work.

* Firstly, the configuration is not stored in the information database and the file system
* This implies the use of a popular version control system (git, svn), which obviously is the second significant advantage

It should be understood that DT does not realize operation with version control system independently, and uses ready mechanisms Eclipse platform. 

Therefore, she can only use version control system, support (extension) which has in Eclipse.

Storing the edited configuration in the file system, rather than information-based, meaning that the editing of the configuration can be carried out even without the system "1C: Enterprise" is installed on your development machine. 

However, if necessary, start the application solution or debug some mechanism, the presence of the installed version of "1C: Enterprise" is a must.

### Main Enterprise Development Tools differences from conventional Configurator:
1. The Eclipse platform and the ability to write their own plug-ins for convenience
2. Cross-platform, ie, finally, you can work on a Mac)
3. The configuration is not stored in the information database and the file system. This implies the use of a popular version control system (git, svn)
4. Develop configuration can be used with different information bases and different versions of "1C: Enterprise"
5. At the same time, you can edit multiple configurations
6. Work into DT has some differences in terms of working with objects, and save the configuration results, as use the Eclipse platform
7. More convenient and fast development team

