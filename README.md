<h1 align="center">Jeancarlo Alzate Ramírez</h1>
<p align="center">
  Desarrollador de software · Apps móviles nativas y sistemas backend en tiempo real<br/>
  Colombia
</p>

<p align="center">
  <a href="https://www.jeancarlo.space/es"><img src="https://img.shields.io/badge/Portafolio-jeancarlo.space-0F2027?style=flat-square&logo=googlechrome&logoColor=white" alt="Portafolio"/></a>
  <a href="https://www.linkedin.com/in/jeancarlo-alzate-58478a310/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:jeancarlo.alzate12@gmail.com"><img src="https://img.shields.io/badge/Email-333333?style=flat-square&logo=gmail&logoColor=white" alt="Email"/></a>
</p>

---

## Perfil

Desarrollo aplicaciones móviles en **Swift** y **Kotlin** y servicios backend en **Node.js**. Mi proyecto principal es **SismoAlerta**, un sistema de alerta sísmica para Colombia que detecta eventos mediante **visión computacional sobre trazas de ondas** de estaciones sismológicas y contrasta sus resultados con el catálogo oficial del Servicio Geológico Colombiano (SGC).

Actualmente profundizo en arquitectura de software y despliegues en la nube.

---

## Caso de estudio: SismoAlerta

Sistema de alerta sísmica para Colombia: app iOS, backend y worker de detección en producción. *(Código en repositorios privados; el detalle está en mi [portafolio](https://www.jeancarlo.space/es).)*

**Estado actual:** el detector opera en *Shadow Mode*: genera y registra alertas sin notificar al público. El objetivo es aumentar la precisión antes de habilitar notificaciones push.

```mermaid
flowchart LR
    A[Trazas de estaciones] --> B[Detección por<br/>visión computacional]
    B --> C[Worker en Render<br/>Shadow Mode]
    C --> D[(Firestore<br/>alertas preliminares)]
    D --> E[Backtest vs<br/>catálogo SGC]
    D -.-> F[App iOS<br/>push públicos: próximamente]
```

**Decisiones de ingeniería**
- **Validación con datos:** cada alerta se compara con el catálogo SGC, separando verdaderos positivos y falsos negativos, para medir el detector y no depender de impresiones.
- **Despliegue en modo sombra:** permite evaluar el sistema en producción sin exponer a usuarios a falsas alarmas.
- **Historial persistente** de alertas preliminares para auditoría y análisis posterior.

**Stack:** Swift · Node.js · Firestore · Render

---

## Otros proyectos

| Proyecto | Descripción | Tecnologías |
|---|---|---|
| [LUKA](https://github.com/jeancarlo12/LUKA) | Proyecto universitario: simulación de una aplicación bancaria móvil | Kotlin · Android |
| [Portafolio](https://www.jeancarlo.space/es) | Mi portafolio personal | Web |

---

## Stack

| Área | Tecnologías |
|---|---|
| Móvil | Swift (iOS) · Kotlin (Android) |
| Backend | Node.js · Firestore · Render |
| Calidad de datos | Backtesting propio, análisis con CSV |
| Herramientas | Git · GitHub · Integración de APIs |

<p>
  <img src="https://skillicons.dev/icons?i=swift,kotlin,nodejs,firebase,git,github&theme=dark" alt="Stack"/>
</p>

---

<sub>Abierto a colaboración en proyectos de alerta temprana, apps móviles y sistemas en tiempo real.</sub>
