# Polling
Polling app with Java jwt auth backend and React frontend

![Polling](./p.png)

# Set Up frontend
> Run the following commands from the root of react-frontend
```
npm i
```
```
npm run build
```
```
<move build file contents to spring-backend/target/classes/static directory>
```

# Set Up backend
> Run the following commands from the root of spring-backend
```
cd backend/src/main/resources
```
```
config application.yml by adding your DB username and password
```
```
mvn clean install
```
```
mvn spring-boot:run
```
```
<run jar on local host or deploy to AWS>
```