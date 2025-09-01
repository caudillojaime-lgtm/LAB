# 📱 LAB en Appsheet

Este repositorio documenta una aplicación desarrollada en **AppSheet** para llevar el control de un laboratorio de patología


## 🚀 Descripción
La app permite:
- Registrar:
-   Pacientes
-   Doctores que diagnostican casos
-   Medicos especialistas que envian muestras
-   Sitios donde se recolectan las muestras
-   Dependencias de salud a donde se envian resultados
-   Tipos de Muestras
- Administra:
-   Calendario de llegada de muestras
-   Fechas de entrega de resultados
-   Entrega de material patológico
- Generar reportes:
-   Resultados de patología
-   Resultados de citología
-   Resultados de liquidos varios
-   Entrega de material patologíco
-   Productividad mensual del laboratorio

Fue diseñada para usarse en dispositivos móviles y web.

---

## 🗂 Estructura del Repositorio
- `/app-definition/` → Contiene el archivo `app-definition.json` exportado desde AppSheet (estructura de la app).
- `/data/` → Ejemplos de las hojas de cálculo o bases de datos usadas (CSV, Excel).
- `/docs/` → Documentación visual: capturas de pantalla, diagramas de flujo y enlaces a videos demo.

---

## 📸 Capturas de pantalla
![Pantalla principal](docs/capturas/pantalla1.png)
![Flujo de navegación](docs/capturas/flujo_app.png)

---

## ⚙️ Cómo replicar
1. Crea una nueva app en AppSheet.
2. Importa las hojas de cálculo del directorio `/data`.
3. Configura las tablas según el archivo `app-definition.json`.
4. Ajusta permisos y pruebas en el editor.

---

## 📜 Licencia
Este proyecto se comparte bajo licencia MIT. Puedes usarlo y adaptarlo libremente.
