# AQUA_INT + Mindden Flow · Presentación a Veolia

Presentación HTML/CSS/JS sin dependencias de build, pensada para mostrar a
Idrica la propuesta de valor de implantar **AQUA_INT** (capa de ingesta y
modelo de dominio agua) y **Mindden Flow** (capa de process mining e IA en
español) como evolución de su forma actual de implantar.

## Cómo abrirla

```bash
# opción 1 · doble clic sobre index.html
# opción 2 · servir en local para tener URL limpia
python3 -m http.server 8000
# abrir http://localhost:8000
```

## Navegación

| Acción | Tecla |
|---|---|
| Avanzar | `↓` · `→` · `espacio` · `PageDown` |
| Retroceder | `↑` · `←` · `PageUp` |
| Ir al inicio / final | `Home` · `End` |
| Pantalla completa | `F` |
| Saltar a slide | clic en los puntos laterales |

## Estructura

```
.
├── index.html          # 13 slides (hero → contexto → 7 pilares → numbers → resumen → cierre)
├── css/style.css       # tema dark, mockups del producto, animaciones, navegación
├── js/presentation.js  # navegación teclado, reveal on scroll, contador, micro-interacciones
├── img/                # capturas reales del producto
└── video/              # vídeo demo
```

## Stack

- HTML5 estático + Tailwind CSS vía CDN
- Iconos [Lucide](https://lucide.dev/) inline
- Fuente Inter (Google Fonts)
- Sin build, sin paquetes, sin runtime servidor — abre directamente en cualquier navegador moderno

## Contenido

13 diapositivas que cubren:

1. **Hero** · de mover datos a entender procesos
2. **Contexto** · las tres deudas de la forma actual de implantar
3. **Arquitectura** · cliente → AQUA_INT → Mindden Flow → negocio
4-10. **Siete pilares** · onboarding · visibilidad · diagnóstico · simulación · IA en español · implantación GoAigua · KPIs sin BI paralelo
11. **Big numbers** · cifras de lo ya construido
12. **Resumen por audiencia** · equipo técnico · comercial · PMO
13. **Cierre** · sesión técnica de 90 min sin compromiso

Cada slide se abre con el contraste *"así se hace hoy"* vs *"así pasa con nosotros"*, sin nombrar tecnologías de terceros.
