# Apple iOS and OS X Management

I had the pleasure to present at [FrOSCon 2016](http://froscon.org) on iOS and OS X management and introduce the workflows used at the University of Oxford's Mac team.

### Abstract (German)

Im Juli 2015 haben Apple und IBM eine Allianz angekündigt, um den Bereich der Enterprise Mobility zu revolutionieren. Durch die Kombination der IBM Professional Services mit den Produkten von Apple steht Unternehmen nun ein global verfügbares Serviceportfolio zur Unterstützung von "mobile first" Strategien zur Verfügung.

Immer mehr Mitarbeiter fordern von ihren IT-Abteilungen, MacBooks, iPads und iPhones auch im beruflichen Kontext einsetzen zu dürfen. Der IT-Betrieb beschafft daraufhin oft diese Geräte, konfiguriert sie initial und übergibt sie mit guter Hoffnung in die Obhut der Anwender. Nachdem Angriffe und Exploits auch bei den populären Apple-Systemen angekommen sind, suchen Systemadministratoren nach belast- und skalierbaren Managementlösungen auch für diese Plattform, die sie beim Deployment, Konfigurations- und Patchmanagement unterstützen.

Apple stellt viele Tools und Frameworks zum Management beider Betriebssysteme zur Verfügung. Allerdings skalieren die kaum und sind eher als Referenzimplemntierung anzusehen. Daher hat sich ein umfangreiches, aber auch unübersichtliches Ökosystem entwickelt. Viele kommerzielle Angebote versprechen umfassende Managementlösungen. Pfiffige Entwickler stellen zuverlässige Alternativen als Open Source zur Verfügung, etwa Munki zur Softwareverteilung, Osquery zur Analyse und Monitoring, oder SAL zum Inventory und Reporting.

Apple verwendet viele Marketing-Akronyme, um Sachverhalte zu benennen, die dem Unix-Admin unter anderem Namen bekannt sind. So steht Beispielsweise BSDP für Boot Service Discovery Protocol, was in Wirklichkeit nicht mehr als DHCP ist. Der Vortrag übersetzt Apples Marketing-Jargon in gängige Technologien und erklärt, wieso sich betroffene Admins eben keine Mac Minis als Server in ihr Rechenzentrum stellen müssen. Darüber hinaus werden für gängige Deployment-Techniken und Management-Strategien die verfügbaren Tools diskutiert. Hierbei fließen die Erkenntnisse aus über einem Jahrzehnt Apple-Management an der University of Oxford in die Bewertung ein.

### Resources

 * [slides (pdf)](https://github.com/mjung/publications/raw/master/2016-08-20_FrOSCon_Mac_and_iOS_Management/2016-08-20_FrOSCon-Apple_OS_X_und_iOS_management.pdf)

### Links

#### Apple Tools & Documentation

 * [Apple OS X Deployment Reference](http://help.apple.com/deployment/osx/)
 * [Apple iOS Deployment Reference](http://help.apple.com/deployment/ios/)
 * [Apple Deployment Programmes Help](https://help.apple.com/deployment/programs/)
 * [Apple Developer Program](https://developer.apple.com/)
 * [Apple OS X Server](http://www.apple.com/de/osx/server/)
 * [Apple Remote Desktop](http://www.apple.com/de/remotedesktop/)

#### MDM & commercial tools

 * [coMmanDMent](https://github.com/jessepeterson/commandment)
 * [microMDM](https://micromdm.io/) 
 * [mdmvendorsign](https://github.com/grinich/mdmvendorsign) (create CSR for Apple's MDM push service)
 * [Enterprise iOS - MDM comparison](http://enterpriseios.com/)
 * [Bushel](http://www.bushel.com)
 * [Filewave](https://www.filewave.com/)
 * [JAMF Casper Suite](http://www.jamfsoftware.com/products/casper-suite/)
 * [LANrev (aka Absolute Manage)](https://heatsoftware.com/lanrev/)
 * [Microsoft System Center Configuration Manager (SSCM)](https://www.microsoft.com/en/server-cloud/products/system-center-configuration-manager/)

#### NetBoot 

 * [Apple Open Source BSDP Documentation](http://www.opensource.apple.com/source/bootp/bootp-170/Documentation/BSDP.doc)
 * [Apple NetBooting using OS X 10.11](https://support.apple.com/en-gb/HT205054)
 * [BSDPy - Python implementation of BSDP](https://bitbucket.org/bruienne/bsdpy)
 * [Justin Elliot: NetBoot Fundamentals and Customizations](https://www.youtube.com/watch?v=yKS2moLySi0&feature=youtu.be)

#### NetBoot Image Creation
 
 * [OS X Server (Mountain Lion): Creating images for NetInstall, NetRestore, and NetBoot](https://support.apple.com/en-gb/HT202652)
 * [Create a NetBoot, NetInstall or NetRestore image that supports multiple Mac models](https://support.apple.com/en-gb/HT202061)
  * [Hack the OS X image to use a RAMDisk instead](https://www.afp548.com/2011/02/01/serving-diskless-netboot-for-your-macs-without-os-x-server/)
 * [Casper NetInstall Image Creator](https://github.com/jamf/CasperNetInstallCreator)
 * [AutoCasperNBI](https://github.com/macmule/AutoCasperNBI/)
 * [AutoNBI.py](https://bitbucket.org/bruienne/autonbi)
 
#### Imaging Tools

 * [Casper Imaging](http://www.jamfsoftware.com/products/casper-suite/)
 * [DeployStudio](http://www.deploystudio.com/)
 * [Imagr](https://github.com/grahamgilbert/imagr)
 * [FileWave Imaging](https://www.filewave.com/products/imaging/)
 * [LANrev (aka Absolute Manage)](https://heatsoftware.com/lanrev/)

#### Image Creation
 
 * [Apple Disk Utility](https://support.apple.com/en-gb/HT202841)
 * [AutoDMG](https://github.com/MagerValp/AutoDMG)
 * [Casper Composer](http://www.jamfsoftware.com/products/casper-suite/)
 * [NBICreator](https://github.com/NBICreator/NBICreator)

#### Inventory & More

 * [Sal - Open Source](https://github.com/salsoftware/sal)
 * [SAL+](http://salsoftware.com/)
 * see commercial apps above

#### Munki & Autopkg

 * [Munki](https://github.com/munki/munki/wiki)
 * [AutoPkg](https://github.com/autopkg/autopkg)
 * [Recipe Robot](https://github.com/homebysix/recipe-robot)
 * [List of a lot of Munki related tools](https://github.com/timsutton/python-macadmin-tools#munki)
 
#### Apple Software Updates

 * [Reposado](https://github.com/wdas/reposado)
 * [Margarita](https://github.com/jessepeterson/margarita)
 * [createOSXinstallPkg](https://github.com/munki/createOSXinstallPkg)
 
#### Authentication and Authorisation

 * Apple Enterprise Connect
 * [NoMAD](https://gitlab.com/Mactroll/NoMAD/) 
 * [KerbMinder](https://github.com/pmbuko/KerbMinder)

#### Security

 * [Cauliflower Vest](https://github.com/google/cauliflowervest)
 * [Crypt](https://github.com/grahamgilbert/Crypt)
 * [osquery](https://osquery.io/)
 * [Plan B](https://github.com/google/macops-planb)
 * [Santa](https://github.com/google/santa)
 
#### Community

 * [Macadmins @ Slack](http://macadmins.org/)
 * [MacSysAdmin.se conference documentation](http://documentation.macsysadmin.se/Documentation2015/Documentation.php)
 
### Credits

I would like to thank [Aaron](https://github.com/oucsaw/), [Ben](https://github.com/fuzzylogiq/), [Chris](https://github.com/cdbeard), and [Gary](https://github.com/AltMeta) for their hard work to make all this happen.
