# dashboard_de_costos_aws
# Objetivos específicos del template:
El objetivo de este template es automatizar el despliegue de los componentes principales de la solución: el bucket de S3 para los reportes de costos, el rol de IAM con los permisos necesarios, y la función Lambda que procesará los datos.

Este template es un punto de partida que puedes adaptar. Se enfoca en la automatización y la consistencia.

## 1) Crear un Amazon S3 Bucket para almacenar los reportes de uso y costos de AWS (CUR).

## 2) Configurar un rol de IAM con los permisos mínimos necesarios para que la función Lambda pueda leer datos del bucket y publicar métricas en CloudWatch.

## 3) Desplegar una función Lambda que será activada por un evento cuando un nuevo reporte de costos sea subido al bucket S3.

## 4) Configurar una regla de evento S3 para que el bucket invoque la función Lambda.
