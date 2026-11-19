# Guía de Resolución: Laboratorio de Desafíos (Módulo 5)
**Creación de un sitio web dinámico para la cafetería**  
*AWS Academy Cloud Architecting (Spanish LATAM)*

## Descripción general
Este proyecto recoge la documentación completa, paso a paso y verificada (calificación **30/30**), para completar el **Laboratorio de desafíos del Módulo 5** de AWS Academy Cloud Architecting.

El objetivo del laboratorio es desplegar una aplicación web dinámica en **Amazon EC2** con pila **LAMP** (Amazon Linux, Apache en el puerto `8000`, PHP y MariaDB), conectar la aplicación de forma segura a **AWS Secrets Manager** mediante roles de **AWS IAM**, crear una **AMI** del entorno de desarrollo en **Norte de Virginia (`us-east-1`)** y replicar el entorno de producción en **Oregón (`us-west-2`)**, resolviendo los **3 desafíos prácticos** y las **7 preguntas de evaluación**.

Se incluyen **dos versiones de la guía** adaptadas a distintos perfiles de uso, pensadas tanto como material de apoyo para el profesorado como para facilitar el seguimiento autónomo al alumnado.

---

## Acceso directo a las guías

* **[📘 Abrir Versión 1 — Guía Técnica de Referencia](./Guia_Lab5_V1_Tecnica.md)**
* **[🧭 Abrir Versión 2 — Guía Guiada ("A prueba de atascos")](./Guia_Lab5_V2_Paso_a_Paso.md)**

---

## ¿Qué versión de la guía elegir?

| Aspecto | [Versión 1 — Guía Técnica](./Guia_Lab5_V1_Tecnica.md) | [Versión 2 — Guía Guiada](./Guia_Lab5_V2_Paso_a_Paso.md) |
| :--- | :--- | :--- |
| **Perfil ideal** | Profesorado o alumnado con soltura en AWS que busca el solucionario limpio y rápido. | Alumnado haciendo el laboratorio por primera vez sin quedarse bloqueado en ningún paso. |
| **Estilo** | Manual técnico formal, directo al grano y orientado a documentación. | Guía paso a paso cercana, estructurada de forma acompañada y didáctica. |
| **Control de datos** | Los datos aparecen repartidos en el paso donde se utilizan. | Incluye una **hoja de apuntes inicial** (tabla en blanco) para anotar `LabIDEURL`, contraseña, IP de Virginia e IP/DNS de Oregón y tenerlos siempre a mano. |
| **Verificación en cada paso** | Indica la acción a realizar y la captura correspondiente. | Cada paso incluye un bloque **«Cómo saber que vas bien»** con el texto, estado verde o salida exacta que debe aparecer en pantalla antes de continuar. |
| **Resolución de desafíos y errores reales** | Resume el problema y aplica la solución directa. | Explica el porqué técnico paso a paso e incorpora avisos de **«Error típico y cómo arreglarlo»** basados en los fallos reales más habituales del laboratorio. |
| **Imágenes** | 51 capturas reales organizadas en `./img/`. | Exactamente las mismas 51 capturas de `./img/` (compartidas por ambas versiones). |

---

## Estructura del proyecto

* **`README.md`** — Este archivo de presentación y comparativa.
* **[`Guia_Lab5_V1_Tecnica.md`](./Guia_Lab5_V1_Tecnica.md)** — Versión 1: Manual técnico de referencia.
* **[`Guia_Lab5_V2_Paso_a_Paso.md`](./Guia_Lab5_V2_Paso_a_Paso.md)** — Versión 2: Guía guiada a prueba de atascos.
* **`img/`** — Carpeta con las 51 capturas de pantalla (`01a_...` a `34_...`) enlazadas en ambas guías.

> **Importante:** Mantén siempre los archivos `.md` al mismo nivel que la carpeta `img/` para que todas las capturas y enlaces carguen correctamente.

---

## Cómo visualizar las guías
* **En Visual Studio Code (recomendado):** Abre `README.md` y pulsa **`Ctrl + Shift + V`** para abrir la vista previa; desde ahí podrás hacer clic directamente en cualquiera de las dos guías.
* **En GitHub / GitLab o visores Markdown:** Se renderizan automáticamente junto con las capturas y los enlaces internos.