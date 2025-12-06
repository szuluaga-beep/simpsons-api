# 🍩 Simpsons API - Galería de Personajes

Una aplicación web que muestra los personajes de Los Simpson utilizando [The Simpsons API](https://thesimpsonsapi.com/).

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)

## 📋 Descripción

Esta aplicación consume la API pública de Los Simpson para mostrar una galería de personajes con su información básica, incluyendo:

- 📸 Imagen del personaje
- 👤 Nombre
- 🎂 Fecha de nacimiento
- ⚧ Género

## 🚀 Características

- ✅ Diseño responsivo con CSS Grid
- ✅ Estilo visual inspirado en Los Simpson (colores amarillo y azul)
- ✅ Consumo de API REST con Fetch
- ✅ Sin dependencias externas

## 📁 Estructura del Proyecto

```
simpsons/
├── index.html    # Estructura HTML principal
├── index.js      # Lógica JavaScript para consumir la API
├── style.css     # Estilos CSS
└── readme.md     # Documentación
```

## 🛠️ Instalación y Uso

### Opción 1: Abrir directamente

1. Clona el repositorio:
   ```bash
   git clone https://github.com/szuluaga-beep/simpsons-api.git
   ```

2. Navega al directorio del proyecto:
   ```bash
   cd simpsons-api
   ```

3. Abre el archivo `index.html` en tu navegador favorito.

### Opción 2: Usar Live Server (Recomendado)

Este proyecto está configurado para usarse con la extensión **Live Server** de VS Code:

1. Instala la extensión [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) en VS Code.

2. Haz clic derecho en `index.html` → **"Open with Live Server"**.

3. El navegador se abrirá automáticamente en `http://127.0.0.1:5500`.

## 🔗 API Utilizada

Este proyecto utiliza [The Simpsons API](https://thesimpsonsapi.com/):

- **Endpoint:** `https://thesimpsonsapi.com/api/characters`
- **Método:** GET
- **Respuesta:** JSON con array de personajes

### Ejemplo de respuesta:

```json
{
  "results": [
    {
      "name": "Homer Simpson",
      "birthdate": "12 de mayo de 1956",
      "gender": "Masculino",
      "portrait_path": "/homer.png"
    }
  ]
}
```

## 🎨 Personalización

Puedes modificar los estilos en `style.css`:

| Variable | Descripción | Valor por defecto |
|----------|-------------|-------------------|
| Color primario | Color amarillo Simpson | `#ffd90f` |
| Color secundario | Fondo de tarjetas | `#2c3e50` |
| Fuente | Tipografía principal | `Comic Sans MS` |

## 🖥️ Vista Previa

La aplicación muestra una cuadrícula responsiva de tarjetas con la información de cada personaje de Los Simpson.

## 📄 Licencia

Este proyecto es de código abierto y está disponible bajo la licencia MIT.

## 👨‍💻 Autor

Desarrollado por [@szuluaga-beep](https://github.com/szuluaga-beep)

---

⭐ Si te gustó este proyecto, ¡dale una estrella en GitHub!
