# Proyecto de Clase Month (Mes)

## Descripción
Este proyecto demuestra la implementación de una clase `Month` en Java, mostrando el uso de diferentes colecciones de Java (`ArrayList` y `HashSet`) y conceptos de programación orientada a objetos.

## Características
- Clase personalizada `Month` con implementación adecuada de:
  - `equals()`
  - `hashCode()`
  - `toString()`
- Demostración de:
  - Operaciones con ArrayList
  - Uso de HashSet
  - Implementación de Iterator
  - Manipulación de colecciones

## Estructura del Código
Los componentes principales incluyen:
- `Month.java`: Contiene la implementación de la clase Month con un método main que demuestra varias operaciones

## Ejemplo de Uso
El programa demuestra:
1. Creación y población de un ArrayList con meses
2. Inserción de elementos en posiciones específicas
3. Conversión de ArrayList a HashSet
4. Prueba de manejo de duplicados en HashSet
5. Diferentes formas de iterar a través de colecciones:
   - Bucle for-each
   - Iterator

## Ejemplo de Salida 

Contenido del ArrayList:
Enero
Febrero
Marzo
Abril
Mayo
Junio
Julio
Agosto
Septiembre
Octubre
Noviembre
Diciembre
Contenido del HashSet usando bucle for-each:
[Todos los meses se mostrarán sin un orden particular]
Contenido del HashSet usando iterator:
[Todos los meses se mostrarán sin un orden particular]

## Detalles Técnicos
- Lenguaje: Java
- Paquete: tascaS103Ex1
- Colecciones utilizadas: 
  - `ArrayList`
  - `HashSet`
  - `Iterator`

## Notas
- El HashSet demuestra cómo se manejan automáticamente los duplicados (intentando agregar Enero dos veces)
- El proyecto muestra la implementación correcta de los métodos `equals()` y `hashCode()` para el funcionamiento correcto del HashSet
