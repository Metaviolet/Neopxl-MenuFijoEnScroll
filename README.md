Neopxl-MenuFijoEnScroll
=======================

Este repositorio aloja el Demo del Menú fijo al hacer scroll con jQuery.

El efecto del menú fijo al hacer scroll en este Demo es generado utilizando el Plugin de jQuery llamado jquery-scrolltofixed, desarrollado por Joseph Cava-Lynch.

La configuración por default para el uso del plugin es la siguiente:

```javascript
$(document).ready(function() {
  $('#mydiv').scrollToFixed();
});
```

Determinando opciones de límite en márgenes:

```javascript
$(document).ready(function() {
  $('#cart').scrollToFixed({ marginTop: 10, limit: $($('h2')[5]).offset().top });
});
```

