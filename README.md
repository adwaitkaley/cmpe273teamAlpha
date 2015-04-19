# cmpe273teamAlpha
How to Run

1. Navigate to Project root in Terminal
2. gradle bootRun
3. access url "localhost/8080/getalbums"


Reading and Writing Images from MongoDB

1. Navigate to application.properties and set IMAGE_DIRECTORY to a path in your system
2. Start MongoDB Server (type mongod in shell)
3. Access url "localhost/8080/getalbums"
4. Authenticate into the application using facebook credentials
5. Access url "localhost/{album_id}/photos"
6. Check mongodb and the file directory for the Images