# SUTI — Glosario minero bilingüe

Primera versión funcional de prueba. Aplicación web estática, adaptable a móviles y escritorio, con búsqueda local y soporte PWA/offline.

## Ejecutar localmente

No abras `index.html` directamente. Desde esta carpeta ejecutá:

```bash
python -m http.server 8000
```

Después abrí http://localhost:8000.

## Publicar en GitHub Pages

1. Creá un repositorio público en GitHub.
2. Subí el contenido de esta carpeta a la raíz del repositorio.
3. En Settings → Pages, elegí Deploy from a branch y la rama `main`, carpeta `/ (root)`.
4. Abrí la URL publicada una vez con conexión para que el navegador descargue y almacene los recursos.

## Contenido y limitaciones conocidas

- El glosario incluye los 250 registros de la planilla original.
- Las pronunciaciones son aproximaciones automáticas de lectura para hispanohablantes; requieren revisión lingüística antes de considerarse definitivas.
- La exploración por tareas operativas está visible en la interfaz, pero el índice y las relaciones tarea-término están pendientes de validación. No se inventaron asociaciones.
- La búsqueda del MVP se realiza por términos en inglés, admite coincidencias parciales y prioriza coincidencia exacta, inicio de término y luego coincidencia interna.
- El modo offline requiere una primera carga correcta desde un servidor (por ejemplo, GitHub Pages o localhost). El comportamiento de instalación y almacenamiento depende del navegador y dispositivo.

## Licencias

El código de esta primera versión se publica bajo MIT (ver LICENSE). La tipografía Creato Display se incluye con su licencia SIL Open Font License.
