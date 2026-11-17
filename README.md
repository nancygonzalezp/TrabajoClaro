# TrabajoClaro
Seguimiento de trabajos y pagos para trabajadores independientes y sus clientes.

Trabajo grupal – Interacción Humano Computador, Unidad 2: "Modelos conceptuales, interfaces y prototipos". Ingeniería en Informática, Universidad Mayor.

Integrantes: Martina Alarcón y Nancy González

# Prototipo
Prototipo navegable: https://USUARIO.github.io/trabajoclaro/prototipo/
Código: prototipo/index.html, un solo archivo con HTML, CSS y JavaScript, sin dependencias.

Para probarlo sin internet, descarga prototipo/index.html y ábrelo con doble clic en el navegador.

# Qué permite hacer
Ver los trabajos y filtrarlos por: todos, los que requieren respuesta y los que tienen saldo por cobrar.
Crear un trabajo y enviar la propuesta al cliente.
Cambiar entre la vista del trabajador y la del cliente con el selector de la parte superior. Es una simulación: ambas vistas se usan en el mismo dispositivo.
El cliente acepta o rechaza el acuerdo y los adicionales, y antes de decidir ve cómo quedaría el saldo.
Registrar pagos parciales. Se bloquean los montos mayores al saldo y el último pago se puede deshacer.
Marcar el avance del trabajo (acordado, en curso, entregado) por separado del pago.
Consultar el historial de eventos con fecha.
Reglas de cálculo
Total confirmado = monto base aceptado + adicionales aceptados
Saldo = total confirmado − pagos registrados
Un adicional pendiente no suma al total.

Los datos se guardan en el navegador (localStorage). El enlace "Restablecer datos de ejemplo" vuelve a los datos iniciales.

Fuera del alcance: inicio de sesión, pagos reales y mensajería.
