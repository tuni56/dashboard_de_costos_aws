# dashboard_de_costos_aws
# Objetivos específicos del template:

Crear un Amazon S3 Bucket para almacenar los reportes de uso y costos de AWS (CUR).

Configurar un rol de IAM con los permisos mínimos necesarios para que la función Lambda pueda leer datos del bucket y publicar métricas en CloudWatch.

Desplegar una función Lambda que será activada por un evento cuando un nuevo reporte de costos sea subido al bucket S3.

Configurar una regla de evento S3 para que el bucket invoque la función Lambda.
