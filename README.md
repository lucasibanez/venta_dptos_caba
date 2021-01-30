# Creacion de modelos de regresion

Como parte del desafio del curso de Data Science de Digital, el objetivo final fue la creación de un modelo de aprendizaje supervisado.
Para lograr esto, se realizaron diferentes acciones:

• Comprensión de los datos usando la documentación que nos proporciona la web (Documentación en anexo);\
• Preparación, estructuración y limpieza de los datos;\
• Analisis estadístico explotario;\
• Uso de otros datasets para mejorar la precision de nuestros modelos.

El dataset que fue utilizado corresponde a Properati, un sitio de búsqueda de inmuebles, que contiene diferentes datos sobre las caractericas de cada inmueble junto con su precio, sea para venta, alquiler o alquiler temporal.
 
Los mismos se encuentran en el siguiente: https://www.properati.com.ar/data/

### Documentacion

• type - Tipo de aviso (Propiedad, Desarrollo/Proyecto).\
• country - País en el que está publicado el aviso (Argentina, Uruguay, Colombia, Ecuador, Perú)\
• id - Identificador del aviso. No es único: si el aviso es actualizado por la inmobiliaria (nueva versión del aviso) se crea un nuevo registro con la misma id pero distintas fechas: de alta y de baja.\
• start_date - Fecha de alta del aviso.\
• end_date - Fecha de baja del aviso.\
• created_on - Fecha de alta de la primera versión del aviso.\
• place - Campos referidos a la ubicación de la propiedad o del desarrollo.\
• lat - Latitud.\
• lon - Longitud.\
• l1 - Nivel administrativo 1: país.\
• l2 - Nivel administrativo 2: usualmente provincia.\
• l3 - Nivel administrativo 3: usualmente ciudad.\
• l4 - Nivel administrativo 4: usualmente barrio.\
• property - Campos relativos a la propiedad (vacío si el aviso es de un desarrollo/proyecto).\
• operation - Tipo de operación (Venta, Alquiler).\
• type - Tipo de propiedad (Casa, Departamento, PH).\
• rooms - Cantidad de ambientes (útil en Argentina).\
• bedrooms - Cantidad de dormitorios (útil en el resto de los países).\
• bathrooms - Cantidad de baños.\
• surface_total - Superficie total en m².\
• surface_covered - Superficie cubierta en m².\
• price - Precio publicado en el anuncio.\
• currency - Moneda del precio publicado.\
• price_period - Periodo del precio (Diario, Semanal, Mensual)\
• title - Título del anuncio.\
• description - Descripción del anuncio.\
• development - Campos relativos al desarrollo inmobiliario (vacío si el aviso es de una propiedad).\
• status - Estado del desarrollo (Terminado, En construcción, ...)\
• name - Nombre del desarrollo.\
• short_description - Descripción corta del anuncio.\
• description - Descripción del anuncio.\
