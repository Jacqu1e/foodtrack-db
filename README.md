
# foodtrack-db
Esquema relacional para FoodTrack, una plataforma de gestión de operaciones de foodtrack en distintos puntos de una ciudad.

## Descripción del modelo
La base de datos contempla información de foodtrucks, productos, pedidos, ubicaciones, y detalle de ítems pedidos.

Diagrama relacional

<img width="5149" height="4468" alt="Diagrama ER" src="https://github.com/user-attachments/assets/76004ff3-9f62-4aec-8b88-b191a92c24e5" />

| Tabla | Descripción|
| ----------- | ----------- | 
|  Foodtrucks | Información de cada foodtruck (nombre, tipo de cocina, ciudad | 
| Products | Productos ofrecidos por cada foodtruck |
| orders | Pedidos realizados a un foodtruck |
| order_items | Detalle de productos por pedido |
| locations | Ubicaciones registradas de cada foodtruck |
