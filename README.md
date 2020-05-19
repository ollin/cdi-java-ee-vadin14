# Vaadin 14 Flow and CDI on openliberty 

This project is an attempt to solve the exceptions when using vaadin 14 together with openliberty 20.0.0.4 

Run application using
```
mvn clean package liberty:run
```

Use the dev mode if you want hot reload
```
mvn liberty:dev
```

Open [http://localhost:8080/dada](http://localhost:8080/dada) in browser.

If you want to run your app locally in the production mode, run using
```
mvn clean package liberty:run -Pproduction
```

The application is deployed on the [openliberty 20.0.0.4](https://openliberty.io/) server.
