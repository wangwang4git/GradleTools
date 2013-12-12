GradleTools
===========

Gradle Tools...

Tool One
===
1. Copy From https://github.com/townsfolk/gradle-templates
2. Like `Maven Archetype`

  Useage:
  
  Add In Your `Build.gradle`

  > apply from: https://raw.github.com/wangwang4git/GradleTools/master/archetype/archetype.groovy

  Use `gradle tasks` look tasks, and you will know.

Tool Two
===
1. Look From http://www.gradle.org/docs/current/userguide/publishing_maven.html
2. `Gradle` java project generate `Maven` java project, and push the result to `Github mvn-repo`(like maven repository), can see http://blog.rueedlinger.ch/2012/09/use-github-as-maven-remote-repository/

  Useage:
  
  Add In Your `Build.gradle`

  > apply from: https://raw.github.com/wangwang4git/GradleTools/master/gradle-mvn-push/gradle-mvn-push-java.gradle

  Add In Your `gradle.properties`
  
  > POM\_GROUP\_ID
  
  > POM\_ARTIFACT\_ID
  
  > POM\_PACKAGING
  
  > POM\_VERSION
  
  > POM\_NAME
  
  > POM\_DESCRIPTION
  
  > POM\_URL

  Use `gradle publish` look path `./build/repo`, and `git push` to your `github`.