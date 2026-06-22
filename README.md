# Plan de Mejora — Mantenimiento LHD
## Codelco Chuquicamata Subterránea

Presentación interactiva con temporizador integrado para exposición de 20 minutos (4 bloques de 5 minutos cada uno).

### 📁 Estructura

```
proyecto-lhd/
├── index.html          ← Presentación principal
├── gantt.html          ← Carta Gantt (Anexo A)
├── datos.html          ← Cuaderno de Datos Sistematizados
├── video.mp4           ← Video Sandvik LH517i
├── imagen.avif         ← Foto del equipo
└── README.md           ← Este archivo
```

### 🚀 Uso

#### Local
1. Descarga la carpeta `proyecto-lhd/`
2. Abre `index.html` en tu navegador
3. El temporizador comienza automáticamente

#### GitHub Pages
1. Sube esta carpeta a un repositorio (`https://github.com/usuario/proyecto-lhd`)
2. Ve a **Settings → Pages**
3. Selecciona **Deploy from a branch**
4. Elige `main` o `master`
5. Accede en `https://usuario.github.io/proyecto-lhd`

### ⏱️ Temporizador

- **Total**: 20 minutos (cuenta atrás)
- **Bloques**: 4 × 5 minutos cada uno
  - Bloque 1: Slides 1–5
  - Bloque 2: Slides 6–11
  - Bloque 3: Slides 12–14
  - Bloque 4: Slides 15–19
- **Alertas**: Aviso visual/sonoro a 1 minuto antes de finalizar cada bloque
- **Controles**: Pausa/Reanuda, Reset

### 📋 Bloques de Exposición

| Bloque | Slides | Expositor | Temas |
|--------|--------|-----------|-------|
| 1 | 1–5 | — | Contexto, Diagnóstico, Alternativas |
| 2 | 6–11 | — | Ciclo de Preguntas, Línea Base |
| 3 | 12–14 | — | Evaluación, Plan de Acción |
| 4 | 15–19 | — | Indicadores, Cierre, Sostenibilidad |

### 🔧 Características

✅ Presentación interactiva con navegación por teclado (← →)  
✅ Paneles de FAQ con múltiples categorías (Slide 21)  
✅ Gráficos dinámicos (Chart.js)  
✅ Temporizador con alertas automáticas  
✅ Completamente offline una vez descargado  
✅ Compatible con GitHub Pages  

### 📝 Notas

- Los assets (video, imagen, HTMLs) se cargan bajo demanda
- La presentación funciona sin conexión a internet una vez descargada
- El navegador debe tener JavaScript habilitado
- Recomendado: Chrome, Firefox, Safari (versiones recientes)

---

**Última actualización**: Junio 2026
