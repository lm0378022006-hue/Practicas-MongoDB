# Práctica MongoDB — usuarioUNAB

**Universidad Dr. Andrés Bello (UNAB)**
**Facultad de Ingeniería en Ciencias de la Computación**
**Módulo III: Bases de Datos No Relacionales**

---

## Descripción

Este repositorio contiene el desarrollo de la práctica de laboratorio del Módulo III correspondiente a Bases de Datos No Relacionales, utilizando **MongoDB**. La práctica abarca:

- Creación de la base de datos `usuarioUNAB` y la colección `clientes`.
- Inserción de documentos con `insertMany()`.
- Consultas con filtros y operadores de comparación (`$gt`, `$lte`, `$ne`).
- Operadores lógicos (`$in`, `$nin`, `$or`).
- Proyección de campos.
- Ordenamiento (`sort`), límites (`limit`, `skip`).
- Creación de índices simples, compuestos y únicos.
- Análisis de rendimiento con `.explain("executionStats")` (COLLSCAN vs. IXSCAN).
- Eliminación de índices.
- Validación de integridad con índice único (error E11000).

---

## Integrantes — Grupo G1

| Nombre | Rol |
|--------|-----|
| Alejandro de Jesús Linares Marroquín | Integrante |
| Nathalie Jeannette Sibrian Pérez | Integrante |
| Miguel Daniel Reyes Martínez | Integrante |
| Vladimir Natanael Villalobos Vega | Integrante |

**Fecha de entrega:** 16 de mayo de 2026

---

## Contenido del repositorio

```
.
├── README.md                       # Este archivo
├── practica_mongodb.js             # Script con todos los comandos ejecutados
└── Practica comandos mongodb.docx        # Documento con capturas y evidencias
```

---

## Requisitos

- MongoDB Community Server (recomendado: versión 7.x o superior)
- MongoDB Shell (`mongosh`) o MongoDB Compass

---

## Cómo ejecutar la práctica

1. Iniciar el servicio de MongoDB localmente.
2. Abrir `mongosh` (o la pestaña MongoSH dentro de MongoDB Compass).
3. Ejecutar los comandos del archivo `practica_mongodb.js` en orden, uno por uno.
4. Verificar los resultados que se documentan en `Practica_MongoDB_G1.docx`.

```bash
# Ejemplo desde mongosh
mongosh
> use usuarioUNAB
> load("practica_mongodb.js")   // o copiar y pegar comando por comando
```

---

## Aprendizajes clave

- **Modelo orientado a documentos:** flexibilidad respecto al modelo relacional.
- **Operadores de consulta:** construcción de filtros complejos de forma intuitiva.
- **Índices:** mejoras de rendimiento drásticas (COLLSCAN → IXSCAN).
- **Integridad de datos:** los índices únicos protegen la consistencia a nivel del motor.

---

## Licencia

Trabajo académico — uso exclusivo para evaluación del Módulo III, UNAB 2026.
