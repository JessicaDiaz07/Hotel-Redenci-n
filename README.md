# Proyecto Final "Algoritmia y Programación" 

## Integrantes 

- Santiago Ceballos Garro – Encargado del código. 
- Luna Daniela Arismendi Tafur – Encargada de documentación. 
- Jessica Julieth Diaz Dizzett – Encargada de pruebas 

## Vínculos académicos y descripción: 

### Jessica Diaz , (Estudiante de Ingeniería Industrial) 

Es estudiante de Ingeniería Industrial y, aunque todavía no posee una amplia experiencia técnica, está preparada para aportar su enfoque analítico en el diseño y la organización de pruebas, la identificación de errores y la verificación de que el software cumpla con los requisitos establecidos y sea fácil de usar. 

### Luna Arismendi , (Estudiante de Ingeniería Industrial) 

Tiene una actitud positiva y está comprometida con el aprendizaje continuo, siempre interesada en crecer, adquirir nuevas habilidades y adaptarse a los cambios. Se destaca por su disciplina y comprende la importancia de la constancia y la organización para alcanzar sus objetivos. Le gusta interactuar con otras personas, construir relaciones positivas y fomentar un ambiente de trabajo colaborativo. 

### Santiago Ceballos , (Estudiante de Ingeniería Industrial) 

Soy una persona con iniciativa, siempre en busca de crecimiento personal y profesional. Me adapto con facilidad a los cambios y procuro extraer lo mejor de cada experiencia. Disfruto analizar situaciones, identificar problemas y proponer soluciones. Además, valoro el trabajo en equipo y me esfuerzo por contribuir de manera efectiva al logro de objetivos comunes. 

## Nombre del proyecto y detalles: 

## Hotel Redención 

### El proyecto Hotel Redención tiene como objetivo desarrollar un software de consola utilizando el lenguaje de programación Python, orientado a mejorar la gestión operativa del hotel Redención.  

Este sistema informático busca automatizar y optimizar dichos procesos mediante una aplicación intuitiva y fácil de usar desde la línea de comandos. Entre las principales funcionalidades que ofrecerá el software se encuentran: Registro de huéspedes: Captura y almacenamiento de los datos personales de cada visitante para su correcta identificación y seguimiento. Gestión de reservas: Asignación de habitaciones disponibles según fechas específicas, tipo de habitación y preferencias del cliente. Control de check-in y check-out: Registro automático de entradas y salidas, actualizando en tiempo real la disponibilidad de habitaciones. Cálculo de pagos: Generación precisa del valor a pagar según la duración de la estadía, tipo de habitación y servicios adicionales utilizados. Emisión de facturas: Creación de comprobantes detallados para el cliente, listando todos los cargos correspondientes a su estadía. Generación de reportes administrativos: Producción de informes periódicos para la gerencia sobre ocupación, ingresos, historial de huéspedes y otros indicadores clave para la toma de decisiones.  

### El objetivo del Hotel Redención 

Proporcionar un servicio de hospedaje cómodo y eficiente, brindando una experiencia memorable a sus huéspedes mediante la atención personalizada, un ambiente tranquilo y la mejora continua de sus procesos operativos para garantizar la satisfacción y fidelidad de sus clientes. 

### Logotipo del Proyecto 
![7544d7c6-70ce-4493-997a-1d5e0d928941](https://github.com/user-attachments/assets/62dae58d-4d87-4325-972f-b96995c40185)

## Licencia del software 

 Hotel Redención © 2025 por Jessica Diaz, Luna Arismendi, Santiago Ceballos está bajo licencia Creative Commons Reconocimiento-SinDerivadas 4.0 Internacional. Para ver una copia de esta licencia, visite https://creativecommons.org/licenses/by-nd/4.0/ 
 
## Reporte de visión 

Este software tiene como objetivo ayudar al Hotel Redención a gestionar de manera eficiente el registro de huéspedes, las reservas, los check-ins y check-outs, así como los cobros y la emisión de facturas. El programa resolverá problemas de desorganización, errores en la información y retrasos en los procesos, que actualmente se gestionan de forma manual. Si el sistema funciona correctamente, facilitará el trabajo administrativo, mejorará la precisión de los cobros, optimizará el tiempo del personal y proporcionará un mejor servicio a los clientes, permitiendo al hotel operar de manera más eficiente y sin inconvenientes. 

### Requisitos Especificados

El sistema debe ser capaz de gestionar de manera eficiente las operaciones de un hotel, incluyendo el registro de huéspedes, la realización de reservas, el registro de salida (check-out) y la administración de los datos de los huéspedes y las habitaciones. 

### Acciones que puede realizar el sistema: 

Registrar huésped: El sistema debe permitir registrar un nuevo huésped en el hotel. Se validarán los datos de nombre, apellido, documento de identidad, correo electrónico y teléfono. 
Realizar reserva de habitación: Solo los huéspedes registrados pueden realizar reservas. El sistema debe validar tipo de habitación, fechas de ingreso, número de noches y disponibilidad de habitaciones. Generar comprobante de reserva: Tras una reserva exitosa, el sistema debe generar un comprobante con todos los detalles de la reserva, incluyendo costo total estimado. 
Registrar salida (Check-Out): El sistema debe permitir el check-out solo si el huésped está registrado y tiene una estancia activa. 
Se debe calcular el costo final y generar una factura. 
Administración de usuarios: El sistema debe permitir que solo los usuarios con credenciales válidas accedan a la parte de administración del sistema. 
Generación de reportes administrativos: El sistema debe generar reportes sobre el total de huéspedes registrados, habitaciones ocupadas, habitaciones disponibles, ingresos generados, tiempo promedio de estancia, entre otros.  

### Expectativas del sistema: 

Validación de datos: El sistema debe validar correctamente todos los datos introducidos para los huéspedes, reservas, y check-out, asegurándose de que no haya errores como caracteres no permitidos o formatos incorrectos. Manejo de reservas: El sistema debe ser capaz de manejar las reservas de manera eficiente, asegurándose de que se asignen habitaciones disponibles y se calcule correctamente el costo basado en el tipo de habitación y el número de noches. Generación de comprobantes y facturas: Después de realizar una reserva o un check-out, el sistema debe generar y mostrar un comprobante o factura con la información completa. Control de acceso: Solo los usuarios autorizados deben poder acceder al módulo de administración y realizar acciones críticas como ver reportes y gestionar los datos de los huéspedes. 

### Lo que el sistema debe evitar: 

Errores de validación: El sistema no debe permitir que se registren huéspedes con datos incorrectos o incompletos. Reserva sin disponibilidad: No se debe permitir que los huéspedes realicen reservas para fechas en las que no haya disponibilidad de habitaciones. Cobro erróneo: El sistema debe evitar calcular costos incorrectos, especialmente en caso de salidas anticipadas. Acceso no autorizado: Los usuarios no autorizados no deben poder acceder a la parte administrativa del sistema. 

### Funciones necesarias para la solución: 

validar_nombre_apellido(nombre): Valida que el nombre y apellido del huésped tengan al menos 3 caracteres y no contengan números o caracteres especiales. 
validar_documento(documento): Valida que el documento de identidad tenga entre 3 y 15 dígitos y contenga solo números. 
validar_correo(correo): Valida que el correo electrónico tenga un formato adecuado (contenga un "@" y un dominio válido). 
validar_telefono(telefono): Valida que el teléfono tenga entre 7 y 15 dígitos y contenga solo números. 
realizar_reserva(huesped, tipo_habitacion, fecha_ingreso, num_noches): Permite realizar una reserva para un huésped previamente registrado, validando disponibilidad y fechas. 
calcular_costo(reserva): Calcula el costo total de la estancia en base al tipo de habitación y el número de noches. generar_comprobante(reserva): Genera un comprobante detallado de la reserva, incluyendo datos como costo total y fechas de estancia. registrar_salida(reserva): Realiza el proceso de check-out, calcula el costo y genera una factura con los detalles del huésped. 
autenticar_usuario(usuario, contrasena). Valida las credenciales del administrador y permite el acceso al módulo de administración. 
generar_reportes (huespedes, reservas): Genera los reportes administrativos sobre huéspedes registrados, habitaciones ocupadas, ingresos y más. 
