
# Práctica 1:'Fotocasa Web-scraping'

- Descripción.

   Extrae los precios y características de los diferentes inmuebles en venta de la página web https://www.fotocasa.es/es/.

- Contexto.

   La materia de datos recogidos hace referencia a las características de los inmuebles a la venta en la provincia de Lugo.
   
- Contenido.

   Se recogen todos los datos de los anuncios disponibles hasta la fecha. Cuando un inmueble se vende su anuncio se elimina, por lo que   no tiene cabida buscar en un rango de fechas.
   Se incluyen los siguientes campos:
   
    -Title: título del anuncio
    
    -Description: descripción del anuncio
   
    -Price: precio en euros del inmueble
    
    -hab: número de habitaciones
    
    -m2: tamaño en m2
    
    -Timeago: hace cuánto fue publicado 
    
    -Phone: teléfono de contacto
    
    -url: página del anuncio
    
    -imgurl: la url de imagen principal
    
    Finalmente se genera un csv con estos datos y una carpeta con la imágen principal de cada inmueble.
    
- Inspiración.

   La búsqueda de piso es siempre bastante tediosa. Este web scraping permite tener la información más relevante de manera más sencilla y rápida. Aunque se ha partido de la búsqueda de los inmuebles en Lugo, se puede seleccionar otra ciudad y posteriormente copiar la url en el código antes de ejecutarlo.

   
