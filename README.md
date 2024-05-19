Búsqueda del camino más corto entre dos vértices en un grafo Este proyecto se enfoca en implementar una estructura de datos de grafo en Java con el objetivo de encontrar el camino más corto entre dos vértices dados. A continuación, se presenta una breve guía sobre cómo utilizar y compilar el programa, así como una descripción de la estructura del código.

Versión 1.0

Uso del programa Limpiar mvn clean

Compilar mvn compile

Generar Javadoc mvn javadoc:javadoc

Ejecutar pruebas mvn test

Estructura del código El proyecto consta de dos clases principales:

Graph.java: Ubicada en el paquete main, esta clase contiene el método que realiza la simulación y proporciona funcionalidades para manipular el grafo, como agregar vértices, arcos, obtener vértices adyacentes y comprobar la existencia de un vértice.

GraphTest.java: En el paquete test, esta clase comprueba que el método onePath(V v1, V v2) encuentra un camino entre los vértices cuando existe.

Diagrama UML Se proporciona un diagrama de clases (diagramadeclases.png) que ilustra la estructura del código.

Licencia Copyright [2024] [Alejandra Vázquez Corbella y Manuel Enrique Tabasco García] Este proyecto esta licenciado bajo la Licencia Apache 2.0. Consulte el archivo LICENSE para obtener más detalles.
