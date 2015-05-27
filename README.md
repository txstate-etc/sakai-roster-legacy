# sakai-roster-legacy
The Sakai integration provided by TurningPoint depends on the old roster which was removed in Sakai 10.

Trying to build the old roster for Sakai 10 is not really possible, so I've pulled out the methods used by the TurningPoint integration and put them here.

To include this code in your build, simply add this project to your sakai source folder and add roster_legacy as a module in Sakai's top level pom.xml.

`<module>roster_legacy</module`

NOTE: You may need to update versions in various pom.xml files in this project to match your current Sakai version.

This code comes from the Sakai project: https://github.com/sakaiproject/sakai
