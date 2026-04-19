## Pipeline CI/CD (Simulado)

El pipeline se diseñó siguiendo la arquitectura de AWS:

1. Origen:
El código fuente se almacena en GitHub.

2. Construcción (CodeBuild):
El archivo buildspec.yml define las fases de instalación y construcción de la aplicación.

3. Despliegue (CodeDeploy):
El archivo appspec.yml define cómo se despliega la aplicación.

4. Ejecución:
La aplicación se ejecuta localmente para validar el despliegue.