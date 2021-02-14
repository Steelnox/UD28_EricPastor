# UD28_EricPastor_Ej1


#### 1. Description
```
Demo API REST creada con .NET COre 3.1 utilizando varias entidades ER y conectada con base de datos 
MS Sql Virtualizada sobre Fedora 32  y Virtualbox 6.1. Aplicación con fines educativos.
```

#### 2. Link a un demo con el proyecto desplegado: https://github.com/Steelnox/UD28_EricPastor/tree/main/UD27_Ej1

```
* Nombre de la App: [GIT] (https://github.com/)
```
#### 3. Lista con los pasos mínimos que se necesitan para clonar exitosamente el proyecto y echarlo a andar en local.

###### Install
```
IDE               Visual Studio 2019 Community Version
Core              C# 
Framework         NET Core 3.1
DataBase          Microsoft Sql Server 
Virtual           VirtualBox 6.1
SO                Fedora 32
```
###### packages Nuget 
```
Install-Package Microsoft.VisualStudio.Web.CodeGeneration.Design  -Version 3.1.4
Install-Package Microsoft.EntityFrameworkCore.Tools               -Version 3.1.8
Install-Package Microsoft.EntityFrameworkCore.SqlServer           -Version 3.1.8
Install-Package System.IdentityModel.Tokens.Jwt                   -Version 5.6.0
Install-Package Microsoft.AspNetCore.Authentication.JwtBearer     -Version 3.1.8
```
###### Cadena de Conexión Base de datos 
```
"AllowedHosts": "*",
    "ConnectionStrings": {
        "DatabaseConnection": "Server=192.168.0.29;Database=UD27_Ej1;User ID=Eric; Password=Root_1234"
    }
```
#### 4. URIs endpoints.
```
Piezas
GET       /api/Piezas
POST      /api/Piezas
GET       /api/Piezas/{id}
PUT       /api/Piezas/{id}
DELETE    /api/Piezas/{id}

Proveedores
GET       /api/Proveedores
POST      /api/Proveedores
GET       /api/Proveedores/{id}
PUT       /api/Proveedores/{id}
DELETE    /api/Proveedores/{id}

Suministras
GET       /api/Suministras
POST      /api/Suministras
GET       /api/Suministras/{id}
PUT       /api/Suministras/{id}
DELETE    /api/Suministras/{id}

Token
POST     /api/Token
```

#### 5. Screenshot imagen que indique cómo debe verse el proyecto.
![image](https://user-images.githubusercontent.com/11030691/107885900-1a2efb80-6efd-11eb-8fa3-783c9470ea0e.png)


# UD28_EricPastor_Ej2


#### 1. Description
```
Demo API REST creada con .NET COre 3.1 utilizando varias entidades ER y conectada con base de datos 
MS Sql Virtualizada sobre Fedora 32  y Virtualbox 6.1. Aplicación con fines educativos.
```

#### 2. Link a un demo con el proyecto desplegado: https://github.com/Steelnox/UD27_EricPastor/tree/main/UD27_Ej2

```
* Nombre de la App: [GIT] (https://github.com/)
```
#### 3. Lista con los pasos mínimos que se necesitan para clonar exitosamente el proyecto y echarlo a andar en local.

###### Install
```
IDE               Visual Studio 2019 Community Version
Core              C# 
Framework         NET Core 3.1
DataBase          Microsoft Sql Server 
Virtual           VirtualBox 6.1
SO                Fedora 32
```
###### packages Nuget 
```
Install-Package Microsoft.VisualStudio.Web.CodeGeneration.Design  -Version 3.1.4
Install-Package Microsoft.EntityFrameworkCore.Tools               -Version 3.1.8
Install-Package Microsoft.EntityFrameworkCore.SqlServer           -Version 3.1.8
Install-Package System.IdentityModel.Tokens.Jwt                   -Version 5.6.0
Install-Package Microsoft.AspNetCore.Authentication.JwtBearer     -Version 3.1.8
```
###### Cadena de Conexión Base de datos 
```
"AllowedHosts": "*",
    "ConnectionStrings": {
        "DatabaseConnection": "Server=192.168.0.29;Database=UD27_Ej2;User ID=Eric; Password=Root_1234"
    }
```
#### 4. URIs endpoints.
```
Cientificos
GET       /api/Cientificos
POST      /api/Cientificos
GET       /api/Cientificos/{id}
PUT       /api/Cientificos/{id}
DELETE    /api/Cientificos/{id}

Proyectos
GET       /api/Proyectos
POST      /api/Proyectos
GET       /api/Proyectos/{id}
PUT       /api/Proyectos/{id}
DELETE    /api/Proyectos/{id}

Asignados_a
GET       /api/Asignados_a
POST      /api/Asignados_a
GET       /api/Asignados_a/{id}
PUT       /api/Asignados_a/{id}
DELETE    /api/Asignados_a/{id}

Token
POST     /api/Token
```

#### 5. Screenshot imagen que indique cómo debe verse el proyecto.
![image](https://user-images.githubusercontent.com/11030691/107886414-ec978180-6eff-11eb-8987-5e49f687a43c.png)


# UD28_EricPastor_Ej3


#### 1. Description
```
Demo API REST creada con .NET COre 3.1 utilizando varias entidades ER y conectada con base de datos 
MS Sql Virtualizada sobre Fedora 32  y Virtualbox 6.1. Aplicación con fines educativos.
```

#### 2. Link a un demo con el proyecto desplegado: https://github.com/Steelnox/UD27_EricPastor/tree/main/UD27_Ej3

```
* Nombre de la App: [GIT] (https://github.com/)
```
#### 3. Lista con los pasos mínimos que se necesitan para clonar exitosamente el proyecto y echarlo a andar en local.

###### Install
```
IDE               Visual Studio 2019 Community Version
Core              C# 
Framework         NET Core 3.1
DataBase          Microsoft Sql Server 
Virtual           VirtualBox 6.1
SO                Fedora 32
```
###### packages Nuget 
```
Install-Package Microsoft.VisualStudio.Web.CodeGeneration.Design  -Version 3.1.4
Install-Package Microsoft.EntityFrameworkCore.Tools               -Version 3.1.8
Install-Package Microsoft.EntityFrameworkCore.SqlServer           -Version 3.1.8
Install-Package System.IdentityModel.Tokens.Jwt                   -Version 5.6.0
Install-Package Microsoft.AspNetCore.Authentication.JwtBearer     -Version 3.1.8
```
###### Cadena de Conexión Base de datos 
```
"AllowedHosts": "*",
    "ConnectionStrings": {
        "DatabaseConnection": "Server=192.168.0.29;Database=UD27_Ej3;User ID=Eric; Password=Root_1234"
    }
```
#### 4. URIs endpoints.
```
Cajeros
GET       /api/Cajeros
POST      /api/Cajeros
GET       /api/Cajeros/{id}
PUT       /api/Cajeros/{id}
DELETE    /api/Cajeros/{id}

Productos
GET       /api/Productos
POST      /api/Productos
GET       /api/Productos/{id}
PUT       /api/Productos/{id}
DELETE    /api/Productos/{id}

Maquinas_registradoras
GET       /api/Maquinas_registradoras
POST      /api/Maquinas_registradoras
GET       /api/Maquinas_registradoras/{id}
PUT       /api/Maquinas_registradoras/{id}
DELETE    /api/Maquinas_registradoras/{id}

Venta
GET       /api/Venta
POST      /api/Venta
GET       /api/Venta/{id}
PUT       /api/Venta/{id}
DELETE    /api/Venta/{id}

Token
POST     /api/Token
```

#### 5. Screenshot imagen que indique cómo debe verse el proyecto.
![image](https://user-images.githubusercontent.com/11030691/107886611-21580880-6f01-11eb-9957-44c6dd4468e5.png)

# UD28_EricPastor_Ej4


#### 1. Description
```
Demo API REST creada con .NET COre 3.1 utilizando varias entidades ER y conectada con base de datos 
MS Sql Virtualizada sobre Fedora 32  y Virtualbox 6.1. Aplicación con fines educativos.
```

#### 2. Link a un demo con el proyecto desplegado: https://github.com/Steelnox/UD27_EricPastor/tree/main/UD27_Ej4

```
* Nombre de la App: [GIT] (https://github.com/)
```
#### 3. Lista con los pasos mínimos que se necesitan para clonar exitosamente el proyecto y echarlo a andar en local.

###### Install
```
IDE               Visual Studio 2019 Community Version
Core              C# 
Framework         NET Core 3.1
DataBase          Microsoft Sql Server 
Virtual           VirtualBox 6.1
SO                Fedora 32
```
###### packages Nuget 
```
Install-Package Microsoft.VisualStudio.Web.CodeGeneration.Design  -Version 3.1.4
Install-Package Microsoft.EntityFrameworkCore.Tools               -Version 3.1.8
Install-Package Microsoft.EntityFrameworkCore.SqlServer           -Version 3.1.8
Install-Package System.IdentityModel.Tokens.Jwt                   -Version 5.6.0
Install-Package Microsoft.AspNetCore.Authentication.JwtBearer     -Version 3.1.8
```
###### Cadena de Conexión Base de datos 
```
"AllowedHosts": "*",
    "ConnectionStrings": {
        "DatabaseConnection": "Server=192.168.0.29;Database=UD27_Ej4;User ID=Eric; Password=Root_1234"
    }
```
#### 4. URIs endpoints.
```
Investigadores
GET       /api/Investigadores
POST      /api/Investigadores
GET       /api/Investigadores/{id}
PUT       /api/Investigadores/{id}
DELETE    /api/Investigadores/{id}

Facultades
GET       /api/Facultades
POST      /api/Facultades
GET       /api/Facultades/{id}
PUT       /api/Facultades/{id}
DELETE    /api/Facultades/{id}

Equipos
GET       /api/Equipos
POST      /api/Equipos
GET       /api/Equipos/{id}
PUT       /api/Equipos/{id}
DELETE    /api/Equipos/{id}

Reservas
GET       /api/Reservas
POST      /api/Reservas
GET       /api/Reservas/{id}
PUT       /api/Reservas/{id}
DELETE    /api/Reservas/{id}

Token
POST     /api/Token
```

#### 5. Screenshot imagen que indique cómo debe verse el proyecto.
![image](https://user-images.githubusercontent.com/11030691/107887000-6f6e0b80-6f03-11eb-8a91-8aaaa9e0db79.png)

