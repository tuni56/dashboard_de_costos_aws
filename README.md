# 🚀 Dashboard de Costos en AWS

Este proyecto provee un **template automatizado** para desplegar la infraestructura necesaria para procesar y visualizar reportes de costos en AWS.  
El enfoque está en **automatización, consistencia y mínimos privilegios**.

---

## 🎯 Objetivo

Automatizar el despliegue de los componentes principales de la solución:

- **Amazon S3 Bucket** para almacenar los reportes de uso y costos (AWS CUR).
- **IAM Role** con permisos mínimos para que Lambda procese datos y publique métricas en CloudWatch.
- **AWS Lambda Function** que transforma y procesa los reportes.
- **Eventos S3 → Lambda** para disparar el procesamiento automáticamente.

Este template es un **punto de partida flexible** que puedes adaptar a tus necesidades.

---

## 🛠️ Componentes principales

1. **Amazon S3 Bucket**  
   Almacena los reportes de uso y costos de AWS (Cost and Usage Report).

2. **IAM Role con permisos mínimos**  
   Permite que la función Lambda lea los datos del bucket y publique métricas en CloudWatch.

3. **AWS Lambda Function**  
   Procesa automáticamente los reportes cuando se suben al bucket.

4. **Regla de evento S3**  
   Configura la invocación automática de la Lambda al detectar nuevos archivos.

---

## ✅ Próximos pasos

- Personalizar el template según tu cuenta y región de AWS.  
- Implementar métricas clave en CloudWatch para el monitoreo de costos.  
- (Opcional) Integrar con **AWS Budgets + SNS** para alertas automáticas.

---

## 📖 Recursos útiles

- [AWS Cost and Usage Reports](https://docs.aws.amazon.com/cur/latest/userguide/what-is-cur.html)  
- [AWS Lambda Documentation](https://docs.aws.amazon.com/lambda/latest/dg/welcome.html)  
- [Amazon CloudWatch Metrics](https://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/working_with_metrics.html)

---

## ⭐ Apoya este proyecto

Si este template te fue útil, por favor apóyalo con una **estrella en GitHub**.  
Cada estrella ayuda a que más personas descubran la solución y motiva la mejora continua.  

---

### 😎 Bonus  
¿Te gustó lo que viste?  
Entonces haz lo tuyo y deja una **estrella en GitHub** ⭐.  
Más estrellas = más features.
## 🤝 Colaboraciones y contacto

Este proyecto es **open source** y se encuentra en constante evolución.  
Si quieres contribuir:  
- Haz un **fork** del repositorio  
- Crea tu rama (`git checkout -b feature/nueva-funcionalidad`)  
- Envía un **pull request**  

Cualquier idea, issue o mejora es bienvenida.  

📬 **Contacto**  
- LinkedIn: https://www.linkedin.com/in/rociobaigorria/?locale=es_ES  
- Email: tunidev56@gmail.com  

---

## 📜 Licencia

Este proyecto está bajo la licencia **MIT**.  
Eres libre de usarlo, modificarlo y distribuirlo, siempre que se mantenga la atribución original.

