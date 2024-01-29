<!-- Documentación del Proyecto Vue.js -->

# 📚 Documentación del Proyecto Vue.js

Este documento proporciona una descripción detallada de los archivos y funciones principales de la aplicación Vue.js.

## 📂 Archivo `App.vue`

<details>
  <summary><b>📝 Descripción</b></summary>

  El archivo `App.vue` es el componente principal de la aplicación. Contiene la estructura general de la interfaz de usuario y la lógica principal del componente. A continuación, se destacan las principales características:

  - **Variables Reactivas:**
    - `cantidad`: Una referencia reactiva para la cantidad del préstamo.
    - `meses`: Una referencia reactiva para el plazo de pago en meses.
    - `total`: Una referencia reactiva para el total a pagar.

  - **Funciones:**
    - `formatearDinero(valor)`: Formatea un valor numérico como una cantidad de dinero.
    - `handleChangeDecremento()`: Maneja la disminución de la cantidad del préstamo.
    - `handleChangeIncremento()`: Maneja el aumento de la cantidad del préstamo.

  - **Cálculos Computados:**
    - `pagoMensual`: Calcula el pago mensual basado en el total a pagar y los meses.

  - **Observadores:**
    - `watch([cantidad, meses])`: Observa cambios en la cantidad y los meses para actualizar el total.

  - **Componentes:**
    - `Header`: Componente que muestra el encabezado de la aplicación.
    - `Button`: Componente para los botones de incremento y decremento.
</details>

## 📂 Carpeta `components`

<details>
  <summary><b>📁 Estructura</b></summary>

  La carpeta `components` contiene los siguientes archivos:

  - `Header.vue`: Componente que define el encabezado de la aplicación.
  - `Button.vue`: Componente que define los botones de incremento y decremento.
</details>

## 📂 Carpeta `helpers`

<details>
  <summary><b>📁 Estructura</b></summary>

  La carpeta `helpers` contiene el siguiente archivo:

  - `index.js`: Archivo que exporta la función `calcularTotalPagar` utilizada en el cálculo del total.
</details>

## 📋 Requisitos del Proyecto

<details>
  <summary><b>⚙️ Requisitos del Proyecto</b></summary>

  Asegúrate de tener Vue.js instalado en tu proyecto antes de ejecutar la aplicación.
</details>

## 💡 Uso

<details>
  <summary><b>💡 Uso</b></summary>

  1. Descarga o clona el repositorio.
  2. Asegúrate de tener Vue.js instalado.
  3. Ejecuta la aplicación y ajusta la cantidad y los meses para simular diferentes escenarios de préstamo.
</details>

## 🤝 Contribución

<details>
  <summary><b>🤝 Contribución</b></summary>

  Si deseas contribuir al proyecto, sigue estas pautas:

  1. Crea un fork del repositorio.
  2. Realiza tus cambios en una rama separada.
  3. Asegúrate de realizar pruebas para comprobar que tus cambios funcionan correctamente.
  4. Envía una solicitud de extracción.
</details>

## 📄 Licencia

<details>
  <summary><b>📄 Licencia</b></summary>

  Este proyecto está bajo la Licencia MIT. Consulta el archivo `LICENSE` para obtener más información.
</details>

## ✉️ Contacto

<details>
  <summary><b>✉️ Contacto</b></summary>

  Si tienes alguna pregunta o sugerencia, no dudes en ponerte en contacto.
  lucho_l.f@hotmail.com
</details>

¡Gracias por utilizar esta aplicación Vue.js! 🚀
