# Sistema de Verificación de Inscripción de Cursos con Tau Prolog

Este proyecto permite verificar si un **alumno** 
puede inscribir un curso en función de los **prerrequisitos** 
que haya aprobado, utilizando **Tau Prolog** directamente en el navegador.

---

## Requisitos

- Tener un navegador web moderno (Chrome, Firefox, Edge, etc.).
- Tener instalado **Git** en tu computadora.
- Una cuenta en [GitHub](https://github.com).

---

## Archivos principales del proyecto

- `Alumno-Docente.html` → Interfaz principal del sistema (abre este archivo en el navegador).
- `tau-prolog.js` → Intérprete de Prolog en JavaScript.
- `README.md` → Documento con instrucciones (este archivo).

---

## Cómo subir el proyecto a GitHub

### 1. Crear un repositorio en GitHub
1. Ingresa a tu cuenta de GitHub.
2. Haz clic en **New Repository**.
3. Coloca un nombre, por ejemplo:  
   ```
   PrimeraActividad-Prolog
   ```
4. Elige que sea público o privado. "en ese caso se uso el publico"
5. Da clic en **Create repository**.

---

### 2. Subir la carpeta del proyecto desde tu computadora

Abre la **terminal** en la carpeta donde guardaste los archivos (`Alumno-Docente.html`, `tau-prolog.js`, `README.md`) y ejecuta:

```bash
# Inicializar git en la carpeta del proyecto
git init

# Conectar con tu repositorio en GitHub
git remote add origin https://github.com/briantarias/PrimeraActividad-Prolog.git

# Agregar todos los archivos del proyecto
git add .

# Confirmar los cambios
git commit -m "Primer commit - sistema de inscripción con Tau Prolog"

# Subir los archivos al repositorio en la rama principal
git branch -M main
git push -u origin main
```

---

### 3. Verificar en GitHub
- Abre tu repositorio en GitHub.
- Deberías ver los archivos:
  - `Alumno-Docente.html`
  - `tau-prolog.js`
  - `README.md`

---

## Ejecución del proyecto

1. Descarga el repositorio o clónalo:
   ```bash
   git clone https://github.com/TU-USUARIO/sistema-inscripcion-prolog.git
   cd sistema-inscripcion-prolog
   ```

2. Abre `Alumno-Docente.html` en tu navegador (doble clic o clic derecho → abrir con navegador).

3. Selecciona un **alumno** y una **materia**, luego haz clic en **"Verificar Elegibilidad"**.

4. El sistema mostrará si el alumno cumple los requisitos o qué cursos le faltan.

---

## Ejemplo de uso

- Alumno: **Pedro**  
- Materia: **Bases de Datos I**  
- Resultado: NO. Falta el prerrequisito **Estructuras de Datos**.

---

## Notas

- El proyecto utiliza [Tau Prolog](http://tau-prolog.org/) 

---

## Autor

Proyecto desarrollado por **[Briant Arias]**