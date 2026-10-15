# 🚀💻 Guía de Git y GitHub para el Ciber de las Bermudas 🏴‍☠️

> 🎯 **¡Bienvenidos al centro de operaciones del equipo!**
>
> Este repositorio es nuestro espacio de trabajo colaborativo. Acá vamos a compartir código, desarrollar proyectos y trabajar en equipo. 🤝
>
> ⚠️ **Misión principal:** mantener nuestro trabajo organizado, sincronizado y seguro, evitando sobrescribir los cambios de nuestros compañeros.

---

## ⚙️ 1. Configuración inicial (solo la primera vez)

🛠️ Si es la primera vez que usás Git en tu computadora, configurá tu nombre y correo electrónico. Utilizá el mismo correo asociado a tu cuenta de GitHub.

```bash
git config --global user.name "Tu Nombre"
git config --global user.email "tu_email@ejemplo.com"
```

✅ **¡Listo!** Git ya sabe quién sos y podrá identificar tus contribuciones.

---

## 📥 2. Descargar el proyecto por primera vez

📦 Para obtener una copia del proyecto en tu computadora, ejecutá:

```bash
git clone https://github.com/MatiRodrigo/fabrica.git
```

📁 Esto descargará el repositorio y creará una carpeta llamada `fabrica` en el directorio donde estés trabajando.

### 🪜 Paso a paso

**🔗 Paso 1. Copiar la URL del repositorio**

Entrá al repositorio en GitHub, presioná el botón **Code** y copiá la URL HTTPS.

**💻 Paso 2. Abrir una terminal**

Podés utilizar cualquiera de estas opciones:

- 🪟 CMD o PowerShell en Windows.
- 🐧 Terminal en Linux.
- 🧑‍💻 Terminal integrada de Visual Studio Code.

**🚀 Paso 3. Ejecutar el comando**

Pegá el comando `git clone` en la terminal y presioná **Enter**.

🎉 ¡Perfecto! Ya tenés una copia local del proyecto.

---

## 🔄 3. Flujo de trabajo diario (¡regla de oro!)

🛡️ **Antes de empezar a programar, sincronizá tu proyecto.** Así evitás trabajar con una versión desactualizada del código.

```bash
git checkout main
git pull origin main
```

🔍 ¿Qué hace cada comando?

- `git checkout main` ➡️ Cambia a la rama principal.
- `git pull origin main` ⬇️ Descarga e integra los últimos cambios de GitHub en tu rama local `main`.

⚠️ **Importante:** si tenés cambios locales sin guardar, revisalos antes de sincronizar para evitar conflictos.

---

## 🔎 4. Revisar el estado de tus archivos

Antes de preparar tus cambios, comprobá qué archivos modificaste:

```bash
git status
```

👀 Este comando te permite ver archivos modificados, archivos nuevos y cambios pendientes de confirmar.

---

## 📦 5. Preparar los cambios para el commit

Cuando estés conforme con tu trabajo, prepará los archivos que querés incluir en el próximo commit.

### 📂 Opción A: preparar todos los cambios

```bash
git add .
```

### 📄 Opción B: preparar un archivo específico

```bash
git add archivo.js
```

💡 **Consejo:** si trabajás en equipo, revisá los archivos antes de agregarlos para no incluir configuraciones personales, contraseñas o archivos innecesarios.

---

## 💾 6. Confirmar los cambios (commit)

📝 Un commit es una instantánea de los cambios que preparaste, acompañada de un mensaje que explica qué hiciste.

```bash
git commit -m "Explicación breve de lo que hiciste"
```

✅ Escribí mensajes claros y descriptivos.

**Ejemplos:**

```bash
git commit -m "Agrega formulario de inicio de sesión"
git commit -m "Corrige error en el cálculo de ventas"
git commit -m "Actualiza estilos del menú principal"
```

---

## ☁️ 7. Subir tus cambios a GitHub

📤 Cuando hayas terminado, subí tus cambios a la rama remota correspondiente:

```bash
git push origin nombre-de-tu-rama
```

🔁 Reemplazá `nombre-de-tu-rama` por el nombre de la rama en la que estés trabajando.

Por ejemplo:

```bash
git push origin feature/formulario-login
```

⚠️ **¡Atención!** No trabajes directamente sobre `main` si el equipo utiliza ramas para desarrollar funcionalidades. Antes de subir cambios, asegurate de estar en la rama correcta.

---

## 🧭 8. Resumen rápido de comandos

| 🎯 Acción | 💻 Comando |
|---|---|
| Descargar el proyecto | `git clone URL` |
| Cambiar de rama | `git checkout nombre-rama` |
| Actualizar la rama principal | `git pull origin main` |
| Revisar cambios | `git status` |
| Preparar todos los cambios | `git add .` |
| Preparar un archivo | `git add archivo.js` |
| Confirmar cambios | `git commit -m "Mensaje"` |
| Subir cambios | `git push origin nombre-rama` |

---

## 🏴‍☠️ Reglas de oro del Ciber de las Bermudas

- 🤝 **Trabajá en equipo:** respetá los cambios de tus compañeros.
- 🔄 **Sincronizá antes de empezar:** evitá trabajar con código desactualizado.
- 📝 **Escribí buenos commits:** explicá qué modificaste.
- 🌿 **Usá ramas cuando corresponda:** mantené el trabajo organizado.
- 🔍 **Revisá antes de subir:** comprobá qué archivos vas a compartir.
- 🔐 **Nunca subas contraseñas, tokens ni claves privadas.**

---

# 🚀 ¡A programar, equipo! 💻🔥

**Un buen equipo no solo escribe código: también sabe organizarlo, compartirlo y mantenerlo.** 🤜🤛