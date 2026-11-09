# Sistema de Matrícula Distribuido (2PC + MapReduce + LDAP)

**Asignatura:** Sistemas Distribuidos (ISA902)  
**Universidad Nacional Micaela Bastidas de Apurímac**  
**Facultad de Ingeniería - EP de Ingeniería Informática y Sistemas**  
**Docente:** Mg. Daryl Andrés Huamaní López  

---

## Descripción del Proyecto
Prototipo de un sistema de matrícula distribuido que aplica transacciones distribuidas en dos fases (2PC) para garantizar la consistencia ACID entre una base de datos relacional (SQLite) y una base documental (MongoDB/mongomock), previa autenticación jerárquica con LDAP. Además, genera un reporte de promedios por curso usando un modelo MapReduce multiproceso.

---

## Requisitos de Instalación

```bash
pip install ldap3 mongomock