## For Github Actions Tutorial

By TechWorld with Nana 
https://www.youtube.com/watch?v=R8_veQiYBjI




##### build the project

    ./gradlew build

##### build Docker image called java-app. Execute from root

    docker build -t java-app .
    
##### push image to repo 

    docker tag java-app demo-app:java-1.0
    
