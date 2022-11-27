# Gestor de biblioteca

### Este es un gestor de biblioteca simple el cual va a <b>añadir</b>/<b>modificar</b>/<b>eliminar</b> libros dela biblioteca 


```
erDiagram
    CAR ||--o{ NAMED-DRIVER : allows
    CAR {
        string allowedDriver FK "The license of the allowed driver"
        string registrationNumber
        string make
        string model
    }
    PERSON ||--o{ NAMED-DRIVER : is
    PERSON {
        string driversLicense PK "The license #"
        string firstName
        string lastName
        int age
    }
```