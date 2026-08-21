# RetailMax | Segmentacion de clientes

## Recomendaciones para el equipo de marketing

### 1. El reto
RetailMax necesita dejar atras las campañas generales y adaptar sus mensajes a los distintos comportamientos de compra. Para encontrar patrones se aplico K-Means sobre edad, ingreso anual y Spending Score. Las variables fueron estandarizadas antes del modelado para que ninguna dominara el resultado por su escala.

### 2. La fotografia del conjunto de datos

**200 clientes analizados**  
**5 segmentos identificados**  
**3 variables de comportamiento y perfil**  
**56% mujeres y 44% hombres**

Los clusters no representan categorias buenas o malas. Son grupos de clientes con comportamientos parecidos y deben utilizarse como una herramienta para personalizar campañas, priorizar presupuesto y diseñar mejores ofertas.

## 3. Los cinco perfiles

### Cluster 0 | Bajo ingreso, bajo gasto
**20 clientes | 46.3 anos | 26.8 k$ de ingreso | 18.4 de gasto**

Es el segmento de menor poder adquisitivo y menor puntuacion de gasto. Se recomienda utilizar promociones de entrada, descuentos moderados, productos economicos y mensajes centrados en el valor. Conviene medir la rentabilidad antes de invertir demasiado en este grupo.

### Cluster 1 | Jovenes con potencial
**54 clientes | 25.2 anos | 41.1 k$ de ingreso | 62.2 de gasto**

Es el grupo mas numeroso y presenta una puntuacion de gasto elevada para su nivel de ingreso. Se recomiendan campanas digitales, contenido para redes sociales, beneficios por frecuencia, referidos y promociones de tiempo limitado. Este segmento puede convertirse en uno de los principales motores de crecimiento.

### Cluster 2 | Clientes premium activos
**40 clientes | 32.9 anos | 86.1 k$ de ingreso | 81.5 de gasto**

Representa el perfil de mayor valor comercial: alto ingreso y alto gasto. Debe recibir experiencias premium, acceso anticipado a lanzamientos, recomendaciones personalizadas, paquetes de mayor margen y programas de fidelizacion exclusivos. Es importante proteger su relacion con la marca y evitar descuentos innecesarios.

### Cluster 3 | Alto ingreso, bajo involucramiento
**39 clientes | 39.9 anos | 86.1 k$ de ingreso | 19.4 de gasto**

Tiene capacidad economica, pero compra poco. El objetivo debe ser la reactivacion. Se sugieren mensajes personalizados, recordatorios, beneficios de primera recompra, encuestas de satisfaccion y ofertas basadas en categorias de interes. No conviene asumir que un ingreso alto implica lealtad.

### Cluster 4 | Clientes maduros de gasto medio
**47 clientes | 55.6 anos | 54.4 k$ de ingreso | 48.9 de gasto**

Es un segmento amplio y estable. Se recomiendan comunicaciones claras, beneficios por recurrencia, servicio posventa, promociones practicas y canales que transmitan confianza. Las campanas deben priorizar la retencion y aumentar gradualmente la frecuencia de compra.

## 4. Incorporacion del genero

Al incluir genero en un segundo modelo, aparecieron patrones complementarios: un cluster de alto ingreso y alto gasto con 54% de mujeres, otro de alto ingreso y bajo gasto con 55% de mujeres, un segmento de ingreso medio compuesto completamente por mujeres y un segmento de clientes mayores compuesto completamente por hombres. Estos resultados deben usarse para personalizar creatividades y canales, nunca para excluir clientes ni asumir preferencias individuales.

## 5. Plan de accion

**Prioridad 1:** fidelizar al Cluster 2 con beneficios premium.  
**Prioridad 2:** activar al Cluster 3 con campañas de recuperacion.  
**Prioridad 3:** hacer crecer al Cluster 1 mediante frecuencia, referidos y canales digitales.  
**Prioridad 4:** retener al Cluster 4 con confianza y servicio.  
**Prioridad 5:** atender al Cluster 0 con propuestas de valor sostenibles.

### Conclusion
El clustering permite pasar de una estrategia masiva a una estrategia segmentada. La recomendacion es lanzar una campana piloto por cluster, medir conversion, ticket promedio, frecuencia y retorno de inversion, y revisar los segmentos periodicamente. Los clusters son una fotografia del comportamiento actual, no una etiqueta permanente: deben actualizarse cuando cambien los datos o las condiciones del negocio.
