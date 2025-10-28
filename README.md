# Auditoría de Base de Datos: Sistema de Gestión FINDEPRO

![Compilado con LaTeX](https://img.shields.io/badge/Fuente-LaTeX-00A0A0?style=for-the-badge&logo=latex)

Este repositorio contiene el informe de avance y los recursos técnicos (como scripts y checklists) para un proyecto de auditoría de bases de datos. El caso de estudio se centra en el sistema de gestión de **FINDEPRO**, una Institución Financiera de Desarrollo (IFD).

---

## ℹ️ Contexto Académico

Este proyecto es desarrollado para la asignatura de **Auditoría Informática (INF-314)** de la Carrera de Informática.

- **Universidad:** Universidad Mayor de San Andrés (UMSA)
- **Facultad:** Ciencias Puras y Naturales
- **Docente:** M. Sc. Miguel Cotaña Mier
- **Gestión:** 2025

---

## 🎯 Objetivo General del Proyecto

Evaluar integralmente la gestión, seguridad y rendimiento de la base de datos de FINDEPRO, identificando riesgos, verificando la efectividad de los controles implementados y proponiendo recomendaciones para fortalecer la protección de los datos y optimizar su uso.

### Objetivos Específicos

- Evaluar la **seguridad de acceso** (usuarios, roles, permisos).
- Verificar la **integridad y consistencia** de los datos (constraints, calidad).
- Validar la **confidencialidad** de datos sensibles (cifrado).
- Examinar los procedimientos de **respaldo y recuperación** (Backup & Restore).
- Analizar los mecanismos de **auditoría y monitoreo** (trazabilidad).
- Verificar el **cumplimiento** con políticas internas y normativas externas (ASFI).

---

## 🛠️ Metodología y Marcos Aplicados

El enfoque de la auditoría está basado en riesgos, alineado con marcos de referencia internacionales clave:

- **COBIT 2019:** Con énfasis en los dominios **DSS05** (Gestionar los Servicios de Seguridad) y **DSS06** (Gestionar los Controles del Proceso de Negocio).
- **ISO/IEC 27001:2022:** Para la Gestión de la Seguridad de la Información.
- **Regulaciones de la ASFI:** Aplicables a la entidad por ser una IFD.

---

## 🗂️ Estructura del Repositorio

- **/informe-latex/**: Contiene el código fuente `.tex` del informe de auditoría y sus recursos (imágenes, bibliografía).
- **/scripts-sql/**: (Sugerido) Scripts SQL utilizados para ejecutar las pruebas técnicas sobre la base de datos (ej. verificar permisos, buscar registros huérfanos, etc.).
- **/checklists/**: (Sugerido) Listas de verificación personalizadas basadas en COBIT e ISO 27002 utilizadas para la revisión documental y de campo.
- `README.md`: Este archivo.
- `.gitignore`: Archivo que ignora los archivos temporales de LaTeX y compilación.

---

## 👥 Integrantes

- Cristian Abel Mamani Mamani
- Carmen Reyna Candia Suñagua
- Gonzalo Rafael Esprella Coaquira
- Limbert Nelson Escobar Mamani
- Limberth Carbajal Colque
- Greis Estefani Gonzales Chávez

---

<details>
  <summary>🇬🇧 English Description</summary>
  
  ## Database Audit: FINDEPRO Management System

This repository holds the progress report and technical resources (like scripts and checklists) for a database audit project. The case study focuses on the management system of **FINDEPRO**, a Development Financial Institution (DFI).

### Academic Context

This project is developed for the **IT Audit (INF-314)** course at the Universidad Mayor de San Andrés (UMSA).

### Project Objective

To comprehensively evaluate the management, security, and performance of the FINDEPRO database. This includes identifying risks, verifying the effectiveness of implemented controls, and proposing recommendations to strengthen data protection and optimize its use.

### Methodology & Frameworks

The audit follows a risk-based approach, aligned with key international frameworks:

- **COBIT 2019** (Focusing on DSS05 and DSS06)
- **ISO/IEC 27001:2022**
- **ASFI Regulations** (Local financial authority regulations)

</details>
