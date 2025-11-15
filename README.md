# Calculadora Simple

Una calculadora web funcional y moderna desarrollada con HTML, CSS y JavaScript vanilla. Esta aplicación permite realizar operaciones matemáticas básicas de forma intuitiva.

## 📋 Descripción

Esta calculadora es una aplicación web simple que permite realizar operaciones aritméticas básicas (suma, resta, multiplicación y división) a través de una interfaz de usuario limpia y fácil de usar.

## ✨ Características

- **Operaciones básicas**: Suma (+), Resta (-), Multiplicación (x) y División (/)
- **Interfaz intuitiva**: Diseño de grid con botones grandes y fáciles de usar
- **Diseño moderno**: Fondo con gradiente y botones con efecto hover
- **Display en tiempo real**: Muestra los números y operaciones mientras se ingresan
- **Botón de borrar**: Permite limpiar la calculadora y comenzar una nueva operación

## 🛠️ Tecnologías Utilizadas

- **HTML5**: Estructura de la página
- **CSS3**: Estilos y diseño responsive con CSS Grid
- **JavaScript (Vanilla)**: Lógica de la calculadora sin dependencias externas

## 📁 Estructura del Proyecto

```
calculadora-simple/
├── index.html    # Estructura HTML de la calculadora
├── style.css     # Estilos y diseño visual
├── calc.js       # Lógica de la calculadora
└── README.md     # Este archivo
```

## 🚀 Cómo Usar

1. Abre el archivo `index.html` en tu navegador web
2. Haz clic en los botones numéricos (0-9) para ingresar números
3. Selecciona un operador (+, -, x, /) para realizar una operación
4. Ingresa el segundo número
5. Presiona el botón "=" para obtener el resultado
6. Usa el botón "C" para borrar y comenzar una nueva operación

## 💻 Funcionalidades Técnicas

### Funciones Principales

- `agregarNumero()`: Agrega números al display actual
- `agregarSimbolo()`: Agrega símbolos matemáticos a la operación
- `seleccionarOperacion()`: Selecciona y prepara la operación a realizar
- `calcularResultado()`: Ejecuta el cálculo según la operación seleccionada
- `actualizarDisplay()`: Actualiza el display con el valor actual
- `borrar()`: Limpia todas las variables y reinicia la calculadora

### Operaciones Soportadas

- **Suma (+)**: `número1 + número2`
- **Resta (-)**: `número1 - número2`
- **Multiplicación (x)**: `número1 × número2`
- **División (/)**: `número1 ÷ número2`

## 🎨 Diseño

La calculadora utiliza un diseño de grid CSS que organiza los botones en una cuadrícula de 4 columnas. El display ocupa todo el ancho de la calculadora y muestra los números en tiempo real. El fondo presenta un gradiente moderno que va del azul al verde.

## 📝 Notas

- La calculadora maneja números enteros y decimales
- El display es de solo lectura para evitar edición manual
- Los botones tienen efecto hover para mejorar la experiencia de usuario
- La aplicación es completamente funcional sin necesidad de conexión a internet

## 🔧 Compatibilidad

Esta calculadora funciona en todos los navegadores modernos que soportan:

- CSS Grid
- JavaScript ES6+
- HTML5

## 📄 Licencia

Este proyecto es de código abierto y está disponible para uso personal y educativo.
