![deepseek_mermaid_20250707_5c0969](https://github.com/user-attachments/assets/69080b6e-25a6-40af-9314-a2d99662a0a7)
![deepseek_mermaid_20250707_5c0969](https://github.com/user-attachments/assets/a4fbd286-a2cb-4085-bb71-cf8e110c2041)
# Análisis de Sitios Web y Aplicaciones Web  

## 1. Sitios Web Informativos  
**Definición**: Plataformas que ofrecen contenido estático o actualizado para consulta, sin funcionalidades interactivas complejas.  

### Ejemplos  
- 🌐 **Wikipedia** - Enciclopedia digital colaborativa.  
- 📰 **BBC News** - Portal de noticias internacionales.  
- 🏞️ **National Geographic** - Sitio educativo sobre ciencia y naturaleza.  

**Justificación**: Su principal objetivo es **presentar información** (textos, imágenes, videos) con interacción limitada a búsquedas o navegación básica.  

---  

## 2. Aplicaciones Web  
**Definición**: Programas accesibles desde navegadores con alta interactividad, similares a software de escritorio.  

### Ejemplos  
- 📝 **Google Docs** - Procesador de texto colaborativo.  
- 📊 **Trello** - Gestor de proyectos con Kanban.  
- 🎨 **Figma** - Editor de diseño en la nube.  

**Justificación**: Permiten **crear, editar y gestionar datos** en tiempo real con interfaces dinámicas (ej: arrastrar y soltar).  

---  

## 3. Claves de Interactividad y Tecnologías  
### ¿Qué las hace interactivas?  
- ✨ **Feedback inmediato** (ej: autoguardado en Docs).  
- 🖱️ **Interfaces avanzadas** (drag-and-drop, menús contextuales).  
- ⚡ **Trabajo en tiempo real** (colaboración simultánea).  

### Tecnologías detrás  
| Área          | Tecnologías Clave                          |  
|---------------|--------------------------------------------|  
| **Frontend**  | React, Angular, Vue.js, HTML5/CSS3        |  
| **Backend**   | Node.js, Django (Python), Ruby on Rails    |  
| **Comunicación** | WebSockets, APIs REST/GraphQL           |  
| **Almacenamiento** | Firebase, PostgreSQL, MongoDB        |  

---  
**Conclusión**: La diferencia clave es que las aplicaciones web **procesan datos y responden a acciones del usuario**, mientras que los sitios informativos priorizan la entrega de contenido.  

# 🏗️ Arquitectura Web Básica: Frontend, Backend y Base de Datos

## 1. 📖 Definiciones Fundamentales

### 🖼️ **Frontend** (Cliente)
- **Función**: Interfaz visible que interactúa con el usuario
- **Tecnologías principales**:
  - HTML (estructura)
  - CSS (diseño)
  - JavaScript (lógica interactiva)
  - Frameworks: React, Vue, Angular
- **Responsabilidades**:
  - Mostrar datos
  - Capturar interacciones
  - Validar inputs básicos

### 🧠 **Backend** (Servidor)
- **Función**: Procesar lógica de negocio y gestionar datos
- **Componentes típicos**:
  - Servidor web (Node.js, Django, Spring)
  - API/RESTful services
  - Autenticación
- **Tareas clave**:
  - Procesar solicitudes
  - Comunicarse con la BD
  - Garantizar seguridad

![mermaid-ai-diagram-2025-07-07-151704](https://github.com/user-attachments/assets/9a4ee549-9645-454c-b092-eaac838ce40c)

📝 Explicación del Flujo:
Paso 1: El usuario realiza una acción (ej: click)

Paso 2: El frontend envía solicitud HTTP al backend

Paso 3: El backend:
Valida la petición
Construye consulta a la BD
Paso 4: La BD devuelve los datos solicitados

Paso 5: El backend procesa y envía respuesta al frontend

Paso 6: El frontend actualiza la interfaz

![deepseek_mermaid_20250707_ab02c8](https://github.com/user-attachments/assets/0b43c436-7269-4e44-be81-d17b605845fe)
