### Este documento XML almacena datos sobre producciones audiovisuales y espectáculos. Su esquema XML debe validar los siguientes aspectos:

- Las producciones se dividen en proyectos
    - Cada proyecto debe contar con cuatro atributos:
        - Nombre (debe ser único, debe eliminarse cualquier espacio o salto de linea y no puede tener mas de 40 caracteres de longitud)
        - Productora
        - Fecha (tipo date)
        - ID que debe estar conformado por las letras PX y cuatro dígitos (los códigos no deben poder repetirse).
    - Los proyectos deben tener un tipo, que puede ser solamente: largometraje, cortometraje o festival.
    - Cada proyecto debe tener uno o mas seguros
    - Cada proyecto puede tener cero o mas patrocinadores
    - Cada proyecto debe tener una o mas localizaciones(lugares donde se graba/realiza)
    - Dentro de cada proyecto figura un apartado de personal en el cual figuran empleados con los siguientes datos:
        - Nombre completo (atributo)
        - Departamento
        - Empresa
        - Puesto