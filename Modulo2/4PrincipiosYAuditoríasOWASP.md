# Principios de Seguridad del Open Web Application Security Project (OWASP)
---

-  ### Minimizar la superficie expuesta a ataques
Se refiere a todas las vulnerabilidades potenciales que podría aprovechar un agente de amenaza.

**Ejemplo:** Vectores de ataque, que son vías de acceso que los atacantes utilizan para penetrar las defensas de seguridad.(correos de phishing y contraseñas poco seguras).

- ### Principio de mínimo privilegio
Significa conceder únicamente el acceso y la autorización mínimos necesarios para completar una tarea o función. La razón para limitar el acceso a la información y los recursos de la organización es reducir el daño que podría causar una violación de seguridad.

**Ejemplo:** Como analista de nivel inicial, puede que tengas acceso a los datos de registro pero es posible que no tengas acceso para cambiar los permisos de usuario.

- ### Defensa en profundidad
Hace referencia a que las organizaciones deben disponer de varios controles de seguridad que aborden los riesgos y las amenazas de diferentes maneras.

**Ejemplo:** La autenticación de múltiples factores (MFA), requiere un paso mas allá de solo ingresar el nombre de usuario y contraseña para acceder a una aplicación. Otros ejemplos pueden ser firewalls, sistemas de detección de intrusiones y configuraciones de permisos.


- ### Separación de funciones
 Refiere a que las acciones críticas deben depender de varias personas, cada una de las cuales sigue el principio del mínimo privilegio. 

 **Ejemplo:** El empleado que firma las nóminas no debería ser también quien las prepara.


- ### Simplificar la seguridad
Tiene que ver con evitar soluciones innecesariamente complicadas, porque la complejidad dificulta la seguridad.


- ### Solucionar los problemas de seguridad correctamente
ignifica que, cuando ocurren incidentes de seguridad, es necesario identificar la causa, contener el impacto, detectar las vulnerabilidades y realizar pruebas para garantizar que la reparación sea exitosa.

**Ejemplo:** Una contraseña débil para acceder a la red Wi-Fi de la organización porque podría causar una falla de seguridad. Para solucionar esto se podrían implementar políticas de contraseñas mas estrictas.


## Otros principios de seguridad de OWASP
A continuación, aprenderás acerca de otros cuatro principios de seguridad de OWASP que se utilizan para mantener seguras las operaciones de una organización y a las personas

- ### Establecer configuraciones seguras por defecto
Este principio indica que el estado de seguridad óptimo de una aplicación también debe ser su estado predeterminado para los usuarios. O sea, debería requerirse un esfuerzo adicional para hacer que la aplicación sea insegura. 

- ### Fallar de forma segura
Fallar de forma segura significa que, cuando un control falla o se detiene, debe hacerlo restableciéndose automáticamente a su opción más segura. 

**Ejemplo:** Si un cortafuegos (firewall) falla, simplemente, debería cerrar todas las conexiones y bloquear las nuevas, en lugar de comenzar a aceptar todo.

- ### No confiar en los servicios
Muchas organizaciones trabajan con firmas asociadas o proveedoras de servicios. Estas suelen tener políticas de seguridad diferentes a las de la empresa. Por lo tanto, la compañía no debería dar por sentado que los sistemas de estas firmas sean seguros.   

**Ejemplo:** Si una aerolínea terceriza a una empresa proveedora el seguimiento de los puntos de recompensa, antes de compartir esa información con sus clientes, debería asegurarse de que los datos obtenidos y el saldo sean precisos.


- ### Evitar la seguridad por oscuridad
La seguridad de los sistemas clave no debe depender de mantener los detalles ocultos. Analiza el siguiente ejemplo de OWASP (2016):

La seguridad de una aplicación no debe depender de mantener el código fuente en secreto, sino que su seguridad tiene que basarse en muchos otros factores, como las políticas de contraseñas razonables, la defensa en profundidad, los límites de transacciones comerciales, una sólida arquitectura de red, y los controles de fraude y auditoría.


## Conclusion
Las y los profesionales de la ciberseguridad aplican constantemente los principios de seguridad para proteger a las organizaciones y a las personas. Como analista de ciberseguridad de nivel inicial, puedes utilizar estos principios para implementar prácticas seguras que reduzcan los riesgos tanto para las empresas como para los usuarios. 



