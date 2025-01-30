# Contribuir al Proyecto

Antes que nada... ¡gracias por tu interés en contribuir a este proyecto! 🎉

Para asegurarnos de mantener un flujo de trabajo organizado y eficiente, 
sigue estas normas básicas al sugerir un cambio mediante un **Pull Request (PR)**.

---

## 📌 Requisitos Previos

Antes de enviar un PR, asegúrate de que:

- Has hecho un **fork** del repositorio y has clonado tu copia localmente.
- Estás trabajando en una **rama nueva** basada en `main` o la rama principal `ifcd65`.
- Sigues el estilo de código del proyecto.
- Tu cambio está bien documentado y probado si aplica.

---

## 🚀 Pasos para Sugerir un Cambio

### 1️⃣ Clona el repositorio y crea una rama nueva

Si aún no tienes el repositorio clonado, hazlo con:
```bash
 git clone https://github.com/tu_usuario/repo.git
 cd repo
```

Crea una nueva rama con un nombre descriptivo:
```bash
 git checkout -b feature-nueva-funcionalidad
```

### 2️⃣ Realiza los cambios y confírmalos

Edita los archivos necesarios y una vez que estés listo, agrega y confirma los cambios:

```bash
 git add .
 git commit -m "Añadida nueva funcionalidad X"
```

### 3️⃣ Sube tu rama al repositorio remoto

```bash
 git push origin feature-nueva-funcionalidad
```

### 4️⃣ Abre un Pull Request

0. Haz un fork de este repositorio:

<img width="146" alt="image" src="https://github.com/cesarlpb/learn-github/assets/164490009/1c66c81e-4a62-4f31-aa64-39c287afd0ce">

1. Ve a la página de tu fork en GitHub.
2. Haz clic en **"Comparar & pull request"**.
3. Escribe un título claro y una descripción detallada del cambio.
4. Asegúrate de que el PR esté dirigido a la rama correcta (`main` o la que corresponda).
5. Envía el PR.

### 5️⃣ Revisión y Feedback

- El equipo revisará tu PR y puede sugerir cambios.
- Realiza los cambios solicitados y vuelve a hacer `git push` a la misma rama.
- Una vez aprobado, tu PR será fusionado al código principal.

---

## ✅ Buenas Prácticas

✔ Usa nombres de rama descriptivos (ej. `fix-bug-login`, `feature-mejoras-ui`).
✔ Escribe mensajes de commit claros y concisos.
✔ Mantén tus cambios enfocados en un solo propósito.
✔ Si el PR cierra un issue, usa `Closes #número_issue` en la descripción del PR.
✔ Respeta las normas del proyecto y el código de conducta.

Gracias por contribuir 🎉
