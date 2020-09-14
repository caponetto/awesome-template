
# awesome-template
This repository contains a basic Maven archetype structure for KIE KJAR projects.

It also includes some example assets in the [src/main/resources/archetype-resources](https://github.com/caponetto/awesome-template/tree/master/src/main/resources/archetype-resources) folder, such as:

 - [MyDataObjectFromTemplate.java](https://github.com/caponetto/awesome-template/blob/master/src/main/resources/archetype-resources/src/main/java/com/MyDataObjectFromTemplate.java)
 - [MyDecisionFromTemplate.dmn](https://github.com/caponetto/awesome-template/blob/master/src/main/resources/archetype-resources/src/main/resources/MyDecisionFromTemplate.dmn)
 - [MyProcessFromTemplate.bpmn](https://github.com/caponetto/awesome-template/blob/master/src/main/resources/archetype-resources/src/main/resources/MyProcessFromTemplate.bpmn)
 - [MyRuleFromTemplate.drl](https://github.com/caponetto/awesome-template/blob/master/src/main/resources/archetype-resources/src/main/resources/MyRuleFromTemplate.drl)

Refer to [this](https://github.com/kiegroup/droolsjbpm-knowledge/tree/master/kie-archetypes/kie-kjar-archetype) repository if you want to create an empty KIE KJAR project.

### Basic customization
1. Clone this repostiory.
2. Replace the values for `groupId`, `artifactId` and `version` in the [pom.xml](https://github.com/caponetto/awesome-template/blob/master/pom.xml) file according to your needs.
3. Add your own assets in [src/main/resources/archetype-resources](https://github.com/caponetto/awesome-template/tree/master/src/main/resources/archetype-resources) folder (and remove the example assets).
4. Install the archetype on your local maven repository with `mvn clean install`.

### Related blog post
[Maven archetype support in Business Central](https://medium.com/kie-foundation/maven-archetype-support-in-business-central-b5fdf5e98556)
 
