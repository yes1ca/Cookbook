# COMU
Este proyecto es parte del proyecto final, que tiene como objetivo demostrar las capacidades de trabajar con la estructura básica, el uso de atributos, etiquetas, adicionar imágenes, etc.
Para plasmar parte del conocimiento adquirido, decidí centrarme en crear un archivo HTML que contenga recetas, el concepto es similar al de un blog, donde la página no solo sea para leer
información, sino también para contribuir con recetas nuevas.

## Proceso de creación
En un inicio no tenía bien definida mi idea, sabía que los sitios de recetas suelen ser extensos y eso es lo que buscaba, pues de esa forma podría incluir una barra de navegación y de
verdad se viera reflejado cómo es que se movía hacia abajo dentro de la misma página, supongo que eso fue lo que me motivo a pensar en recetas.
- Comencé con la plantilla del código base de HTML, creé un repositorio y realicé el primer commit y subí los cambios con un git push origin master a mi repositorio de GitHub.
- Una vez que estaba segura que mi primer commit estaba reflejado dentro de mi repositorio, comencé a trabajar en la estructura base que tendría mi archivo, sin preocuparme mucho aún por el
contenido, a medida que avanzaba iba guardando mi archivo y asegurándome que se viera como esperaba, el contenido base que establecí seccionado fue la barra de navegación, Historia, Comidas,
Postres, Bebidas, Únete, Redes Sociales y Footer. Hice un segundo commit.
- Para el tercer commit, las modificaciones fueron muy breves pero quería asegurarme que no hubiera ningún problema con los links de las redes sociales y redirigieran como esperado, al ser
una página fictivcia, no cuento con RRSS por lo que me limité a colocar solo las URL de las principales redes sociales que podrían ser interesantes para una página así, Facebook, Twitter,
Instagram y Pinterest, incluí también el inicio de sesión, que en el ideal, es lo que usarían los usuarios para poder comenzar a colaborar, así mismo, incluí el footer y comencé a redactar
la Historia, así me di cuenta que el nombre de la página no hacía exatamente match, por lo que de COCO paso a renombrarse como COMU.
- Siguiendo con el cuarto commit, comencé a adicionar una receta de cada sección, esto es una de comida, una de postre y una de bebida, aquí fue donde más pude aprovechar el uso de títulos y
subtítulos, aproveché el usar listas desordenadas para los ingredientes y pensaba usar listas ordenadas para la preparación, sin embargo, a mi parecer se veía un poco simple, así que lo que
hice fue usar un tamaño de letra h5 para el número de paso y un párrafo para la explicación de ese paso.
- Para el quinto commit, me dediqué solo a insertar imágenes de las recetas, pensaba solo incluir imagenes para que pudiera visualizarse el platillo, sin embargo, me pareció en algun punto
que lucía muy plano, por lo que en los pasos donde se requería de una referencia visual, ya sea para ver la consistencia o entender cómo hacer la acción, incluí imágenes, todas ellas las
obtuve de internet, a excepción del logo, para crearlo busqué una foto en internet que hiciera referencia a muchos platillo del mundo y sobre esa adicioné el nombre del sitio, de esa forma
me parece que da un mejor aspecto.
- El último commit fue porque noté un error que dejé pasar desde el inicio, mi menú no redireccionaba, ahí caí en cuenta que me hacía falta la referencia, en mi caso como no era una URL la que
necesitaba, sino el id dentro de la misma página, bastó con adicionar en las comillas del href #NombreDelIDQueDiALaSección (en mi caso, p.e. <a href="#Historia"...)

## Código
Este es el código que estuve trabajando para el proyecto final.
![Vista previa](https://i.postimg.cc/bYDXv33g/final-project.png)
