<div align="center">

# 🏭 Simulaciones RobotStudio

### *Simulaciones industriales de soldadura robotizada con ABB*

[![RobotStudio](https://img.shields.io/badge/Software-RobotStudio-FF6F00?style=for-the-badge)](https://new.abb.com/products/robotics/robotstudio)
[![ABB](https://img.shields.io/badge/Robot-IRB2600ID-CC0000?style=for-the-badge)](https://new.abb.com/products/robotics/industrial-robots/irb-2600)
[![Soldadura](https://img.shields.io/badge/Proceso-Soldadura_Robotizada-1a1a2e?style=for-the-badge)]()
[![Prácticas](https://img.shields.io/badge/Contexto-Prácticas_Curriculares-0077B6?style=for-the-badge)]()

> **Prácticas Curriculares** · Sector de Automatización Industrial · Ingeniería Robótica · 2025

</div>

---

## 🏭 ¿Qué contiene este repositorio?

Simulaciones de **soldadura robotizada industrial** desarrolladas con **ABB RobotStudio** durante las prácticas curriculares del Grado en Ingeniería Robótica, en una empresa del sector de la automatización industrial.

Los proyectos replican condiciones y requerimientos reales de producción: geometrías complejas, coordinación multirobot y optimización de tiempos de ciclo.

> ⚠️ Los archivos de simulación pertenecen a la empresa. Este repositorio recoge únicamente las descripciones técnicas de los proyectos realizados.

---

## 🔬 Simulaciones Realizadas

### 1 — Soldadura de Valla Convencional

Simulación completa de la soldadura de una valla, incluyendo todos sus componentes estructurales: barrotes, cuatro patas, elementos laterales, chapa central y cierre perimetral.

| Elemento | Detalle |
|----------|---------|
| Software | ABB RobotStudio |
| Robot | IRB 2600ID |
| Periférico | Volteador IRBP K600 L1200 3150 |
| Proceso | Soldadura MIG/MAG robotizada |

<div align="center">

[![Soldadura Valla](https://img.youtube.com/vi/7JAz_CPhBUo/maxresdefault.jpg)](https://www.youtube.com/watch?v=7JAz_CPhBUo)

</div>

---

### 2 — Soldadura de Pieza Personalizada con Doble Robot

Coordinación de dos robots para soldar una pieza de geometría personalizada en el menor tiempo posible, minimizando los tiempos muertos de cada robot.

| Elemento | Detalle |
|----------|---------|
| Software | ABB RobotStudio |
| Robots | 2 × IRB 2600ID (seleccionado por mayor alcance frente a IRB 1660ID) |
| Objetivo | Minimizar tiempo de ciclo total |
| Reto principal | Coordinación eficiente sin tiempos de espera |

**Proceso de selección del robot:** se evaluaron dos modelos (IRB 1660ID vs IRB 2600ID). Tras pruebas de alcance con la geometría real de la pieza, se optó por el IRB 2600ID al cubrir todas las zonas de soldadura sin reposicionamientos adicionales.

<div align="center">

[![Pieza Personalizada Doble Robot](https://img.youtube.com/vi/UKq3S805BGg/maxresdefault.jpg)](https://www.youtube.com/watch?v=UKq3S805BGg)

</div>

---

## 🛠️ Tecnologías

- **ABB RobotStudio** — programación offline y simulación
- **RAPID** — lenguaje de programación del robot
- Volteadores y posicionadores para acceso a geometrías complejas
- Coordinación multirobot con sincronización de trayectorias

---

## 📚 Contexto

**Tipo:** Prácticas Curriculares · Grado en Ingeniería Robótica  
**Sector:** Automatización industrial · Soldadura robotizada  
**Autor:** Nicolás Fernández Blánquez  
**Año:** 2025

---

<div align="center">

_Simulaciones desarrolladas sobre requerimientos reales de producción industrial._

</div>
