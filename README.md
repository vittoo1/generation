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

# 🖥️ Arquitectura Web Básica: Frontend, Backend y Base de Datos

## 1. 📚 Conceptos Clave

### 🎨 **Frontend** 
*(Capa de presentación)*  
- **Qué es**: La parte visible con la que interactúa el usuario  
- **Tecnologías**:  
  ```mermaid
  pie 
      title Tecnologías Frontend
      "HTML" : 35
      "CSS" : 30
      "JavaScript" : 35


  sequenceDiagram
    participant Usuario
    participant Frontend as "Frontend (Navegador)"
    participant Backend as "Backend (Servidor)"
    participant DB as "Base de Datos"
    
    Usuario->>Frontend: Hace clic en "Enviar"
    Frontend->>Backend: Envía datos (API Request)
    Backend->>DB: Consulta información
    DB-->>Backend: Devuelve resultados
    Backend-->>Frontend: Responde con JSON
    Frontend->>Usuario: Muestra nueva pantalla
