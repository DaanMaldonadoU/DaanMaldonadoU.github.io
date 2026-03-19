---
jupytext:
  formats: md:myst
  text_representation:
    extension: .md
    format_name: myst
    format_version: 0.13
    jupytext_version: 1.11.5
kernelspec:
  display_name: Python 3
  language: python
  name: python3
---

# Ejecución de códigos

Los capítulos de este libro contienen celdas de código interactivas que pueden ejecutarse directamente en el navegador. Para utilizarlas, siga los siguientes pasos:

1. Haga clic en el ícono 🚀 ubicado en la parte superior de la página.
2. Seleccione la opción **Live Code**.
3. Espere a que el entorno se inicialice (puede tardar 1-2 minutos la primera vez).
4. Ejecute las celdas **en orden secuencial**, de arriba hacia abajo, usando el botón *run* de cada celda.

```{warning}
Cada celda puede depender de variables definidas en celdas anteriores. Si obtiene un error de tipo `NameError` (variable no definida), asegúrese de haber ejecutado **todas las celdas previas** en orden. En particular, la primera celda de código de cada capítulo importa las bibliotecas necesarias y genera los datos iniciales; esta celda **debe ejecutarse siempre primero**.
```

```{note}
Si desea modificar algún parámetro del código, primero ejecute todas las celdas anteriores, luego realice sus modificaciones y ejecute la celda correspondiente. Algunas celdas posteriores podrían necesitar ejecutarse nuevamente para reflejar los cambios.
```
