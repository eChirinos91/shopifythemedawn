Tienda shopify FeremiTech

Este documento proporciona una descripción general de las personalizaciones realizadas en tu tienda de Shopify. Las personalizaciones incluyen la creación de una página de colección personalizada, una sección de reseñas y la funcionalidad para agregar automáticamente un regalo al carrito. El objetivo de estas personalizaciones es mejorar la experiencia de compra proporcionando un proceso optimizado para agregar productos al carrito y mostrar las reseñas de los clientes.

Página de Colección Personalizada
Archivo: templates/sbh-collection-section.liquid
Esta plantilla muestra una colección de productos e incluye un formulario para agregar cada producto al carrito. Si ya hay un producto de servicio en el carrito, se reemplaza con el nuevo producto seleccionado.

Características Clave:

Muestra productos de una colección específica.
Agrega automáticamente un regalo (Camisa SMG + Lunch Box) al carrito cuando se agrega un producto.
Actualiza el carrito para reemplazar el producto de servicio existente si se selecciona uno nuevo.
Muestra mensajes de error en un modal si ocurre algún problema durante el proceso.

Sección de Reseñas
Archivo: sections/reviews-section.liquid
Esta sección muestra las reseñas de los clientes. Cada reseña incluye la imagen del cliente, su nombre, la calificación en estrellas y el comentario.

Agrega un regalo (Camisa SMG + Lunch Box) cuando se agrega un producto al carrito.

Sección de Review
Archivo: sections/reviews-section.liquid
Esta sección muestra las reseñas de los clientes. Cada reseña incluye la imagen del cliente, su nombre, la calificación en estrellas y el comentario.

Características Clave:

- Permite agregar múltiples reseñas.
- Cada reseña incluye una imagen, nombre, calificación en estrellas y comentario
- Configurable a través del personalizador de temas de Shopify.

Funcionalidad de Regalo Gratis
JavaScript para Agregar el Regalo Gratis
Este código JavaScript agrega automáticamente un regalo al carrito cuando se agrega un producto. También asegura que si ya hay un producto de servicio en el carrito, se reemplaza con el nuevo producto de servicio seleccionado.

Características Clave:

Agrega un regalo (Camisa SMG + Lunch Box) cuando se agrega un producto al carrito.
Reemplaza el producto de servicio existente en el carrito con el nuevo producto de servicio seleccionado.
Muestra mensajes de error en un modal si ocurre algún problema durante el proceso.
