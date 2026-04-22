# ðŸš— Car Dealership Management System (Java Swing GUI & File I/O)

<p align="center">
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white" alt="Java" />
  <img src="https://img.shields.io/badge/GUI-Java_Swing-007396?style=for-the-badge" alt="Swing GUI" />
  <img src="https://img.shields.io/badge/Persistence-File_I%2FO-047857?style=for-the-badge" alt="File IO" />
  <img src="https://img.shields.io/badge/Academic-1Âº_DAW_STUCOM-10B981?style=for-the-badge" alt="STUCOM" />
</p>

> ðŸŽ“ **Academic Project Notice:** This project was developed as an academic assignment for the **1st year of Web Application Development (DAW)** at **STUCOM Pelai** (Barcelona) within the Object-Oriented Programming and Data Access modules.

---

## ðŸ“Œ Overview / DescripciÃ³n General

### ðŸ‡¬ðŸ‡§ English
Desktop vehicle inventory and dealership management system developed in **Java** using a graphical user interface built with **Java Swing (.form UI views)** and flat-file data persistence (rchivo.txt). It provides full CRUD operations for vehicles, enabling staff to search, insert, and delete records reliably.

### ðŸ‡ªðŸ‡¸ EspaÃ±ol
Sistema de escritorio para la gestiÃ³n de inventario y concesionario de vehÃ­culos desarrollado en **Java**, empleando una interfaz grÃ¡fica de usuario creada con **Java Swing** y persistencia de datos en ficheros de texto plano (rchivo.txt). Permite realizar operaciones CRUD sobre los vehÃ­culos: bÃºsqueda por matrÃ­cula, inserciÃ³n de nuevas unidades y eliminaciÃ³n.

---

## âœ¨ Key Features / CaracterÃ­sticas Principales

- ðŸ–¥ï¸ **Graphical User Interface (GUI):** Clean Swing views (insertarView, uscarView, eliminarView) designed with NetBeans GUI Builder.
- ðŸ’¾ **File-Based Persistence (Fichero.java):** Custom file I/O layer reading and writing vehicle records safely to rchivo.txt.
- ðŸ” **Vehicle Lookup & Validation:** Fast search by vehicle license plate with input validation and exception handling.
- ðŸš˜ **Vehicle Data Model (Vehiculo.java):** Encapsulation of brand, model, registration date, and technical attributes.

---

## ðŸ—ï¸ Architecture & Project Structure

`
src/main/java/com/mycompany/concesionario/
â”œâ”€â”€ main.java            # Application entry point launching the main UI window
â”œâ”€â”€ Concesionario.java   # Business logic and vehicle collection management
â”œâ”€â”€ Vehiculo.java        # Vehicle entity definition with getters, setters, and validation
â”œâ”€â”€ Fichero.java         # File persistence handler (file stream read/write)
â”œâ”€â”€ insertarView.java    # Swing form view for registering new vehicles
â”œâ”€â”€ buscarView.java      # Swing form view for searching vehicles by plate
â””â”€â”€ eliminarView.java    # Swing form view for removing vehicles
`

---

## ðŸš€ How to Run / CÃ³mo Ejecutar

1. **Requirements:** Java JDK 17+ and Apache Maven.
2. **Compile and Run:**
   `ash
   mvn clean compile
   mvn exec:java -Dexec.mainClass="com.mycompany.concesionario.main"
   `
   *Or open and run the project directly in NetBeans, IntelliJ IDEA, or Eclipse.*

---

## ðŸ“„ License

Distributed under the **MIT License**.
