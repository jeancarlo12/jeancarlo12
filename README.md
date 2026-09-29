<!-- Banner -->
<h1 align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=200&section=header&text=Jeancarlo&fontSize=60&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Desarrollador%20de%20software%20%C2%B7%20Colombia%20%F0%9F%87%A8%F0%9F%87%B4&descAlignY=58&descSize=18" alt="Banner"/>
</h1>

<p align="center">
  <a href="https://github.com/jeancarlo12/SismoAlerta-Backend">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&pause=1200&color=36BCF7&center=true&vCenter=true&width=600&lines=Construyo+sistemas+de+alerta+s%C3%ADsmica+%F0%9F%8C%8B;Apps+m%C3%B3viles+en+Swift+y+Kotlin+%F0%9F%93%B1;Backend+con+Node.js+y+Firestore+%E2%9A%99%EF%B8%8F;Visi%C3%B3n+computacional+aplicada+a+sismolog%C3%ADa+%F0%9F%91%81%EF%B8%8F" alt="Typing SVG" />
  </a>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=jeancarlo12&label=Visitas&color=0e75b6&style=flat" alt="Visitas"/>
  <img src="https://img.shields.io/github/followers/jeancarlo12?style=flat&logo=github&label=Seguidores" alt="Seguidores"/>
  <a href="https://github.com/jeancarlo12?tab=repositories"><img src="https://img.shields.io/badge/Repos-ver%20todos-2ea44f?style=flat&logo=github" alt="Repos"/></a>
</p>

---

## 👨💻 Sobre mí

- 🌎 Desarrollador desde Colombia, enfocado en **apps móviles nativas** y **sistemas backend en tiempo real**.
- 🌋 Actualmente construyo **SismoAlerta**: un sistema de alertas sísmicas para Colombia que detecta eventos con **visión computacional sobre trazas de ondas** de estaciones sismológicas.
- 🎯 Mi foco ahora: **subir la precisión** del detector antes de habilitar notificaciones push públicas.
- 📊 Valido cada alerta contra el **catálogo oficial del SGC** (backtesting con verdaderos positivos y falsos negativos).
- 🌱 Aprendiendo: Arquitectura de software y despliegues en la nube.
- 📫 Contacto: jeancarlo12@ejemplo.com <!-- Recuerda reemplazar por tu correo real -->

---

## ⭐ Proyecto destacado: SismoAlerta

> Sistema de alerta sísmica para Colombia, con app iOS, backend y un worker de detección en producción.

```mermaid
flowchart LR
    A[📡 Trazas de estaciones] --> B[🧠 Detección por visión computacional]
    B --> C[⚙️ Worker en Render<br/>Shadow Mode]
    C --> D[(🔥 Firestore<br/>preliminary_alerts_history)]
    D --> E[📊 Backtest vs catálogo SGC]
    D -.-> F[📱 App iOS<br/>Push públicos: próximamente]
