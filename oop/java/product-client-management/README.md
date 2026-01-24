# Sistema de Gestión de Almacén
1. Existen dos tipos de productos (Perecederos y No Perecederos).
2. Ambos tipos de productos poseen descripción, precio y cantidad de inventario, dichos atributos pueden ser nulos.
3. Los productos perecederos poseen un atributo que indica la cantidad de días que le quedan para vencer.
4. Crear un método que calcule el precio del inventario, tomando en cuenta que los productos perecederos tienen un 30% menos de valor “oferta” si poseen menos de 10 días por vencer.
5. Los clientes poseen nombre, apellido, tipo y número de documento.
6. Crear un método utilitario que imprima la lista de productos en oferta un texto como texto:

Hola {nombre}:
Esta semana tenemos los siguientes ofertas para ti:
- {descripcion} Antes: {precio} Después:{oferta}.