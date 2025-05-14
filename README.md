# AWS CloudTrail – Registro básico de eventos

Este laboratorio se centra en configurar un trail básico con CloudTrail para registrar eventos de administración en una cuenta de AWS. El objetivo es verificar que los registros se almacenen correctamente en un bucket S3, dejando evidencia de las acciones realizadas dentro del entorno.

Es parte de una serie de ejercicios prácticos orientados a entender cómo auditar accesos, detectar movimientos sensibles y tener mayor visibilidad sobre lo que ocurre en la cuenta, algo esencial cuando se trabaja con recursos en la nube.


---

## Servicios y herramientas utilizadas

- **AWS CloudTrail** – Servicio de registro y auditoría de acciones
- **Amazon S3** – Almacenamiento de logs generados por el trail
- **AWS CLI** – Validación de logs desde la terminal
- **Linux/WSL2** – Entorno de desarrollo con Ubuntu
- **Git + GitHub** – Control de versiones y documentación

---

## Estructura del proyecto

```plaintext
aws-cloudtrail-basico/
├── screenshots/
│   ├── 01-estructura-inicial.png
│   ├── 02-configurar-cloudtrail-basico.png
│   ├── 03-eventos-administracion-habilitados.png
│   ├── 04-trail-creado-exitosamente.png
│   └── 05-verificar-logs-generados.png
└── README.md
```

---

## Pasos realizados

1. Crear estructura de carpetas local para el laboratorio.
2. Configurar un trail en CloudTrail, eligiendo:
   - Registro de eventos de administración.
   - Actividad de lectura y escritura.
   - Crear un nuevo bucket S3 para almacenar los logs.
3. Validar que el trail se creó correctamente en la consola de CloudTrail.
4. Verificar que los logs se estén generando correctamente usando `aws s3 ls`.
5. Documentar el proceso con capturas y subirlo a GitHub.

---

## Capturas del proceso

### 1️⃣ Estructura inicial del proyecto local
![Estructura inicial](screenshots/01-estructura-inicial.png)

### 2️⃣ Configuración del trail básico en CloudTrail
![Configurar CloudTrail](screenshots/02-configurar-cloudtrail-basico.png)

### 3️⃣ Eventos de administración habilitados
![Eventos de administración](screenshots/03-eventos-administracion-habilitados.png)

### 4️⃣ Trail creado exitosamente en consola
![Trail creado](screenshots/04-trail-creado-exitosamente.png)

### 5️⃣ Verificación de logs generados en el bucket S3
![Verificar logs](screenshots/05-verificar-logs-generados.png)


---

## Contacto: [sebastian.cardenas.t@gmail.com](mailto:sebastian.cardenas.t@gmail.com)
