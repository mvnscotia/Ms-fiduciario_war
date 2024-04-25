# Deploy WAR para despliegue en wildfly

Proyecto usado para crear el WAR de despliegue en wildfly tomando como base el proyecto generado en react.

Para crear el WAR debes primero haber realizado el "build" de tu proyecto de react, tomaras todo lo que este en la carpeta "build" dentro del root del proyecto
lo colocaras en la carpeta src/main/webapp, una vez realido esto, generaras el WAR:


## Deployment

To deploy this project run

```bash
  mvn install
```
o donde quiera que tengas tu instalación de maven el WAR generado estara en la carpeta target

