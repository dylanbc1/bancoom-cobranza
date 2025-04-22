# Banco Coomeva - Cobranza Agente IA
This is an AI agent for Banco de Occidente to automate collection tasks.

## Análisis de la Gestión de Cobranza (cada 30 minutos):

✅ Configurado con un disparador programado cada 30 minutos (Schedule Trigger)
✅ Analiza resultados y tendencias mediante el nodo Python que aplica los modelos ML
✅ Optimiza la asignación de canales de contacto (llamadas, SMS, WhatsApp, email) usando el modelo de predicción de canal


## Automatización de Tareas Operativas:

✅ Automatiza la estrategia de filtrado que actualmente consume 40 minutos diarios
✅ Implementa los mismos criterios de filtrado descritos en la estrategia de cobro
✅ Genera automáticamente la cartera optimizada sin intervención manual


## Alertas y Seguimiento de Contactabilidad:

✅ Comprueba si la contactabilidad es inferior al 26% (IF - Alerta Contactabilidad)
✅ Envía notificaciones por SMS y correo electrónico a coordinadores
✅ Genera registros detallados con estadísticas y resultados de la estrategia


## Cumplimiento de Normativa (Ley 2300 de 2023):

✅ El modelo Python incluye la función verificarCumplimientoLey2300 que valida restricciones legales
✅ Considera horarios permitidos para contacto en la determinación de canales


## Segmentación y Cargue Predictivo:

✅ Identifica el canal más efectivo para cada cliente mediante el modelo ML
✅ Genera automáticamente la base estructurada para cargar a Wolkvox
✅ Incluye la integración directa con Wolkvox mediante API (HTTP Request (Carga a Wolkvox))
