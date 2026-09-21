# markdown# Proyecto de Demostración Markdown

Bienvenido a la documentación principal del repositorio. En este documento se aplican los elementos estándar de la sintaxis Markdown.

---

## 1. Formato de Texto


* **Texto en negrita**
* *Texto en cursiva*
* ***Texto en negrita y cursiva***
* ~~Texto tachado~~
* Formato `inline code` para comandos o variables.

---

## 2. Citas en Bloque

> "Markdown te permite escribir de forma fácil y legible, convirtiéndose de manera directa a HTML estructurado."
>
> — John Gruber

---


## 3. Listas

### Lista ordenada (pasos de instalación):
1. Clonar el repositorio.
2. Acceder al directorio de trabajo.
3. Abrir los archivos `.md` en el editor preferido.

### Lista desordenada (características):
* Soporte universal en plataformas web.
* Sintaxis limpia y minimalista.
* Renderizado automático en GitHub.

### Lista de verificación (tareas):
- [x] Crear el repositorio en GitHub.
- [x] Subir el archivo `README.md`.
- [x] Crear el directorio `images/` y subir un archivo.
- [ ] Ampliar la documentación en futuras versiones.

---
## 4. Imagen
[IES Maria Enriquez]: https://portal.edu.gva.es/mariaenriquez/
![IES Maria Enriquez](images/maria-enriquez-gandia-Rlo3JcVQWU7dhRKRGsYvHzH-1248x770@Las%20Provincias.jpg)

## . Bloques de Código

Fragmento de código en Python:

```python
def saludar(nombre: str) -> str:
    """Devuelve un saludo formateado."""
    return f"Hola, {nombre}! Bienvenido al repositorio."

print(saludar("desarrollador"))

