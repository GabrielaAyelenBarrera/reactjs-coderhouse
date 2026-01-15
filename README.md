# Detoxik (Ecommerce de Lencería)
Se trata de una aplicación web de tipo **ecommerce**, donde los usuarios pueden navegar un catálogo de productos de lencería, ver el detalle de cada producto, agregar artículos al carrito y finalizar una compra.

---

## 📚 Conceptos trabajados

- Fundamentos de React
- Componentes y JSX
- Hooks (`useState`, `useEffect`, `useContext`)
- Manejo de estado global
- Ruteo con React Router
- Consumo de APIs
- Flujo de compra en ecommerce
- Buenas prácticas de desarrollo
- Configuración y optimización del proyecto con **Vite**

---

## 🔹 Funcionalidades principales

- Navegación por categorías de productos
- Listado dinámico de productos
- Vista de detalle de cada producto
- Selección de cantidad
- Carrito de compras persistente
- Proceso de checkout
- Generación de orden de compra
- Obtención de un **ID de seguimiento** al finalizar la compra
- Almacenamiento de la orden en **Cloud Firestore**

---

## 🧩 Tecnologías utilizadas

- **React JS**
- **Vite**
- **React Router DOM**
- **Firebase / Cloud Firestore**
- **JavaScript (ES6+)**
- **HTML5**
- **CSS3**

---

## 🚀 Cómo correr el proyecto

### 1️⃣ Clonar el repositorio

```bash
git clone https://github.com/GabrielaAyelenBarrera/reactjs-coderhouse.git
cd reactjs-coderhouse
```
---
### 2️⃣ Verificar la carpeta del proyecto
Antes de instalar dependencias, verificar que la terminal esté ubicada en la carpeta correcta.

```bash
pwd
```
---
Luego listar los archivos:
```bash
ls
```
---
Debe mostrarse algo similar a: `docs/  reactjs-coderhouse/  README.md`

### 3️⃣ Instalar dependencias
Una vez confirmada la carpeta del proyecto, instalar las dependencias:
```bash
npm install 
```
---

### 4️⃣ Levantar servidor

```bash
npm run dev
```
---
### 4️⃣ Abrir el proyecto en el navegador
Una vez iniciado el servidor, Vite mostrará una URL similar a:

`http://localhost:5173/`

---

## 🛒 Flujo de la aplicación

- El usuario ingresa al Home y visualiza los productos
- Puede navegar por las categorías desde el menú
- Accede al detalle del producto
- Selecciona la cantidad y lo agrega al carrito
- Visualiza el checkout
- Completa el formulario con sus datos
- Genera la orden de compra
- Recibe un ID de seguimiento
- La orden queda almacenada en Firebase

---

## 📦 Almacenamiento de datos

Las órdenes de compra se guardan en Cloud Firestore, lo que permite:

- Persistencia de datos
- Identificación única de cada orden
- Gestión segura de la información del cliente

---

## 🖼️ Vista previa

## 🏠 **HOME**  
![...](docs/images/home.png)


## 💖 **ROMANTIC PANTIES**  
![...](docs/images/romant.png)

## 🌙 **NIGHT COLLECTION**  
![...](docs/images/night.png)


## 👙 **BRA & PANTY SETS**  
![...](docs/images/bra.png)


## 🛍️ Detalle del Producto
![...](docs/images/cart1.png)


## 🛒 Detalle de Producto con selección de cantidad
![...](docs/images/cart2.png)


## 🧾 Checkout – Resumen de la Compra
![...](docs/images/cart3.png)


## 📦 Confirmación de Compra y número de seguimiento
![...](docs/images/cart4.png)
![...](docs/images/cart5.png)


---

## 👩‍💻 Autora

Gabriela Ayelén Barrera

📫 Email:
gabrielaayelenbarrera1145@gmail.com

🔗 LinkedIn:
https://www.linkedin.com/in/gabrielabarrera
