# EmployeeWise

## Features

- Add, delete, and update employees effortlessly.
- Pagination and sorting features for streamlined management.
- Obtain nth level manager for each employee seamlessly.
- Efficient exception handling for smooth operation.
- Email notification capability integrated.

## Configurations

Check following configurations Change DB details accordingly

```bash
#DB related
spring.data.mongodb.host=localhost
spring.data.mongodb.port=27017
spring.data.mongodb.database=demo

#Email related
spring.mail.host=smtp.gmail.com
spring.mail.port=587
spring.mail.username={email-id}
spring.mail.password={password}
spring.mail.properties.mail.smtp.auth=true
spring.mail.properties.mail.smtp.starttls.enable=true
```

## Run Locally

Clone the project

```bash
  git clone https://link-to-project
```

Go to the project directory

```bash
  cd my-project
```

Install dependencies

```bash
  mvn clean install
```

Start the server

```bash
  mvn spring-boot:run
```
