# practicaSena1
Documento paso a paso instalación git
# Cómo subir un proyecto a GitHub usando Git Bash y VS Code

## Introducción

Git y GitHub son herramientas fundamentales para el control de versiones y la gestión de proyectos de software. En este documento se explica el proceso paso a paso para subir un proyecto local a GitHub utilizando Git Bash y Visual Studio Code.

---

# Requisitos

Antes de comenzar, es necesario tener instalado:

- Git Bash
- Visual Studio Code
- Una cuenta en GitHub

---

# Paso 1: Crear un repositorio en GitHub

1. Ingresar a GitHub.
2. Hacer clic en **New Repository**.
3. Escribir el nombre del repositorio.
4. Seleccionar si será público o privado.
5. Hacer clic en **Create Repository**.

---

# Paso 2: Abrir el proyecto en VS Code

1. Abrir Visual Studio Code.
2. Seleccionar **File > Open Folder**.
3. Elegir la carpeta del proyecto.

---

# Paso 3: Abrir la terminal de Git Bash

En VS Code abrir la terminal con:

```bash
Ctrl + ñ
```

O desde:

```text
Terminal > New Terminal
```

---

# Paso 4: Inicializar Git en el proyecto

Ejecutar el siguiente comando:

```bash
git init
```

Este comando crea un repositorio Git local.

---

# Paso 5: Verificar el estado de los archivos

```bash
git status
```

Este comando muestra los archivos pendientes por agregar.

---

# Paso 6: Agregar los archivos al repositorio

```bash
git add .
```

El punto (`.`) indica que se agregarán todos los archivos del proyecto.

---

# Paso 7: Crear el primer commit

```bash
git commit -m "Primer commit"
```

El commit guarda los cambios realizados en el proyecto.

---

# Paso 8: Conectar el proyecto con GitHub

Copiar la URL del repositorio de GitHub y ejecutar:

```bash
git remote add origin https://github.com/USUARIO/NOMBRE-REPOSITORIO.git
```

Ejemplo:

```bash
git remote add origin https://github.com/yulianajaramillo/mi-proyecto.git
```

---

# Paso 9: Subir el proyecto a GitHub

```bash
git branch -M main
```

Luego ejecutar:

```bash
git push -u origin main
```

Este comando sube el proyecto al repositorio remoto en GitHub.

---

# Paso 10: Verificar el proyecto en GitHub

1. Ingresar nuevamente al repositorio en GitHub.
2. Actualizar la página.
3. Verificar que los archivos fueron cargados correctamente.

---

# Comandos principales de Git

| Comando | Función |
|---|---|
| `git init` | Inicializa Git en el proyecto |
| `git status` | Muestra el estado de los archivos |
| `git add .` | Agrega todos los archivos |
| `git commit -m "mensaje"` | Guarda cambios |
| `git remote add origin URL` | Conecta con GitHub |
| `git push -u origin main` | Sube archivos a GitHub |

---

# Conclusión

Git y GitHub facilitan el control de versiones y permiten almacenar proyectos de manera segura en la nube. Aprender a utilizar estas herramientas mejora la organización del desarrollo de software y fortalece el trabajo colaborativo.