[![mi-web](https://github.com/rociopenciaroli/elementos/blob/master/svg-2.svg)](http://holarocio.com)
[![diseño-web](https://github.com/rociopenciaroli/elementos/blob/master/web-design.svg)](http://holarocio.com)
[![diseño-grafico](https://github.com/rociopenciaroli/elementos/blob/master/graphic-design.svg)](http://holarocio.com)
[![ux](https://github.com/rociopenciaroli/elementos/blob/master/ux.svg)](http://holarocio.com)
[![ui](https://github.com/rociopenciaroli/elementos/blob/master/ui.svg)](http://holarocio.com)


## ACORDEÓN EN ELEMENTOR, CERRADO POR DEFECTO

Encima del elemento __acordeón__, vas a colocar un código ```<script>``` 
que va a permitir que el acordeón se encuentre cerrado por defecto.

```js
<script> 
jQuery (documento) .ready (función ($) { 
var delay = 100; setTimeout (function () {
$ ('. elementor-tab-title'). removeClass ('elementor-active');
 $ ('. elementor-tab-content'). css ('display', 'none'); }, retraso);
}); 
</script>
```
