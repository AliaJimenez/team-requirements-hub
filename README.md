# P3 Team Requirements Hub 🚀

Este proyecto nació para solucionar un problema común en el desarrollo de proyectos grupales académicos: **el caos de coordinar tareas y requerimientos a través de múltiples documentos PDF dispersos**. 

Para resolverlo, desarrollamos esta **plataforma web centralizada** que permite a todo el equipo de desarrollo acceder a las especificaciones técnicas del proyecto de la materia **Programación III (P3)** desde cualquier dispositivo, en tiempo real, sin necesidad de descargar archivos adicionales y simplemente abriendo un enlace.

El proyecto cuenta con un flujo de integración y despliegue continuo (CI/CD) automatizado a través de **GitHub Actions**.

---

## 💡 Problemas que Resuelve

*   **Dispersión de información:** Evita el uso de múltiples versiones de PDFs de requerimientos al unificar todo en una única fuente de verdad.
*   **Accesibilidad multiplataforma:** Permite la consulta rápida de asignaciones y responsabilidades desde dispositivos móviles o computadoras de forma instantánea.
*   **Sincronización de responsabilidades:** Facilita la división de tareas y asegura que cada integrante del equipo conozca sus responsabilidades en tiempo real.

---

## 🛠️ Tecnologías y Herramientas

*   **Frontend:** HTML5, CSS3 / Frameworks de diseño (según implementación de tu `index.html`).
*   **CI/CD / Automatización:** GitHub Actions (`.github/workflows/main.yaml`) para automatizar el despliegue continuo cada vez que se actualizan los requerimientos.
*   **Despliegues:** Configurado para servirse estáticamente (GitHub Pages u homólogos).

---

## 📁 Estructura del Repositorio

*   **`index.html`**: El portal principal donde se visualizan y estructuran de forma responsiva los requerimientos de desarrollo del equipo[cite: 5].
*   **`.github/workflows/main.yaml`**: Pipeline de GitHub Actions encargado de compilar, verificar o desplegar la web automáticamente ante cambios en la rama principal.

---

## 🚀 Despliegue y Contribución

### Cómo ejecutar localmente:
1. Clona el repositorio en tu máquina local:
   ```bash
   git clone https://github.com/AliaJimenez/team-requirements-hub 
