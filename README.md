# Proyecto React

En grupo o de manera individual, el objetivo es hacer una app que cumpla las siguientes consignas:
- Debe estar hecha en React y estilada con Styled-Components
- Debe usar paginación con react-router
- Debe comunicarse con una api y mostrar los resultados 
- Debe permitirle al usuario buscar resultados o filtrarlos

## Ejemplos

### E-commerce con buscador 

Usando la API de MercadoLibre, permitirle al usuario buscar productos. 
Se deben desplegar en una lista, y al hacer clic en una tarjeta debemos ir a una pagina nueva en donde se vea mas información del producto

Ejemplo posible: https://e-store-malerey.now.sh/

Endpoints: 
- Busqueda https://api.mercadolibre.com/sites/MLA/search?q=' + query 
- Producto: https://api.mercadolibre.com/items/' + id 
- Descripcion de un producto https://api.mercadolibre.com/items/' + id + '/description'

### Buscador de noticias 

Usando la API NewsAPI, mostrar las noticias principales de Argentina 
Debe contener un menu en donde podamos filtrar las noticias por fuente 
Debe contener un buscador para buscar noticias por un tema en espacifico

Ejemplo posible: https://news.malerey1.now.sh/

Endpoints: 
- Todas las noticias: https://newsapi.org/v2/top-headlines?apiKey= + apiKey + &country=ar
- Un diario en particular: https://newsapi.org/v2/top-headlines?apiKey= + apiKey + &sources= + diario
- Buscar por tema: https://newsapi.org/v2/everything?apiKey= + apiKey + &language=es&q= + busqueda

### Web de viajes

Usando la API de Amadeus, hacer una web donde el usuario pueda buscar vuelos por fecha, origen y destino. Al buscar se debe redireccionar a otra pagina donde se muestren los resultados. 
Dada la dificultad de la API y el form, solo se pide que se muestren los resultados de vuelos en forma de tarjetas 

Ejemplo posible: https://screeching-field.surge.sh/ (no es necesario hacerlo tan complejo)

Guia para la API: https://github.com/Ada-IT/bootcamp-frontend/tree/master/trabajos-practicos/tp-final

### Alternativa propia

Por grupos o de manera individual pueden proponer una idea para una web. Mientras se cumplan los requisitos principales, es posible hacerla. Buscamos juntas una API que sirva a los propósitos y un diseño a emular. Elijan algo que las motive, porque eso siempre ayuda a trabajar mejor :) 






