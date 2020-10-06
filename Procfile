#Heroku Procfile that specifies the commands that are executed by the app on startup
release: ./mvnw package
web: echo -e "\nHeroku Port: $PORT\n" && java -Dquarkus.http.port=$PORT -jar target/rest-quarkus-server-jpa-runner.jar
