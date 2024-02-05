# Desafío Inmobiliaria

Este proyecto consiste en el desarrollo de un sitio web para una inmobiliaria utilizando JavaScript.

## Descripción

El sitio web cuenta con las siguientes páginas:

- index.html: Página de inicio que muestra 3 propiedades en venta y 3 propiedades en alquiler.
- propiedades_venta.html: Página que muestra todas las propiedades en venta.
- propiedades_alquiler.html: Página que muestra todas las propiedades en alquiler.

La información de las propiedades se obtiene de dos arreglos de objetos, uno para las propiedades en venta y otro para las propiedades en alquiler.

Cada objeto de propiedad tiene la siguiente estructura:

```js
{
  nombre: '',
  src: '', 
  descripcion: '',
  ubicacion: '',
  habitaciones: 0,
  bano: 0,
  costo: 0,
  smoke: false, 
  pets: true
}
```

Se utilizan ciclos y plantillas creadas con innerHTML para renderizar las propiedades en las páginas.

Además se aplican condicionales para mostrar mensajes personalizados si se permite fumar o tener mascotas en cada propiedad.

## Requerimientos

- Páginas HTML para venta, alquiler e index
- Arreglos de objetos de propiedades
- Renderizado dinámico con ciclos e innerHTML 
- Condicionales para mostrar mensajes de mascotas y fumar
- Mostrar solo 3 propiedades en index.html

## Instalación

No requiere instalación, simplemente abrir el archivo index.html en el navegador.

## Contacto 

Comentarios y sugerencias son bienvenidos!
