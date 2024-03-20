# BaseDatos
Repositorio de trabajos de Base de Datos, ciclo 01/2024

# Apuntes
### 6/03/2024
Bases de datos centralizadas: SQL y NoSQL
Base de datos descentralizadas: Blockchain

En la primera, es más organizada porque lo llevamos en tablas en las bases de datos relacional, es más organizada pero más lenta. La base de datos no relacional (NoSQL) no ocupa tablas, por ejemplo, archivos JSON
Tarea: tipos de datos no relacional (ej. documental, grafos o nodos)
Tipos de datos no relacional: clave valor (los datos se organizan en datos en parejas de clave (id) y valor), un ejemplo puede ser los mapas; documentales (organizan los datos en documentos o archivos, usualmente en formato JSON); grafos (tienen nodos y aristas. Los nodos son un conjunto de información como JSON, y las aristas son conexiones entre ellos. Se ocupan para hacer conexiones). Referencia [aquí](https://ed.team/blog/tipos-de-bases-de-datos-nosql).

Las bases de datos descentralizadas no tienen un punto donde se almacena toda la información, en este caso blockchain, pero no se estudiará.

### 13/03/2024
Los apuntes de la clase de hoy se perdieron al quere subirlos a GitHub. El día de hoy estuvimos repasando lo de la clase pasada.
Tipo de relaciones: binaria, ternaria, reflexiva.
Restricciones: razón de cardinalidad (número de ocurrencias de una entidad que se relacionan con una ocurrencia de otra entidad) y razón de participación (forma de intervención de las ocurrencias de las entidades en una relación).
Los tipos de particiones pueden ser total/dependiente (cada entidad de un conjunto de entidades participa al menos en una relación del conjunto de relaciones de forma obligatoria) o parcial (sólo algunas entidades del conjunto de entidades participan en relaciones del conjunto de relaciones).
NO puede suceder que la cardinalidad mínima sea N ni que la cardinalidad máxima sea 0. Los valores posibles de la cardinalidad mínima son 0 y 1, los valores posibles de la cardinalidad máxima son 1 y N.

### 18/03/2024
La diferencia entre atributo multivaluado y compuesto es que compuesto es de varios tipos, multivaluado tiene varios del mismo tipo.