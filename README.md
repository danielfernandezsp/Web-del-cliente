# Web-del-cliente

## Descripción:

```bash
Esta es una web de recetas donde puedes encontrar una página de noticias, una tienda virtual, un listado 
de recetas y una página para contactar.
```

## Aclaraciones:

```bash
1- Esta web es solo un prototipo, casi no tiene contenido porque para esto necesito integrar tecnologías de
back-end
(BBDD, servlets, JSP, persistencia, etc).

2- Los enlaces a recetas no llevan a nada por lo dicho anteriormente.

3- Los artículos, noticias y productos sí funcionan ya que son enlaces externos.

4- El login y el registro no funcionan porque la página no tiene tecnología de back-end.

5- Aún no tengo creada la página de usuario autenticado.

He tratado de hacer este prototipo de forma que se muestre lo más real posible al producto final con los 
medios disponibles y las necesidades del cliente. Para la futura entrega tendrá todo lo que he dicho 
anteriormente que le falta a la web.
```

## Componentes:

```bash
Los componentes de bootstrap que he usado y merecen ser destacados son:
```
* Jumbotron: Tanto en el header como en el footer.

* Pagination: Las paginaciones las uso en aquellas páginas que tienen mucho contenido para que me muestren 
los datos al usuario de forma dosificada y no todo de golpe en una sola página.

* Navbar: Es la barra de navegación que está arriba en el header.

* Dropdown: En el anterior componente, tanto en recetas como en tienda utilizo dropdowns para que me muestre
un desplegable de las páginas.

* Modal: Los modales los utilizo en dos partes, en el login y el registro de usuarios. Lo veo más útil
que crearme otras dos páginas cuando así queda más visual y es más cómodo con menos código.

* List-group: En la página de inicio. En la zona del aside uso dos de estos componentes para mostrar
enlaces de noticias y recetas destacadas.

## Descripción de las páginas:

```bash
He intentado que cada página tenga una distribución de contenidos diferente sin modificar la estética 
general de la web. Esta consta de una página de inicio, noticias, contactos y subpáginas de recetas y tienda.
Aquí explico mas detalladamente que tiene cada página.
```
* Inicio: Se divide en dos partes que son aside y section. En aside tengo unos enlaces a noticias y recetas
destacadas y en section tengo 4 articles de recetas destacadas. Estos articles tienen una foto del plato,
nombre de la receta, texto descriptivo y un enlace a dicha receta.

* Noticias: Son filas con dos aticles por fila. En cada article de noticias tengo una foto, un título, la 
fecha de creación, texto de la noticia y un enlace a la noticia (una web externa). Consta también de una 
paginación para cuando hay muchas noticias dosificarlas y no mostrarlas de golpe.

* Contactos: Son dos filas. En la primera hay tres articles con el número de teléfono, web secundaria y 
correo del cliente. En la segunda fila un formulario de contacto.

* Tienda:
  - Carne: Es una página donde aparecen artículos relacionados con carnes.
  - Pescado: Es una página donde aparecen artículos relacionados con pescados.
  - Repostería: Es una página donde aparecen artículos relacionados con repostería.
  - Especias: Es una página donde aparecen artículos relacionados con especias.
  - Limpieza: Es una página donde aparecen artículos relacionados con limpieza.
  - Pasta: Es una página donde aparecen artículos relacionados con pasta.
  - Verdura: Es una página donde aparecen artículos relacionados con verdura.
  
* Recetas:
  - Especiales navidad: Es una página donde aparecen recetas navideñas.
  - Recetas kids: Es una página donde aparecen recetas para niños.
  - Carnes: Es una página donde aparecen recetas de carne.
  - Pescado: Es una página donde aparecen recetas de pescados.
  - Pasta: Es una página donde aparecen recetas de pasta.
  - Vegetariana: Es una página donde aparecen recetas vegetarianas.
  - Postres: Es una página donde aparecen recetas de postres.

## Enlace de la web:

[Las recetas de María José](https://danielfernandezsanchezpalencia.000webhostapp.com/dise%C3%B1oDIW/Web%20del%20cliente/)
