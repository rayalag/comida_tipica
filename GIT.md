# Comandos de Git

Para clonar un repositorio usamos
```
git clone <url>
```

Para subir un archivo o archivos a nuestro repositorio remoto, seguimos en método ACP

Para verificar que archivos son nuevos o tienen cambios, ejecutamos un comando

``
git status
``
---
### 🚀Paso 01 Flujo ACP (add)
Selecciona que voy a subir

``
git add <nombre_archivo>
``
### 🚀Paso 02 Flujo ACP (add)
Escribimos el comentario con que subirá este archivo git

``
git commit -m "Comentario"
``
### 🚀Paso 03 Flujo ACP (push)
Enviamos los cambios de nuestros repositorios remotos

``
git push origin <rama>
git push origin main

``