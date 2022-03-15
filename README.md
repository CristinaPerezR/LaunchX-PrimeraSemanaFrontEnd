# LaunchX-PrimeraSemanaFrontEnd
Entregables de la primera semana de la Misión FrontEnd del programa LaunchX de InnovaccionVirtual

## Caso: Abogabot
Descripción: Es un despacho de abogados que quiere automatizar las demandas de sus clientes, esto lo harán a traves de una página web llenando un formulario.
Al momento de llenar el formulario se manda al proceso de pago para finalizar la transacción. Para dar seguimiento a su demanda, el cliente crea una cuenta en la plataforma y verá el seguimiento de cada una de las actualizaciones del proceso legal. El administrador del sitio recbe la notificación de una nueva demanda y con los datos llenados del formulario se crea automaticamente el documento legal en formato word para empezar el proceso. El administrador recibe el pago y debe de ser capaz de verlo en un dashboard para ver la cantidad de ingresos recibidos. El administrador actualiza el proceso de la demanda y agrega comentarios en cada paso del proceso. Al usuario le llegan correos de notificación para saber el avance de su proceso. La página debe de ser responsive para poderla ver desde el celular. La preferencia de colores del cliente es azul marino y blanco, pero acepta propuestas.

## Bosquejo de la app
### Usuario
El usuario deberá identificarse para llegar a la página inicial, si no cuenta con una cuenta deberá crear una. En la página inicial le aparecerán dos opciones: crear una nueva solicitud o ver el estado de su solicitud. 
Para crear una nueva solicitud de demanda debe llenar un formulario con los datos necesarios para proceder a la demanda, para finalizar la solicitud tendrá que proceder al proceso de pago. El usuario podrá ver en cualquier momento el status de su demanda de acuerdo a las actualizaciones del abogado a cargo. 

### Administrador (Abogado)
El administrador deberá ingresar a la página con el usuario y contraseña que le fue asignada. Para ver todas las solicitudes de demanda, deberá ingresar ya sea a la opción de nuevas demandas o demandas anteriores actualizadas, en donde podrá seleccionar el proceso a actualizar y generar los comentarios del mismo. El administrador también podrá solicitar un pago adicional si el proceso de demanda así lo requiere. El administrador podrá ver en "pagos recibidos" la actualización de pago de los usuarios en su proceso de demanda 

## Requerimientos: 
1. Sistema de sign in y sign up
2. Formulario de nueva solicitud de consulta legal
3. Formulario de pago
4. Sign up para administradores 
5. Dashboard que muestra los pagos recibidos, las nuevas consultas solicitadas y las que se encuentran en proceso
6. Pantalla para hacer modificaciones, agregar comentarios y solicitar cargos adicionales de las demandas en proceso
7. Crear automaticamente un archivo .docx con la información del proceso legal. 

## Buyer Persona:
Laura Alcantara de 28 años, Ingeniera de Calidad en Lear Corporation. 
Laura es una persona muy proactiva en su trabajo. Es Ingeniera Industrial titulada con honores. Al graduarse comenzó a trabajar de tiempo completo en la industria automotriz, logrando posiciones líderes. En sus tiempos libres practica yoga y tiene un grupo pequeño de amigos con los que les gusta salir a divertirse, además en una avida lectora. Uno de sus sueños es alcanzar el siguiente nivel de estudio y así conseguir una mejor posición dentro de la empresa. 

**Personalidad:** Es una persona alegre pero tímida. Parte de esa timidez es por la inseguridad que le producen sus colaboradores a la hora de tomar las decisiones.   Disfruta de la compañía de sus amigos y el tiempo sola. 

**Metas:** Convertirse en gerente de ingeniería y tomar más posiciones de liderazgo dentro de la organización. Terminar una maestría. 

**Frustraciones:** Le cuesta tomar decisiones de manera rápida, aunque es muy buena organizandose, sus colaboradores no siguen sus lineamientos debido a que la ven muy joven. 

**Necesidades:** Requiere personal que la respete y valore su posición de liderazgo para cumplir con sus objetivos dentro de la empresa. 

!(https://github.com/CristinaPerezR/LaunchX-PrimeraSemanaFrontEnd/blob/a59fcb65661e837234f2681026dd18122f300883/Buyer%20persona.png)

## Público Objetivo: 
### Perfil Geográfico:
-	Que radiquen en Tlaxcala o Puebla. 
-	Que hablen español. 
-	Habitantes urbanos.

### Perfil Demográfico:
- Personas entre 24 y 34 años.
- Con ingresos arriba de los 10,000 pesos mexicanos
- Personas que se identifiquen como mujeres
- Su giro sea la industria automotriz o de servicios 
- Que gozen de una vivienda propia o que sean independientes
### Perfil Psicográfico:
- Han presentado problemas legales con anterioridad 
- Personas ocupadas que valoren el tiempo de ellas y las demás personas
- No estén conforme con el manejo de sus asuntos legales 
### Perfil de Comportamiento:
- Abiertas a las nuevas tecnologías 
- Activos en las redes sociales 
- Les guste el orden y la organización aplicada en cada parte de su vida 
- Trabajadoras 
