# Ejercicio 2: Facturacion con IVA, Descuento Condicional y Unidades Multiples

Programa en PHP que emite la factura de la compra de unidades de un artículo.

## Archivos
- `index.html`: formulario con descripción del artículo, cantidad y precio unitario.
- `facturar.php`: realiza los cálculos y muestra la factura.

## Funcionamiento
1. Subtotal (precio bruto) = cantidad x precio unitario.
2. IVA = 12% del subtotal.
3. Total con IVA = subtotal + IVA.
4. Si el total con IVA supera 150 $, se aplica un descuento del 15%.
5. Se muestra el desglose: subtotal, IVA, si aplica o no el descuento y el total neto a pagar.
