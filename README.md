# 🚀 QA Engineering: Pruebas Web - Urban Routes (Sprint 3)

Este repositorio contiene la documentación técnica y los resultados de las pruebas integrales realizadas a la funcionalidad de reserva de automóviles.

## 🎯 Objetivo del Proyecto
Validar que el flujo de reserva sea estable y libre de errores críticos, asegurando que la lógica de negocio y la interfaz de usuario (UI) coincidan con los requisitos.

## 🛠️ Tecnologías y Entornos
* **Navegadores:** Google Chrome (800x600) y Firefox (1920x1080).
* **Gestión de Defectos:** Atlassian Jira.
* **Diseño de Pruebas:** Análisis de Valores Límite (AVL) y Partición de Clases de Equivalencia (PCE).

## 📁 Estructura del Proyecto
* **`/documentacion`**: Contiene la hoja de cálculo con listas de comprobación y casos de prueba.
* **`/evidencias`**: Capturas de pantalla del tablero de Jira y reportes técnicos.

## 📊 Gestión de Defectos (Jira)
Se identificaron fallos importantes como:
* **Error de Servidor 503:** Detectado mediante DevTools.
* **Fallo de Lógica (CPG-21):** Error `Unimplemented method` al intentar cancelar una reserva.

## 📝 Conclusión Técnica
Debido a los errores de severidad **"Highest"** encontrados, se recomienda **NO pasar a producción** hasta resolver los defectos de lógica y servidor.
