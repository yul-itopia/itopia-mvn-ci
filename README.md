# Updating Version Numbers 

## Maven CI Friendly Versions

### CI Friendly Maven Project Structure for v99x - Make tecsys-all a Parent BOM

| ![project-structure-tecsys-all-99](diagrams/ci-friendly-project-structure-tecsys-all-99.png "project-structure-tecsys-all-99") |
| --- |

### CI Friendly Maven Project Structure for v99x - New Parent BOM

| ![project-structure-99](diagrams/ci-friendly-project-structure-99.png "project-structure-99") |
| --- |

### CI Friendly Maven Project Structure for v2021.1+

| ![project-structure](diagrams/ci-friendly-project-structure.png "project-structure") |
| --- |


``` 
mvn clean package -Drevision=francois-2021.04-SNAPSHOT
```

``` 
mvn clean package -Drevision=francois-99x-SNAPSHOT
```