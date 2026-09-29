<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=220&section=header&text=Jeancarlo%20Alzate&fontSize=52&fontColor=ffffff&fontAlignY=38&desc=Apps%20m%C3%B3viles%20nativas%20%C2%B7%20Backend%20en%20tiempo%20real%20%C2%B7%20Alerta%20s%C3%ADsmica&descAlignY=60&descSize=16" width="100%" alt="Banner"/>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=18&pause=1500&color=36BCF7&center=true&vCenter=true&width=700&lines=Construyo+sistemas+de+alerta+s%C3%ADsmica+para+Colombia;Visi%C3%B3n+computacional+sobre+trazas+de+ondas;Swift+%C2%B7+Kotlin+%C2%B7+Node.js+%C2%B7+Firestore" alt="Typing SVG"/>
</p>

<p align="center">
  <a href="https://www.jeancarlo.space/es"><img src="https://img.shields.io/badge/PORTAFOLIO-0F2027?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Portafolio"/></a>
  <a href="https://www.linkedin.com/in/jeancarlo-alzate-58478a310/"><img src="https://img.shields.io/badge/LINKEDIN-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:jeancarlo.alzate12@gmail.com"><img src="https://img.shields.io/badge/EMAIL-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
</p>

---

## Sobre mí

<table>
<tr>
<td width="60%" valign="top">

Desarrollo aplicaciones móviles en **Swift** y **Kotlin** y servicios backend en **Node.js**.

Mi proyecto principal es **SismoAlerta**: un sistema de alerta sísmica para Colombia que detecta eventos con **visión computacional sobre trazas de ondas** y valida cada alerta contra el catálogo oficial del **Servicio Geológico Colombiano (SGC)**.

Me interesa la ingeniería que se puede medir: backtesting, métricas y decisiones respaldadas por datos.

</td>
<td width="40%" valign="top">

| | |
|---|---|
| **Ubicación** | Colombia |
| **Enfoque** | Móvil · Backend · Datos |
| **Ahora** | Subir la precisión del detector |
| **Aprendiendo** | Arquitectura de software y cloud |

</td>
</tr>
</table>

---

## Caso de estudio: SismoAlerta

> Sistema de alerta sísmica para Colombia: app iOS, backend y worker de detección en producción. Código en repositorios privados; el detalle está en mi [portafolio](https://www.jeancarlo.space/es).

<table>
<tr>
<td width="33%" valign="top">

**Detección**

Visión computacional sobre trazas de ondas de estaciones sismológicas.

</td>
<td width="33%" valign="top">

**Validación**

Cada alerta se contrasta con el catálogo SGC, separando verdaderos positivos y falsos negativos.

</td>
<td width="33%" valign="top">

**Despliegue**

Worker en Render en *Shadow Mode*: registra alertas sin notificar, evitando falsas alarmas al público.

</td>
</tr>
</table>

```mermaid
flowchart LR
    A[Trazas de estaciones] --> B[Detección por<br/>visión computacional]
    B --> C[Worker en Render<br/>Shadow Mode]
    C --> D[(Firestore<br/>alertas preliminares)]
    D --> E[Backtest vs<br/>catálogo SGC]
    D -.-> F[App iOS<br/>push públicos: próximamente]
```

**Estado:** en validación. El siguiente hito es aumentar la precisión antes de habilitar notificaciones push públicas.

---

## Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=swift,kotlin,nodejs,js,firebase,androidstudio,xcode,git,github&theme=dark" alt="Stack"/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Swift-F05138?style=flat-square&logo=swift&logoColor=white"/>
  <img src="https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white"/>
  <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white"/>
  <img src="https://img.shields.io/badge/Firestore-FFCA28?style=flat-square&logo=firebase&logoColor=black"/>
  <img src="https://img.shields.io/badge/Render-46E3B7?style=flat-square&logo=render&logoColor=black"/>
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white"/>
</p>

---

## Proyectos públicos

<table>
<tr>
<td align="center" width="50%">
  <a href="https://github.com/jeancarlo12/LUKA">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=jeancarlo12&repo=LUKA&theme=tokyonight&hide_border=true" alt="LUKA"/>
  </a>
  <br/><sub>Proyecto universitario: simulación de una app bancaria móvil en Kotlin.</sub>
</td>
<td align="center" width="50%">
  <a href="https://github.com/jeancarlo12/Portafolio-Jeancarlo">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=jeancarlo12&repo=Portafolio-Jeancarlo&theme=tokyonight&hide_border=true" alt="Portafolio"/>
  </a>
  <br/><sub>Mi portafolio personal.</sub>
</td>
</tr>
</table>

---

## Contacto

<p align="center">
  Abierto a colaboración en proyectos de alerta temprana, apps móviles y sistemas en tiempo real.<br/><br/>
  <a href="https://www.jeancarlo.space/es"><img src="https://img.shields.io/badge/Ver%20portafolio-36BCF7?style=for-the-badge&logoColor=white"/></a>
  <a href="mailto:jeancarlo.alzate12@gmail.com"><img src="https://img.shields.io/badge/Escr%C3%ADbeme-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/></a>
</p>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2c5364,100:0f2027&height=100&section=footer" width="100%" alt="Footer"/>
