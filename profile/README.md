<div align="center">

# ArduMaker

### Del código a producción, con un flujo de trabajo más claro.

**Herramientas para desarrolladores, equipos y agentes de IA:** calidad de código, organización de proyectos e infraestructura en un mismo ecosistema.

[**Conocer el Code Checker**](https://ardumaker.com/checker/) · [**Organizar proyectos**](https://ardumaker.com/projects/) · [**Explorar los VPS**](https://ardumaker.com/) · [**Documentación**](https://ardumaker.com/docs/)

</div>

---

## 01 · Code Checker: un estándar para escribir y entregar mejor código

Un proyecto puede funcionar hoy y convertirse en un problema mañana. Archivos enormes, cambios sin pruebas, secretos en Git o commits imposibles de entender hacen que mantenerlo sea cada vez más difícil.

**ArduMaker Code Checker** es una herramienta gratuita para revisar el código y el *formato de trabajo* de un repositorio. Aplica **198 reglas comprobables** sobre estructura, seguridad, convenciones, documentación, historial de Git y configuración.

- **Detecta problemas concretos:** identifica la regla, el archivo, la ubicación y lo que se espera corregir.
- **Revisa antes de publicar:** integra hooks de `pre-commit`, `commit-msg` y `pre-push`.
- **Sirve para personas y agentes de IA:** genera reglas para `AGENTS.md` y ofrece resultados en JSON para agentes y CI.
- **Se adapta a cada proyecto:** permite ajustar reglas, severidades, umbrales y excepciones justificadas.
- **Ayuda a corregir:** `ardumaker fix` aplica las correcciones que pueden automatizarse.

```bash
ardumaker init             # Prepara el repositorio y sus hooks de Git
ardumaker check            # Revisa el proyecto
ardumaker check --strict --json  # Salida estructurada para CI y agentes
```

Gratuito con una cuenta de ArduMaker. Disponible para Linux y Windows de 64 bits. **No reemplaza las pruebas, el diseño ni las revisiones humanas.**

**[Ver cómo funciona →](https://ardumaker.com/checker/)** · [Documentación técnica](https://ardumaker.com/docs/code-checker/)

## 02 · Proyectos: el trabajo también necesita orden

No alcanza con revisar el código si nadie sabe qué sigue, quién se ocupa o qué bloquea la entrega.

El **gestor de proyectos de ArduMaker** reúne tableros, etapas, tareas, checklists, dependencias, calendario, reuniones, notas y archivos. Permite organizar el trabajo en equipo, controlar permisos y vincular repositorios y servidores.

Los agentes conectados por MCP pueden colaborar dentro de los permisos que se les autoricen; las acciones quedan registradas. **La gestión de proyectos es gratuita y no requiere contratar un VPS.**

**[Conocer Proyectos →](https://ardumaker.com/projects/)**

## 03 · VPS e infraestructura: del repositorio a un servicio real

Cuando el proyecto está listo, ArduMaker permite **crear y administrar servidores VPS** y operar lo necesario para publicar una web, una API o una automatización:

| Infraestructura | Herramientas |
| --- | --- |
| **Servidores y despliegues** | VPS Linux, terminal web, SSH, Docker, despliegues desde GitHub y redeploy |
| **Web y dominios** | Nginx, DNS, certificados SSL, WordPress y WooCommerce |
| **Datos y automatización** | PostgreSQL, MySQL, Redis, n8n y copias de seguridad |
| **Agentes de IA** | MCP con permisos, auditoría, Router IA y API de búsqueda |
| **Trabajo y comunicación** | Proyectos, correo con dominio propio y reuniones |

La idea no es sumar herramientas por sumar: es que **un desarrollador pueda revisar su código, coordinar tareas, desplegarlo y administrar su infraestructura** con menos pasos y más control.

**[Explorar ArduMaker →](https://ardumaker.com/)** · [Ver tutoriales cortos](https://ardumaker.com/started/) · [MCP para agentes](https://ardumaker.com/mcp/)

---

## Empieza por donde lo necesites

| Quiero… | Empezar aquí |
| --- | --- |
| Revisar la calidad de mi código y mis commits | [Code Checker](https://ardumaker.com/checker/) |
| Organizar tareas, fechas y entregas | [Gestor de proyectos](https://ardumaker.com/projects/) |
| Publicar mi primera web | [Guía paso a paso](https://ardumaker.com/start/) |
| Desplegar aplicaciones y gestionar servidores | [Plataforma VPS](https://ardumaker.com/) |
| Conectar Claude u otros agentes mediante MCP | [MCP de ArduMaker](https://ardumaker.com/mcp/) |
| Entender cada herramienta con ejemplos | [Videos Started](https://ardumaker.com/started/) y [docs](https://ardumaker.com/docs/) |

> **Nuestro enfoque:** código comprobable, trabajo ordenado e infraestructura bajo control. Cada parte puede usarse según lo que necesites.

### About ArduMaker · English

ArduMaker brings together a **free code quality checker**, **project management** and **VPS infrastructure** for developers, teams and AI agents. Review code with Git hooks and machine-readable results, coordinate your work, then deploy and manage services with GitHub and MCP.

[Website](https://ardumaker.com/) · [Code Checker](https://ardumaker.com/checker/) · [Documentation](https://ardumaker.com/docs/)

---

**Contacto:** [developer@ardumaker.com](mailto:developer@ardumaker.com) · **Web:** [ardumaker.com](https://ardumaker.com/)
