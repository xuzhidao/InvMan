# InvMan
Simple JavaFX inventory management application

## INSTALL

### REQUIREMENTS

- Maven
- Java 1.8 (not tested in older versions yet)

### DOWNLOAD, COMPILE AND RUN (using Maven)

```
git clone [this repo URL]
cd [cloned-dir]
mvn compile
mvn exec:java
```
### LOGIN

The credentials for login are defined in users table in the SQL file placed in the root directory.
By default use following:

```
username: b
pass: b
```

## CHANGELOG

### 1.2.1 

- Added Hibernate ORM


## ROADMAP

### PHASE 1

- [x] Basic dashboard
- [x] Product management
- [x] Product group management
- [x] Orders management
- [x] Stock list

### PHASE 2

- [ ] Unit tests
- [x] Use Hibernate ORM
- [ ] Speed improvement
- [ ] ???
