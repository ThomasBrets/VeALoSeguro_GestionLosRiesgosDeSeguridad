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


---

# Planificauna auditoría en seguridad
¿Como funcionan juntos los **marcos, controles,  principios de seguridad y cumplimiento normativo**?  
Mediante **Auditorías de seguridad**.

## Auditoría de seguridad
Ésta es una revisión de los controles de seguridad, políticas y procedimientos que tiene una organización.

Hay 2 tipos principales de auditorías de seguridad:  
**Auditoría interna y externa**.

### Auditoría interna
La suele realizar un equipo de personas que puede incluir al encargado de cumplimiento, gerente de seguridad y otros miembros del equipo.   

Éstas se utilizan para mejorar la postura de seguridad de una organización y evitar multas de agencias reguladoras por falta de cumplimiento normativo.

#### Propósitos de las auditorías internas:

- Identificar el riesgo organizacional. 

- Evalúa los controles.

- Corrige problemas de cumplimiento.


### Componentes comunes de las auditorías internas:
1. #### Definir el alcance y los objetivos de la auditoría:
El **alcance** se refiere a los criterios de una auditoría interna. El alcance requiere identificar las personas, activos, políticas y procedimientos y tecnologías que podrían afectar a la postura de seguridad.  
Los **objetivos** son un planteo de las metas de seguridad o que se quiere lograr para mejorar la postura de seguridad.

2. #### Evaluar el riesgos de los activos de la organización
Se centra en identificar amenazas, riesgos y vulnerabilidades potenciales. Esto ayuda a las organizaciones a decidir que medidas de seguridad implementar y monitorear para proteger sus activos.  
Al igual que definir el alcance u los objetivos, suelen evaluar el riesgo los gerentes u otras partes interesadas. 

___

### Preguntas de una auditoría
- ¿Qué se quiere lograr con la auditoría?

- ¿Qué activos están más en riesgo?

- ¿Son suficientes los controles actuales para proteger esos activos? 

- Si no lo son ¿Que controles y normativa de cumplimiento se deben implementar?

Al tener en cuenta estas preguntas dispondrás de una base para completar el siguiente elemento: **Evaluar los controles.**
___
3. #### Evaluar los controles
Implica revisar los activos de una organización y luego evaluar los posibles riesgos para esos activos a fin de garantizar que los controles internos sean efectivos.  
Para lograrlo los analistas de nivel inicial podrían clasificar los controles en las siguientes categorías:

- **Controles administrativos:** Se relacionan con el componente humano de la ciberseguridad. Son políticas y procedimientos que definen cómo una organización gestiona los datos, como la implementación de las políticas de contraseñas.

- **Controles técnicos:** Son soluciones de hardware y software para proteger los activos, como usar sistemas de detección e intrusiones (IDS) y cifrado.

- **Controles físicos:** Son medidas implementadas para evitar el acceso físico a los activos protegidos, como cámaras de vigilancia y cerraduras.


4. #### Evaluar el cumplimiento
Hay que evaluar si la organización sigue o no el cumplimiento normativo necesario. El cumplimiento normativo se refiere a las leyes que la organización debe seguir para proteger los datos privados.

5. #### Comunicar los resultados a las partes interesadas. 
Tras completar la auditoría interna, deben notificarse los resultados y las recomendaciones a las partes interesadas.  
En general, este tipo de comunicación:
- Resume el alcance y los objetivos de la auditoría. 

- Enumera los riesgos existentes.

- Indica con que velocidad deben abordarse.

- Identifica el cumplimiento normativo.

- Da recomendaciones para mejorar la postura de seguridad de la empresa.




