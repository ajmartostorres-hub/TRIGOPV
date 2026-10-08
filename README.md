[readme_md.md](https://github.com/user-attachments/files/33187638/readme_md.md)
# TrigoPV — Dimensionado y Análisis de Instalaciones Fotovoltaicas

[![Última Versión](https://img.shields.io/github/v/release/ajmartostorres-hub/TRIGOPV?style=flat-square&color=blue)](https://github.com/ajmartostorres-hub/TRIGOPV/releases)
[![Descargar Executable](https://img.shields.io/badge/Descargar-.exe-brightgreen?style=flat-square&logo=windows)](https://github.com/ajmartostorres-hub/TRIGOPV/releases)
[![Licencia](https://img.shields.io/badge/License-GPLv3-blue.svg?style=flat-square)](LICENSE)
[![Python](https://img.shields.io/badge/GUI-PySide6%20%2F%20Qt6-green.svg?style=flat-square)](https://pyside.org)

**TrigoPV** es una aplicación de escritorio para **Windows** diseñada para la simulación, dimensionado y análisis técnico-económico de instalaciones solares fotovoltaicas.

Combina la precisión de la API oficial de **PVGIS (European Commission Joint Research Centre)** con mapas interactivos de **MapLibre GL** y **Nominatim** para ofrecer una herramienta integral de cálculo de autoconsumo y producción energética sin necesidad de configuraciones avanzadas ni entornos de programación.

---

## 📥 Descarga e Instalación (.exe)

No necesitas instalar Python ni configurar dependencias. Puedes ejecutar **TrigoPV** directamente en tu equipo Windows:

1. **Accede a las versiones oficiales:**
   Dirígete a la sección de [**Lanzamientos / Releases**](https://github.com/ajmartostorres-hub/TRIGOPV/releases).

2. **Descarga el ejecutable:**
   Obtén la última versión del archivo `TrigoPV.exe` (o el paquete `.zip` correspondiente).

3. **Ejecuta la aplicación:**
   Haz doble clic sobre `TrigoPV.exe` para iniciar el programa de forma directa.

---

## 🛡️ Nota sobre la advertencia de Microsoft Defender SmartScreen

Al ejecutar un archivo `.exe` descargado de GitHub que no cuenta con un certificado digital comercial de pago, es normal que Windows muestre la advertencia *"Windows protegió su PC"*.

### ¿Cómo omitir esta advertencia?

1. Haz clic en el enlace **"Más información"** (*More info*) en la ventana flotante de SmartScreen.
2. Haz clic en el botón **"Ejecutar de todos modos"** (*Run anyway*).
3. La aplicación se abrirá con normalidad.


---

## ✨ Características Principales

* **Recurso Solar con PVGIS v5.3:** Cálculo directo de perfiles de radiación global, directa, difusa y generación esperada ($kWh/kWp$).
* **Curvas de Consumo Real:** Compatibilidad con archivos de lectura horaria `.csv` de distribuidoras eléctricas y perfiles estándar.
* **Mapas Interactivos Integrados:** Buscador geográfico e interacción fluida utilizando MapLibre GL, OpenFreeMap y la API de Nominatim vía puente bidireccional `QWebChannel`.
* **Gráficas e Indicadores Clave:** Visualización gráfica de balances energéticos, excedentes, demanda de red y grados de autoconsumo.
* **Gestión de Proyectos:** Guardado y lectura de simulaciones en archivos estructurados `.json`.

---

## 💻 Requisitos del Sistema

* **Sistema Operativo:** Windows 10, Windows 11 (64-bit).
* **Conexión a Internet:** Necesaria para cargar las capas del mapa interactivo y realizar las consultas en tiempo real a la API de PVGIS.
* **Espacio libre en disco:** ~150 MB.

---

## 🛠️ Tecnologías Internas

* **GUI & Lógica:** Python 3 + PySide6 (Qt6 for Python)
* **Mapas & Geocodificación:** MapLibre GL JS + OpenFreeMap + Nominatim API + `QWebChannel`
* **Servicio Fotovoltaico:** PVGIS REST API (European Commission JRC)

---

## 📜 Licencia y Créditos

* **Licencia:** Distribuido bajo la licencia **GNU General Public License v3.0 o posterior (GPLv3+)**.
* **Autor:** Alfonso José Martos Torres ([@ajmt_00](https://github.com/ajmt_00))
* **Repositorio oficial:** [ajmartostorres-hub/TRIGOPV](https://github.com/ajmartostorres-hub/TRIGOPV)
