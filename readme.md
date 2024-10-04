Cosas que hace este proyecto:

Utiliza nodejs, express y MongoDb Atlas, Mongoose, Multer, Handlebars y Websockets.

Para implemntar el backend de un ecommerce con carrito y productos.

Utilza Postman para las pruebas de CRUD en cada coleccion.


En el endpoint /products lista los productos en la base con paginate limit = 6 y page = 1 por defecto

http://localhost:8080/products?limit=10&page=1&sort=asc ordena por precio ascendente

http://localhost:8080/products?category=Pizzas&limit=5&page=2&sort=desc ordena desc y muestra los que tienen category = Pizzas

http://localhost:8080/products?search=Muzza&limit=5&page=1 busca los productos que tienen title Muzza en la pagina 1


En el endpoint /products/realtimeproducts muestra el formulario para dar de alta un producto y la lista actualizada con el producto dado de alta.Tambien en la lista se permite dar de baja un producto.

En el endpoint /products/cart/<cid> muestra los productos de un carrito.



Errores que no crashean la aplicacion:

