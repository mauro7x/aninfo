# Semana 1

## Notas de la Reunión

+ **Hablar en el idioma del modelo de dominio**

- Bajar el objetivo un poco mas a tierra. Describir lo que hace el sistema (desde el punto de vista del sistema)

"Este sistema vende los platos, les dice cuanto sale, y le dice a la persona que lo compra cuanto demora"

atiende pedidos, vende platos, envia pedidos, atiende consultas (que hay, cuanto sale, cuanto demora), control/verificacion de ingredientes, tarjeta/generar cupon/recibirlo firmado/guardarlo


- A partir de la revisión del objetivo, revisar los macroprocesos.

- Hipotesis y supuestos: cancelacion de pedidos? como lo atacamos?

# Semana 2

## Preguntas

- ¿Hipótesis sobre los tiempos de elaboración?

## Notas de la reunión

### Objetivo

- ~Diseñar y construir~
- Sacar paréntesis: (generando y cancelando sus debidos cupones)
- Se debe manejar el stock de _ingredientes_

### Supuestos

- El tiempo no se muestra en conjunto en la lista del menú -> revisar qué es válido hacer sobre cada etapa.
- Cmabiar el tema de manejo de stock.
- 

### Macroprocesos

- Gestión de menú -> gestión de platos/platillos
	- disponibilidad de cierto plato o no? (booleano)

- Gestión de pedidos -> good, considerar que incluye el manejo de los "clientes"

- Gestión de facturación
	- Cargar cupón de tarjeta firmado? -> reescribir

- Gestión de insumos -> revisar cómo está escrito respecto al manejo de stock

### Hacer diagrama de Actividades

Hacerlo representando diferentes escenarios. Ej:
- Cuando un cliente hace una consulta de un plato. Sólo pregunta, tiene un título "Cliente consulta un plato"
	- comienza el cliente
	- responde la gestión de platos
- 


### ¿Hasta dónde avanzamos cada semana?

Todo lo que veamos en la teórica podemos ir agregando.






