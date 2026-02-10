# Práctica de Integración Continua con GitHub Actions Jostin Wilmer Perez

Este proyecto fue desarrollado como parte de la asignatura **Electiva 2** y demuestra la implementación de **Integración Continua (CI)** utilizando **GitHub Actions**.

Cada vez que se realiza un push a la rama **main**, se envía una notificación automática al canal **ntfy.sh/devops-itla**.

---

## 📌 Descripción del Proyecto

El proyecto consiste en un programa sencillo en JavaScript que imprime un mensaje de bienvenida en consola.  
Además, se configuró un workflow de GitHub Actions para notificar automáticamente los cambios realizados en el repositorio.

---

## ⚙️ Funcionamiento

Cuando se hace un push a la rama `main`:

1. GitHub Actions detecta el cambio
2. Se ejecuta el workflow configurado
3. Se envía una notificación con los detalles del push a **ntfy.sh**

---

## 🛠️ Tecnologías Utilizadas

- JavaScript
- GitHub Actions
- ntfy.sh

---

## 🔔 Notificaciones

Las notificaciones pueden verse en el siguiente enlace:

👉 https://ntfy.sh/devops-itla
