# Curso de CSS Grid Básico :hash:

## ¿Qué es CSS Grid Layout?

Es un sistema de grilla, que tiene columnas y filas.

![](https://res.cloudinary.com/dngcu1bvt/image/upload/v1646335201/curso-css-grid/Sin_t%C3%ADtulo-1_vwedwk.svg)

Ejemplo de template

![](https://res.cloudinary.com/dngcu1bvt/image/upload/v1646335686/curso-css-grid/template-clase1_fqbb35.svg)

## Conceptos

Contenedor
```html
<!-- Soy un contenedor -->
    <div class="contenedor"> 
<!--  -->
        <div class="item item1">Item 1</div>
        <div class="item item2">Item 2</div>
    </div>
````
Item
```html
    <div class="contenedor"> 
        <!-- Soy un item -->
        <div class="item item1">Item 1</div>
        <!--  -->
        <div class="item item2">Item 2</div>
    </div>
```
- Container: Es un contenedor donde se almacenan los elementos
Item: Son los elementos que estan en el contenedor y se convierten en Grid Item pueden ser (botones,links,imagenes y videos)

- Lineas : Son los elementos que dividen las filas y columnas de una Grilla

- Celda: Es la unidad minima que tenemos en una Grilla, esta delimitada por 4 lineas. Ocupa 1 columna, 1 Fila

- Track: Los track son un grupo de celdas que estan en una misma fila o una misma columna

- Area: Pueden usar varias filas o varias columnas al mismo tiempo

## Propiedades de Contenedor
- display: grid
- grid-template-columns [Doc](https://developer.mozilla.org/es/docs/Web/CSS/grid-template-columns)
- grid-template-rows [Doc](https://developer.mozilla.org/es/docs/Web/CSS/grid-template-rows)
- grid-gap [Doc](https://developer.mozilla.org/es/docs/Web/CSS/gap)
- row-gap [Doc](https://developer.mozilla.org/en-US/docs/Web/CSS/row-gap)
- column-gap [Doc](https://developer.mozilla.org/es/docs/Web/CSS/column-gap)
- grid-auto-columns [Doc](https://developer.mozilla.org/es/docs/Web/CSS/grid-auto-columns)
- grid-auto-rows [Doc](https://developer.mozilla.org/es/docs/Web/CSS/grid-auto-rows)

## Propiedades de alineación 

### Propiedades para la alineación de los items (elementos):
- justify-items
- align-items
- place-items

### Propiedades para la alineación del container(El Contenedor):
- justify-content
- align-content
- place-content

### Propiedades para la alineación de un solo item individual
- justify-self
- align-self
- place-self

### Propiedades de ubicación

+ grid-column
    - grid-column-start
    - grid-column-end

+ grid-row
    -   grid-row-start
    -   grid-row-end 