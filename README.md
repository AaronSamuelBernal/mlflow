# MLflow

Es una plataforma que permite administrar el ciclo de vida del desarrollo de machine learning desde el principio hasta el final. Posee los siguientes componentes principales

# Seguimiento 
- Le permite realizar un seguimiento de los experimentos para registrar y comparar resultados y parámetros.
# Modelos 
- Permite administrar e implementar modelos desde bibliotecas de aprendizaje autómatico a una variedad de plataformas y servicio de modelos
# Proyectos 
- Permite empaquetar código de machine learning de manera que sea reutilizable y reproducible para ser compartido o llevarlos a producción
# Registro de Modelos 
- Gestionar de forma colaborativa el ciclo de vida completo de un modelo MLflow, incluyendo el versionado de modelos, las transiciones de etapas y las anotaciones

## Casos de Uso

- Científicos de datos de manera individual pueden usar MLflow Tracking para rastrear experimentos localmente en su máquina, organizar código en proyectos para su reutilización futura y modelos de salida que los ingenieros de producción pueden implementar utilizando las herramientas de implementación de MLflow. MLflow Tracking solo lee y escribe archivos en el sistema de archivos local de forma predeterminada, por lo que no es necesario implementar un servidor.
- Científicos de datos en equipos pueden implementar un servidor de seguimiento de MLflow para registrar y comparar resultados entre varios usuarios que trabajan en el mismo problema. Al establecer una convención para nombrar sus parámetros y métricas, pueden probar diferentes algoritmos para abordar el mismo problema y luego ejecutar los mismos algoritmos nuevamente en nuevos datos para comparar modelos en el futuro.
- Ingenieros de producción  pueden implementar modelos de diversas bibliotecas de ML, almacenar los modelos como archivos en un sistema de administración de su elección y realizar un seguimiento de qué ejecución proviene un modelo.

## Cómo Ejecutar
1. Clone el repositorio
2. Modifique el archivo .env con las credenciales deseadas en la base de datos
3. Inicie con el comando `docker-compose up -d --build`
4. Si no ha cambiado los parámetros de start.sh, por defecto el sitio se despliega en localhost:5000
