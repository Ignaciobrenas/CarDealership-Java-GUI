# 🚗 Concesionario de Vehículos (Java Swing & Ficheros)

<p align="center">
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white" alt="Java" />
  <img src="https://img.shields.io/badge/GUI-Java_Swing-007396?style=for-the-badge" alt="Java Swing" />
  <img src="https://img.shields.io/badge/Persistence-File_I%2FO-E34F26?style=for-the-badge" alt="File I/O" />
  <img src="https://img.shields.io/badge/Academic-1º_DAW_STUCOM-10B981?style=for-the-badge" alt="STUCOM" />
</p>

> 🎓 **Proyecto Académico:** Desarrollado para la práctica de **Interfaces Gráficas y Persistencia de Ficheros (MP0485 RA8/RA9)** en **STUCOM Pelai** (Barcelona), 1º Grado Superior en Desarrollo de Aplicaciones Web (DAW).

---

## Descripción del Proyecto

Aplicación de escritorio desarrollada en **Java** con interfaz gráfica **Java Swing** y persistencia en ficheros planos de texto (`archivo.txt`). Permite gestionar el parque automovilístico de un concesionario mediante formularios visuales para el alta, búsqueda, filtrado por matrícula y guardado persistente entre ejecuciones.

---

## 📁 Arquitectura y Paquetes

```
src/main/java/
├── main/
│   └── main.java                 # Punto de entrada de la aplicación Swing
├── controller/
│   └── Concesionario.java        # Controlador de negocio y gestión de la colección
├── model/
│   └── Vehiculo.java             # Entidad del modelo (matrícula, marca, modelo, etc.)
├── persistencia/
│   └── Fichero.java              # Lógica de I/O (BufferedReader, BufferedWriter)
└── view/
    ├── buscarView.java           # Formulario Swing generado con NetBeans GUI Builder
    └── buscarView.form           # Definición XML del layout visual
```

---

## ✨ Características Principales

- 🖥️ **Interfaz Visual Intuitiva:** Formulario Swing con campos de texto, botones de acción y tabla/panel de visualización.
- 💾 **Persistencia en Disco:** Lectura y escritura en `archivo.txt`, garantizando que ningún vehículo registrado se pierda al cerrar el programa.
- 🔍 **Búsqueda Dinámica:** Búsqueda y filtrado instantáneo por número de matrícula.
- 🛡️ **Validación de Datos:** Control de entradas vacías y formato de datos de entrada.

---

## 🚀 Compilación y Ejecución

### Mediante Maven
```bash
# Compilar el proyecto
mvn clean compile

# Ejecutar la aplicación
mvn exec:java -Dexec.mainClass="main.main"
```

### Mediante NetBeans IDE
1. Abrir el proyecto en **NetBeans IDE**.
2. Hacer clic derecho sobre el proyecto y seleccionar **Run**.
3. Interactuar con la ventana gráfica `buscarView`.

---

## 👤 Autor

**Ignacio Breñas Muñoz** — 1º DAW, STUCOM Pelai
