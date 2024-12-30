# ¿Quién es este Pokémon? 🐉

Una aplicación interactiva inspirada en el clásico juego de adivinanza de los episodios de Pokémon. ¡Pon a prueba tus conocimientos e identifica a los Pokémon viendo solo su silueta!

---

## **¡Características principales!**

- 🎮 **Juego interactivo**: Introduce el nombre del Pokémon para descubrirlo.
- 🔐 **Validación dinámica**: Si aciertas, se revela el Pokémon; si no, obtienes feedback inmediato.
- 🔹 **Estado reactivo**: Contador de Pokémon descubiertos que se actualiza en tiempo real.
- 🔌 **Interfaz modular**: Componentes reutilizables creados con Vue.js.
- 🏠 **Diseño responsivo**: Perfecto para cualquier dispositivo.
- 🔍 **Integración con API**: Los datos de los Pokémon se obtienen dinámicamente desde la [PokeAPI](https://pokeapi.co/).

---

## **Tecnologías utilizadas**

- **Framework**: Vue.js 3
- **Librería HTTP**: Axios
- **Estilos**: CSS puro con transiciones suaves.
- **API**: [PokeAPI](https://pokeapi.co/)

---

## **Cómo instalar y ejecutar el proyecto**

### **1. Clona este repositorio:**
```bash
vue create pokemon
cd pokemon
git clone https://github.com/Hatecrew171/pokemon_vue.git
```

### **2. Instala las dependencias:**
Asegúrate de tener [Node.js](https://nodejs.org) instalado.
```bash
npm install
```

### **3. Inicia el servidor de desarrollo:**
```bash
npm run serve
```

El proyecto estará disponible en tu navegador en [http://localhost:8080](http://localhost:8080).

---

## **Estructura del proyecto**

```
src/
├── components/
│   ├── PokemonList.vue
│   └── PokemonCard.vue
├── App.vue
├── main.js
└── assets/
```

- **`PokemonList.vue`**: Maneja la lista de Pokémon y pasa los datos a los componentes individuales.
- **`PokemonCard.vue`**: Componente individual que muestra la silueta del Pokémon, el input de texto y la validación.
- **`App.vue`**: Componente principal que coordina la aplicación y muestra el contador de Pokémon descubiertos.

---

## **Mejoras futuras**

- 🌐 **Internacionalización (i18n)**: Soporte para múltiples idiomas.
- ➕ **Paginación**: Mostrar más Pokémon en diferentes páginas o mediante scroll infinito.
- ⚖️ **Pruebas unitarias**: Implementar Jest para garantizar la calidad del código.
- 🎨 **Mejoras visuales**: Agregar transiciones y animaciones más atractivas.
- 🛠️ **Optimización de carga**: Lazy loading para las imágenes.

---

## **Contribuciones**

¡Todas las contribuciones son bienvenidas! Si tienes una idea o encuentras un problema, por favor abre un _issue_ o envía un _pull request_.

---

## **Licencia**

Este proyecto está bajo la licencia MIT. Consulta el archivo `LICENSE` para más detalles.

---

**¡Que disfrutes descubriendo Pokémon!** 🌟

