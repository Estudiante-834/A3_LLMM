# Enlace al despliegue

https://estudiante-834.github.io/A3_LLMM/  

# Recursos

Igual que la actividad anterior (AD 4 Landing Page), esta actividad usa las mismas propiedades y etiquetas vistas en clase o en videos y apuntes del profesor.

Se ha usado más propiedades relacionadas con grid como: 

- `display: grid` sirve para cambiar el display del contenedor al que se aplica a grid.
- `gap` para configurar el espaciado entre los elementos flex o grid.
- `grid-template-colum: valor_espaciado` determina como irán los elementos hijos dentro del contenedor grid. Las usada en la actividad separa a los elementos hijos en 2 columnas con el mismo espacio.

Se ha optado nuevamente por las propiedades lógicas y las media queries dentro de los selectores de CSS. Y por la nomenclatura en inglés.

```
padding-block: 10px; /* padding-height: 10px*/

h1 {
    @media (width > 1000px) {
        ...
    }
}
```

En cuanto al uso de `flex` no se ha utlizado ninguna propiedad no vista en clase. El `nav` es el único elemento que ha sido implementado utilizando `flex`. He optado por esta opción como menú responsive sobre el desplegable visto en clase, ya que el desplegable a pesar de ser responsive, no podía cerrarse a no ser que se pulsase sobre un enlace o al checkbox.

Para los breakpoints de las media queries he decidido utilizar medidas más comunes según mi criterio, para que las páginas no se estrechasen mucho a la hora de aumentar lo pixeles (1000 frente a las 1300 propuestas).




