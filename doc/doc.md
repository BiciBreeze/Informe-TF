# Capítulo III: Requirements Specification
##### 3.1. To-Be Scenario Mapping.
###### Segmento 1: Jóvenes Universitarios
| Fases  | Se registra en el sitio web  | Explora funciones de la aplicacion   | Escoge un plan de suscripcion  | Obtiene resultados  |
| ------------ | ------------ | ------------ | ------------ | ------------ |
|  Doing |  Accede al sitio web y se registra.  |Navega por el menú principal y revisa las diversas opciones de alquiler.   |  Selecciona un plan de suscripción que se ajuste a sus necesidades. |  Después de un tiempo, revisa el historial de sus alquileres. |
|  Thinking | No puede creer que registrarse en el sitio web sea tan fácil.  | Considera cómo el sitio web puede ayudarle a encontrar bicicletas en su área.  |Piensa que ha encontrado un plan de suscripción que le permitirá ahorrar dinero.   |Reflexiona sobre cómo el sitio web le ha ayudado a gestionar sus alquileres de manera eficiente.   |
|   Feeling| Siente emoción por explorar las funciones del sitio web.  |  Se siente motivado a usar el servicio y a aprovechar las bicicletas disponibles. |Siente satisfacción al encontrar un plan de suscripción adecuado. |  Se siente feliz por haber optimizado sus recorridos y ahorrado tiempo y dinero. | 
###### Segmento 1: Profesionales Urbanos
| Fases  | Se registra en el sitio web  | Explora funciones de la aplicacion   | Escoge un plan de suscripcion  | Obtiene resultados  |
| ------------ | ------------ | ------------ | ------------ | ------------ |
|  Doing |  Se registra en el sitio web proporcionando su información profesional. |Explora las diversas funciones del sitio web, como las rutas recomendadas y los puntos de alquiler cercanos a su trabajo.   |  Selecciona un plan de suscripción adaptado a sus necesidades laborales, como el acceso rápido a bicicletas en horas punta.|  Revisa su historial de alquileres y analiza cómo ha optimizado sus desplazamientos diarios. |
|  Thinking | Se sorprende de lo fácil que fue registrarse en el sitio web y empezar a usar el servicio. | Considera cómo el sitio web puede ayudarle a mejorar su eficiencia en los desplazamientos urbanos. |Piensa que ha encontrado el plan de suscripción ideal para reducir tiempo y costos en sus viajes al trabajo.  |Reflexiona sobre cómo el sitio web ha mejorado su productividad al facilitar desplazamientos rápidos y sin complicaciones.   |
|   Feeling| Siente una gran motivación por aprovechar al máximo las funciones del sitio web para optimizar sus trayectos.  |  Se siente responsable y motivado a utilizar el servicio para hacer sus desplazamientos más sostenibles y eficientes. |Siente satisfacción al haber elegido un plan que se adapta perfectamente a su ritmo laboral. |  Se siente realizado al comprobar que ha mejorado significativamente la gestión de su tiempo gracias al servicio de alquiler. | 

##### 3.2. User Stories.
### Epicas

|  Epic | Titulo  |  Descripcion |
| ------------ | ------------ | ------------ |
| EP01   |  Gestión de Cuentas de Usuario |  Como usuario, quiero registrarme, iniciar sesión y gestionar mi cuenta para acceder de manera segura a la aplicación y mantener mis datos personales actualizados.|
| EP02  |  Navegación Intuitiva y Accesible |  Como  usuario quiero un sistema de navegación que me permita acceder rápidamente a  las funciones principales, como buscar y gestionar casos, usar el chat para  el seguimiento y actualizar mi perfil, mejorando mi experiencia en BiziBrezze.|
| EP03  |  Landing Page Informativa | Como usuario interesado, quiero una landing page clara, atractiva y fácil de entender, que me informe sobre BiziBreeze y los servicios que ofrece, para que pueda tomar una decisión informada sobre su uso.|

|User Story ID | Título  | Descripción   |  Criterios de aceptación |  
| -------- | ------------ | ------------ | ------------ | 
|  US01 | Registro de cuenta  | Como visitante de la landing page, quiero poder registrarme facilemente al sitio web recibiendo un correo de confirmacion, para poder disfrutar los beneficios.  |  Escenario: **Dado que** quiero registrarme al sitio web, **cuando** ingrese a BiziBreeze **y**  le de click a la opcion de registro, **entonces** podre colocar mis datos **y** recibir un correo de verificacion de cuenta.   |   
| US02  |  Ver informacion |  Como visitante de la landing page, quiero ver un diseño moderno y atractivo, para sentir confianza y motivación a usar el servicio. |  Escenario:  **Dado que** el usuario está interesado en alquilar bicicletas, **cuando** ingrese al sitio web de BiziBreeze, **entonces** se mostrará información detallada sobre los planes de suscripción del sitio web y como esta funciona. |  
|  US03 | Tener informacion clara  | Como visitante de la landing page, quiero una interfaz clara y fácil de usar, para reservar una bicicleta rápidamente.  |  Escenario: **Dado que** estoy en la página de reservas, **cuando** interactúe con los elementos, **entonces** el proceso de reserva debería completarse en menos de 3 pasos. |   
| US04  | Ver ubicaciones de bicicleta  | Como usuario, quiero ver un mapa interactivo con estaciones de bicicletas, para localizar la bicicleta más cercana.  | Escenario: **Dado que** quiero buscar una bicicleta, **cuando** abra el mapa, **entonces** debería visualizar las estaciones disponibles en tiempo real.  |   
|  US05 |  Recibir notificaciones | Como usuario, quiero recibir notificaciones en tiempo real sobre la disponibilidad de bicicletas, para estar informado de los cambios.  | Escenario: **Dado que** he configurado notificaciones, **cuando** haya un cambio en la disponibilidad, **entonces** debería recibir una notificación inmediata.  |   
|  US06| Dejar opiniones  | Como usuario, quiero poder compartir mi experiencia en la plataforma, para ayudar a otros usuarios a tomar decisiones.  | Escenario: **Dado que** he usado el servicio, **cuando** intente dejar una reseña, **entonces** debería poder hacerlo fácilmente desde mi perfil.  |   
|  US07 |  Iniciar Sesion  | Como usuario, quiero un sistema de autenticación rápido y seguro, para iniciar sesión sin problemas.  | Escenario:  **Dado que** quiero iniciar sesión, **cuando** ingrese mis credenciales, **entonces** debería poder acceder a mi cuenta en menos de 5 segundos. |   
|  US08 | Personalizacion de Perfil  | Como usuario, quiero poder personalizar mi perfil, para ajustar mis preferencias de uso y comunicación.  | Escenario: **Dado que** quiero cambiar mis datos, **cuando** edite mi perfil, **entonces** los cambios deberían reflejarse inmediatamente.  |   
|  US09 | Promocion especial  |  Como usuario universitario, quiero una suscripcion especial, para animarme y animar a muchos estudiantes en adquirir los servicios.  | Escenario: **Dado que** vaya a adquirir los servicios, **cuando**  me registre con mi correo institucional, **entonces** se aplicara una suscripcion especial para estudiantes. |   
|  US10 |  Seguridad de datos |  Como usuario, quiero que mis datos personales estén seguros, para sentirme confiado al usar la plataforma. | Escenario: **Dado que** he proporcionado mis datos, **cuando** los guarde en la plataforma, **entonces** deberían estar encriptados y almacenados de manera segura.  |   
|  US11 | Alerta de suscripcion  |  Como usuario, quiero recibir un recordatorio antes de que mi reserva expire, para evitar perder mi bicicleta reservada. | Escenario: **Dado que** he reservado una bicicleta, **cuando** esté cerca de expirar la reserva, **entonces** debería recibir un recordatorio.  |   
|  US12 | Reportes de problemas |  Como usuario, quiero poder reportar problemas con las bicicletas, para que se solucionen rápidamente. | Escenario: **Dado que** encuentro un problema con una bicicleta, **cuando** lo reporto, **entonces** debería recibir una confirmación de que el reporte ha sido recibido.  |   
|  US13 | Reportes de uso  | Como usuario, quiero que el sistema genere reportes automáticos de mi uso mensual, para poder revisar mi actividad y gastos.   | Escenario:   **Dado** que quiero revisar mi actividad mensual, **cuando** solicito un reporte, **entonces** el sistema debería generar y enviar automáticamente un resumen detallado de mis viajes y pagos durante el mes. |   
|  US14 |  Preferencias de usuario | Como usuario, quiero que el sistema mantenga un registro de mis preferencias de viaje, para que el proceso de alquiler sea más rápido en el futuro.   |  Escenario: **Dado** que tengo preferencias de viaje guardadas, **cuando** hago una nueva reserva, **entonces** el sistema debería sugerir opciones basadas en mis preferencias anteriores. |   
|  US15 |  Idioma preferido | Como usuario, quiero acceder a la landing page en mi idioma preferido, para entender mejor la información proporcionada.  |  Escenario: **Dado** que la landing page detecta mi idioma, **cuando** accedo al sitio, **entonces** debería ver la versión de la página en mi idioma preferido. |   
|  US16 | Cambio de contraseña  |  Como usuario, quiero recibir un correo electrónico de confirmación después de cambiar mi contraseña, para estar seguro de que la actualización se ha realizado correctamente. | Escenario: **Dado** que he cambiado mi contraseña, **cuando** la actualización se complete, **entonces** debería recibir un correo electrónico de confirmación con la hora y fecha del cambio.  |   
|  US17 | Contraseña Encriptada  | Como usuario, quiero que mi contraseña sea encriptada en la base de datos, para proteger la seguridad de mi cuenta.  | Escenario: **Dado que** registro o cambio mi contraseña, **cuando** el sistema la almacena, **entonces** debería encriptarla antes de guardarla en la base de datos.  |   
|  US18 | Recordar inicio de sesion  |  Como usuario, quiero que el sistema me recuerde mi sesión iniciada incluso después de cerrar y reabrir BiziBreeze, para evitar tener que iniciar sesión repetidamente. |  Escenario: **Dado que** inicio sesión en el sitio web, **cuando** la cierro y la vuelvo a abrir dentro de un período de tiempo razonable, **entonces **debería seguir estando autenticado sin necesidad de volver a iniciar sesión. |   
|  US19 | Agregar Favoritos  | Como usuario, quiero poder agregar bicicletas a una lista de favoritos, para alquilar rápidamente mis bicicletas preferidas sin tener que buscarlas cada vez.  | Escenario: **Dado que** he encontrado una bicicleta que me gusta, **cuando** selecciono la opción "Agregar a favoritos", **entonces** la bicicleta debería ser añadida a mi lista de favoritos **y** ser fácilmente accesible desde mi perfil.   |   
| US20  |  Historial | Como usuario, quiero poder ver un historial de todas mis reservas y alquileres anteriores, para revisar cuándo y dónde he usado el servicio.  |Escenario: **Dado que** he realizado reservas y alquileres en el pasado, **cuando** accedo a la sección de historial en mi perfil, **entonces** debería ver una lista cronológica de todas mis reservas y alquileres, incluyendo fechas, horas, y ubicaciones de uso.  |

##### 3.3. Impact Mapping.
![ef2671ed-62cf-40fa-bf76-21ba165061fa](https://github.com/user-attachments/assets/f2ffc57b-c6b0-4825-a250-ebd132e30fbe)
![defbe6f6-6376-4186-86b6-06af25db54b0](https://github.com/user-attachments/assets/6102ad1f-f238-42b6-aaa0-c64163bbe92e)


##### 3.4. Product Backlog.

| Orden  |User Story ID  | Titulo   | Descripcion | Prioridad |
| ------------ | ------------ | ------------ | ------------ | ------------ |
|  1 | US01 | Registro de cuenta  | Como ciudadano que le interesa el servicio, quiero poder registrarme facilemente al sitio web recibiendo un correo de confirmacion, para poder disfrutar los beneficios. | Alta  |
| 2  | US02 | Ver informacion  |Como usuario, quiero ver un diseño moderno y atractivo en la landing page, para sentir confianza y motivación a usar el servicio.  | Alta  |
| 3  | US03 | Tener informacion clara  |Como usuario, quiero una interfaz clara y fácil de usar, para reservar una bicicleta rápidamente.  | Alta  |
|  4 | US04 | Ver ubicaciones de bicicleta  |Como usuario, quiero ver un mapa interactivo con estaciones de bicicletas, para localizar la bicicleta más cercana.  |  Alta |
| 5  | US05 | Recibir notificaciones  | Como usuario, quiero recibir notificaciones en tiempo real sobre la disponibilidad de bicicletas, para estar informado de los cambios. | Alta  |
|  6 | US06 | Dejar opiniones  | Como usuario, quiero poder compartir mi experiencia en la plataforma, para ayudar a otros usuarios a tomar decisiones. |  Media |
| 7 | US07 |  Iniciar Sesion | Como usuario, quiero un sistema de autenticación rápido y seguro, para iniciar sesión sin problemas. |  Alta |
| 8  | US08  | Personalizacion de Perfil  |Como usuario, quiero poder personalizar mi perfil, para ajustar mis preferencias de uso y comunicación.  | Alta  |
| 9  | US09 | Promocion especial  |Como usuario universitario, quiero una suscripcion especial, para animarme y animar a muchos estudiantes en adquirir los servicios.  |  Alta |
| 10  | US10 | Seguridad de datos  |  Como usuario, quiero que mis datos personales estén seguros, para sentirme confiado al usar la plataforma.| Alta  |
| 11  |  US11| Alerta de suscripcion  | Como usuario, quiero recibir un recordatorio antes de que mi reserva expire, para evitar perder mi bicicleta reservada. | Alta  |
|  12 | US12 |Reportes de problemas   | Como usuario, quiero poder reportar problemas con las bicicletas, para que se solucionen rápidamente. |  Alta |
| 13  | US13 | Reportes de uso  |Como usuario, quiero que el sistema genere reportes automáticos de mi uso mensual, para poder revisar mi actividad y gastos.  |  Alta |
| 14  |US14  | Preferencias de usuario  | Como usuario, quiero que el sistema mantenga un registro de mis preferencias de viaje, para que el proceso de alquiler sea más rápido en el futuro. |  Alta |
|15   |US15  | Idioma preferido  | Como usuario, quiero acceder a la landing page en mi idioma preferido, para entender mejor la información proporcionada.  | Media  |
|16   | US16 |  Cambio de contraseña |Como usuario, quiero recibir un correo electrónico de confirmación después de cambiar mi contraseña, para estar seguro de que la actualización se ha realizado correctamente.  | Alta  |
| 17  | US17 | Contraseña Encriptada  |Como usuario, quiero que mi contraseña sea encriptada en la base de datos, para proteger la seguridad de mi cuenta.  |Alta   |
| 18  | US18 |Recordar inicio de sesion   |Como usuario, quiero que el sistema me recuerde mi sesión iniciada incluso después de cerrar y reabrir BiziBreeze, para evitar tener que iniciar sesión repetidamente.  |  Alta |
| 19  |US19  |  Agregar Favoritos | Como usuario, quiero poder agregar bicicletas a una lista de favoritos, para alquilar rápidamente mis bicicletas preferidas sin tener que buscarlas cada vez. |Alta   |
| 20  | US20 | Historial  |	Como usuario, quiero poder ver un historial de todas mis reservas y alquileres anteriores, para revisar cuándo y dónde he usado el servicio.  |Media   |