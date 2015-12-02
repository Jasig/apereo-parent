# apereo-parent [![Maven Central](https://maven-badges.herokuapp.com/maven-central/org.jasig.parent/jasig-parent/badge.svg?style=flat)]
Apereo parent pom for Apereo Maven projects.  

# Revisions

## Version 41
Updates the license headers to Apereo and includes the reporting plug-ins again.

## Version 40
Starting with version 40, the license plug-in changed from
```
<groupId>com.mycila.maven-license-plugin</groupId>
<artifactId>maven-license-plugin</artifactId>
```
to
```
<groupId>com.mycila</groupId>
<artifactId>license-maven-plugin</artifactId>
```
You will need to update your pom for this.