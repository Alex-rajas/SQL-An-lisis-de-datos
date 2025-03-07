## Evaluación Práctica en SQL sobre el Caso de Smart Desk

Smart Desk es una empresa global dedicada a la fabricación y distribución de mobiliario
de oficina, especializada en soluciones ergonómicas y tecnológicamente avanzadas. En
los últimos años, Smart Desk ha expandido sus operaciones a nivel global, lo que ha
generado la necesidad de analizar datos para ajustar sus estrategias de ventas,
optimizar sus pronósticos y maximizar el beneficio en sus operaciones.
Tu tarea será analizar los datos de Smart Desk utilizando SQL para extraer insights
relevantes, con un enfoque especial en el cálculo de beneficio y la interpretación de las
ventas, que apoyen la toma de decisiones estratégicas en diferentes regiones e
industrias.

## Información sobre las tablas


○ Sales: Contiene datos de ventas reales por cuenta, categoría de producto,
año, trimestre y unidades vendidas.

■ Account (VARCHAR): Identificador único de la cuenta o cliente.
Representa a la empresa que ha comprado productos o servicios.

■ Category (VARCHAR): Categoría del producto vendido.

■ Quarter (VARCHAR): Trimestre en que se realizó la venta.

■ Quarter of Year (VARCHAR): Trimestre del año.

■ Year (NUMBER): El año en el que se realizó la venta.

■ Maintenance ($) (NUMBER): Ingreso generado por servicios de
mantenimiento.

■ Parts ($) (NUMBER): Ingreso generado por la venta de partes o
repuestos.

■ Product ($) (NUMBER): Ingreso generado por la venta de
productos principales.

■ Profit ($) (NUMBER): Beneficio obtenido de la venta, después de
deducir los costes.

■ Support ($) (NUMBER): Ingreso por servicios de soporte técnico o
post-venta.

■ Total ($) (NUMBER): Total de ingresos generados por una
combinación de mantenimiento, partes, producto y soporte. Total de
Ventas

■ Units Sold (NUMBER): Cantidad de unidades vendidas durante la
transacción.


○ Accounts: Esta tabla contiene detalles sobre las cuentas de clientes,
como su ubicación, industria y los contactos relevantes.

■ Account (VARCHAR): Identificador único de la cuenta o cliente.

■ Account Executive (VARCHAR): Nombre del ejecutivo de cuentas
que gestiona la relación con el cliente.

■ Account Level (VARCHAR): Clasificación de la cuenta en función
de su importancia.

■ Contact Email (VARCHAR): Dirección de correo electrónico del
contacto principal de la cuenta.

■ Country (VARCHAR): País en el que se encuentra el cliente.

■ Industry (VARCHAR): Industria a la que pertenece el cliente.

■ Region (VARCHAR): Región geográfica.


○ Forecasts: Proporciona pronósticos de beneficios y oportunidades
comerciales futuras.

■ Account (VARCHAR): Identificador único de la cuenta o cliente.

■ Category (VARCHAR): Categoría de productos o servicios
pronosticados.

■ Prediction Category (VARCHAR): Clasificación del pronóstico.
Pipeline (oportunidades iniciales), Best Case (potenciales
optimistas) y Committed (ventas casi seguras).

■ Forecast ($) (NUMBER): Valor en dólares proyectado como
beneficio futuro.

■ Opportunity Age (NUMBER): Edad de la oportunidad, en días, que
mide cuánto tiempo ha estado abierta la oportunidad de venta. Las
oportunidades son procesos de venta no finalizados.

■ Year (NUMBER): Año del pronóstico
