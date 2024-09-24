# CSS
-Es un lenguaje para dar estilos a la web (1996)

## SINTAXIS
-Como se puede establecer codigo CSS
```
h1{
 color: red;
}
```
- h1 -> selector
- color -> Propiedad
- red -> Valor

## CONCEPTOS IMPORTANTES CSS
- 4 conceptos importantes

/*Selector de etiqueta*/
```css
h1{
 color: red;
}
```
/*Selector de Desendencia*/
```css
nav ul li a{
    color: red;
}
```

## HERENCIA
-Elementos ancestros heredan algunas propiedades a sus decencientes
```html
<h1>CSS <span>Cascade Style Sheet</span></h1>
```
```css
p{
    color: peru;
}
a{
    color: inherit;
}
```

## CASACADA
-Significa que los estilos que llegan de ultimo lugar, sobreescriben a los de antes
-La especificidad vence a la cascada
```css
h1{
    color: red;
}
h1{
    color: blue;
}
```

## ESPECIFICIDAD
-Es un valor numerico que adquieren los selectores y se aplica cunado hay conflictos
```html
<!-- Selector de etiqueta(1)-->

<!-- Selector de clase(10)-->

 <!-- Slector de ID(100)-->

  <!-- INLINE (1000)-->

   <!-- IMPORNTANT (infinito)-->
```