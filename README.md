# 🎬 ScreenMatch - Buscador de Series y Temporadas

Este proyecto es una aplicación de consola desarrollada en **Java** que interactúa con la API de OMDb para buscar información detallada sobre series. Fue desarrollado como parte de la formación en **Alura Latam**, enfocándose en el dominio de la Programación Orientada a Objetos (POO) y el consumo de servicios web.

## 🚀 Funcionalidades
- **Búsqueda Avanzada:** Obtiene datos generales, calificaciones y pósters de series.
- **Detalle de Episodios:** Navega a través de las temporadas y extrae la lista completa de episodios.
- **Historial de Sesión:** Muestra las series consultadas durante la ejecución.
- **Tratamiento de Datos:** Limpieza y transformación de datos crudos (JSON) a objetos Java.

## ⚙️ Tecnologías y Herramientas
* **Java 17** (LTS)
* **Maven:** Gestión de dependencias y ciclo de vida del proyecto.
* **Jackson Annotations:** Para el mapeo y deserialización de JSON.
* **HttpClient:** Para la realización de peticiones asíncronas a la API.
* **OMDb API:** Fuente externa de datos cinematográficos.

## 🏛️ Arquitectura y Conceptos Aplicados
Este proyecto no es solo funcional, sino que sigue estándares de diseño profesional:
- **Interfaces:** Uso de interfaces para desacoplar la lógica de conversión de datos.
- **Generics:** Implementación de métodos genéricos para la reutilización de código.
- **Optional:** Manejo seguro de valores nulos o errores en la respuesta de la API.
- **Separación de Responsabilidades:** Organización en paquetes `service`, `model` y `principal`.

## 🛠️ Cómo ejecutarlo

1. **Clonar el repositorio:**
   ```bash
   git clone [https://github.com/renzodurand/nombre-de-tu-repo.git](https://github.com/renzodurand/nombre-de-tu-repo.git)

2. **Configurar la API Key:**
- Debes de obtener una llave gratuita en omdbapi.com y colocarla en la variable API_KEY dentro de la clase `Principal.java`.

3. **Ejecutar:**
- Compilar y ejecutar desde tu IDE favorito o mediante el Maven Wrapper:
   ```bash
   ./mvnw compile exec:java