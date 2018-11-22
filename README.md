# maven-custom-archetype
this project demonstrate how to use custom archetype  to generate new project or module

### install

1. clone project
        
        git clone git@github.com:alonWang/maven-custom-archetype.git

2. cd into root directory and enter following command

        mvn install
        mvn archetype:crawl

### usage

1. use maven 

         mvn archetype:generate -DarchetypeGroupId=com.github.alonwang -DarchetypeArtifactId=my-archetype -DarchetypeVersio n=0.0.1-SNAPSHOT -DgroupId=com.github.alonwang -DartifactId=archetype-demo -DpascalApplicationName=ApplicationName -Dmessage=hello

2. use idea

