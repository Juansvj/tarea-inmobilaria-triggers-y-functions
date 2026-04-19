# Sistema Inmobiliario

## 📌 Descripción general

Este proyecto consiste en el diseño e implementación de una base de datos para un sistema inmobiliario.
Permite gestionar contratos, clientes y automatizar procesos mediante eventos y funciones en MySQL.

---

## 🗄️ Script de la base de datos

El archivo `database.sql` contiene:

* Creación de tablas
* Relaciones entre entidades
* Funciones (FN_)
* Eventos (EVT_)

---

## ⚙️ Instrucciones de uso

1. Importar el archivo `database.sql` en MySQL o MariaDB
2. Activar el programador de eventos:

```sql id="use1"
SET GLOBAL event_scheduler = ON;
```

3. Ejecutar consultas para verificar funcionamiento:

```sql id="use2"
SELECT * FROM reporte_actividad;
SELECT * FROM alertas;
SELECT * FROM notificaciones;
```

4. Probar funciones:

```sql id="use3"
SELECT FN_CalcularPrecioSugerido(100);
SELECT FN_ObtenerPropiedadesCompatibles(500000);
```

---

## 🧩 Estructura de módulos implementados

* **Contratos:** Gestión de contratos de alquiler
* **Clientes:** Registro de clientes
* **Eventos:** Automatización de procesos
* **Funciones:** Cálculos y análisis de datos

---

## 🚀 Tecnologías utilizadas

* MySQL / MariaDB
* SQL


