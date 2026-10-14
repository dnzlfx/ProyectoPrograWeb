# Ti-Bikersz — Proyecto de Programación Web

Sitio web estático para una tienda de motocicletas (**Ti-Bikersz**), desarrollado
como proyecto final de la asignatura *Programación Web I* de la carrera de
Ingeniería en Tecnologías de la Información (Universidad Politécnica de San
Luis Potosí).

## Secciones

El sitio es multipágina; cada carpeta contiene su propio HTML, CSS y scripts:

| Sección | Contenido |
|---------|-----------|
| `index.html` | Inicio con carrusel de modelos y formulario de cotización |
| `modelos/` | Catálogo de modelos de moto |
| `nosotros/` | Información de la empresa |
| `colaboradores/` | Colaboradores |
| `accesorios/` | Accesorios (con galerías de imágenes) |
| `catalogo/` | Catálogo |
| `blog/` | Blog |
| `contacto/` | Formulario y datos de contacto |

## Funcionalidad destacada

- **Carrusel automático** de imágenes que rota cada 3 segundos (`script.js`).
- **Cotizador**: al enviar el formulario calcula el total según el modelo
  (Moto Eléctrica Urbana, Moto Cross 250cc, Moto Deportiva 600cc) y la cantidad,
  mostrando el importe en pesos.
- **Generación de PDF** de la cotización del lado del cliente con jsPDF
  (cargado por CDN).
- Chat de atención al cliente **Landbot** embebido.
- Páginas responsive con hojas de estilo por sección.

## Estructura

```
index.html                  Página de inicio
style.css                   Estilos globales
script.js                   Carrusel y lógica de cotización
modelos/  nosotros/  colaboradores/  accesorios/  catalogo/  blog/  contacto/
motos/  imagenes/  imagenes2/        Recursos gráficos
zzzDocumentosWordPDFETC/    Documentación de entrega (docx / pdf)
```

## Ejecutar

Sitio 100% estático: abre `index.html` en el navegador o sírvelo con cualquier
servidor de archivos estáticos.

## Tecnologías

HTML5, CSS3, JavaScript (DOM, formularios), jsPDF, Landbot.

## Licencia

MIT — ver [LICENSE](LICENSE).
