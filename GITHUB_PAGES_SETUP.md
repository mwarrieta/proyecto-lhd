# Instrucciones para publicar en GitHub Pages

## 1. Crear repositorio en GitHub

```bash
# Abre GitHub → New repository
# Nombre: proyecto-lhd
# Descripción: Plan de Mejora para Mantenimiento LHD — Presentación interactiva
# Tipo: Public
```

## 2. Clonar y subir archivos

```bash
# Clona el repo
git clone https://github.com/TU_USUARIO/proyecto-lhd.git
cd proyecto-lhd

# Copia los archivos de esta carpeta aquí
# (index.html, gantt.html, datos.html, video.mp4, imagen.avif, README.md)

# Sube a GitHub
git add .
git commit -m "Initial commit: presentación con temporizador"
git push -u origin main
```

## 3. Habilitar GitHub Pages

1. Ve a tu repositorio en GitHub
2. Settings → Pages
3. Under "Build and deployment":
   - Source: Deploy from a branch
   - Branch: main, /(root)
4. Click "Save"
5. Espera 1-2 minutos

## 4. Accede a tu presentación

La presentación estará disponible en:
```
https://TU_USUARIO.github.io/proyecto-lhd
```

## 💡 Tips

- Los cambios en GitHub Pages pueden tardar unos segundos en aparecer
- Puedes editar los archivos directamente en GitHub (Settings → Edit in place)
- Si usas un dominio personalizado, actualiza en Settings → Pages → Custom domain
- Los assets (video, imágenes) se cargan bajo demanda → más rápido

---

¿Preguntas? Consult la documentación oficial: https://docs.github.com/en/pages
