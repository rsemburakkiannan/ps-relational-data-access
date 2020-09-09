# ps-relational-data-access

### Context
This sample app is created to illustrate simple non-web Spring Boot app with logging, profile(for environments like dev, test, uat, prod), Spring JDBC with H2 connect.

In this code, we created only `dev` and `prod` profiles. Default or `dev` profile connects to H2 database.

### How to setup and run the code locally
```
git clone git clone https://github.com/rsemburakkiannan/ps-relational-data-access.git
cd ps-relational-data-access

#To Run the app (Default profile)
gradlew bootRun 

#To Run the App (Using Dev profile)
gradlew bootRun  --args='--spring.profiles.active=dev'

#To Run the App (Using prod profile)
gradlew bootRun  --args='--spring.profiles.active=prod'
```

