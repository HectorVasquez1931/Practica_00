# Práctica 0: Uso de Repositorios  

**Alumno:** Hector Alfredo Vasquez Carpio  
**Profesor:** Carlos Gallegos  
**Fecha:** 10/09/2025  
**Materia:** Prácticas  

---

## Introducción  

El propósito de esta práctica es familiarizarnos con el uso de **Markdown**, **Git** y **GitHub**, así como con la creación de repositorios.  

Estas herramientas son fundamentales en el desarrollo profesional de software ya que permiten documentar, versionar y publicar proyectos de manera ordenada y colaborativa.  

---

## Desarrollo  

### 1. Markdown

**Markdown** es un lenguaje de marcado ligero que permite dar formato a texto de forma sencilla.  
Su sintaxis se basa en símbolos que representan títulos, listas, enlaces, imágenes y código.  

**Ejemplos de sintaxis en Markdown:**  

- `# Título` → Título grande
- `**negritas**` → **negritas**  
- `*cursiva*` → *cursiva*  
- `[enlace](https://github.com)` → [enlace](https://github.com)  
- ``` `código` ``` → `código`  

Markdown se utiliza principalmente en **documentación de proyectos** y archivos `README.md` en repositorios.  

#### Ejercicios en clase  
En clase practicamos diferentes elementos de Markdown. A continuación, se muestra el código que realizamos:  

```md
<!-- Comentario -->

# Encabezado 1

## Encabezado 2

### Encabezado 3

#### Encabezado 4

___

a __texto negrita__

a *italica 2010*

___

Imagen con tooltip y link
[![One piece](download.png)](https://www.google.com/search?q=siglas+html "One piece")

___

Tabla

| dias | meses | anios |
| - | - | - |
| Lunes| Enero | 10000000 |
| Miercoles | Febrero | 1990 |
| Viernes | Noviembre | 2004|

___

Lista

- [ ] tarea 1
- [x] tarea 3

___

Codigo en C

```c
#include <stdio.h>
int main()
{
    int x = 123;

    for(int i = 0; i<123)
}

---
```

### 2. Git y GitHub

**Git** es un sistema de control de versiones que permite llevar un historial de cambios en los proyectos.  
**GitHub** es una plataforma en la nube que almacena repositorios Git y facilita la colaboración entre desarrolladores.  

**Comandos esenciales de Git:**

```bash
git init                # Inicializar un repositorio
git status              # Ver el estado del repositorio
git add .               # Añadir archivos al área de preparación
git commit -m "mensaje" # Confirmar cambios
git remote add origin URL_REPO  # Enlazar con repositorio remoto
git push origin main    # Subir cambios a GitHub
git pull origin main    # Descargar cambios desde GitHub
