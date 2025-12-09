# Tecno‑Market 🛒

## ✨ ¿Qué es Tecno‑Market?

Tecno‑Market es una tienda online que permite comprar productos tecnológicos con un diseño moderno, interfaz sencilla y una estructura clara. Está pensado para servir como base de un e‑commerce completo: catálogo, carrito, gestión de usuarios, pedidos y estructura modular.

> ⚙️ Tecnologías principales: PHP, Blade, CSS, JavaScript, Node.js/Vite (para frontend).

---

## 🧰 Características principales

- Página de catálogo y listado de productos.
- Páginas públicas: inicio, listado, producto individual, contacto, etc.
- Funcionalidades de backend: gestión de rutas, configuración, base de datos, almacenamiento.
- Integración con herramientas modernas de frontend (Vite, JS, CSS).
- Estructura modular — carpetas separadas para rutas, recursos, configuración, base de datos, almacenamiento, etc.
- Proyecto preparado para crecer: tests, configuración, estructura clara.

---

## 📁 Estructura del proyecto

```
/app            # Lógica del backend / aplicación
/bootstrap      # Configuración base
/config         # Configuración general
/database       # Migraciones / modelos / estructura de BD
/public         # Archivos públicos (assets, CSS, JS, imágenes)
/resources      # Vistas / assets / recursos del frontend
/routes         # Definición de rutas
/storage        # Archivos subidos / logs / almacenamiento
/tests          # Tests automatizados
/vendor         # Dependencias de PHP
package.json       # Dependencias frontend (JS, Vite, etc.)
composer.json      # Dependencias de PHP
vite.config.js     # Configuración de Vite
...
README.md       # Este archivo
```

---

## 🚀 Cómo instalar y ejecutar localmente

### Pre‑requisitos

- PHP ≥ 8.x  
- Composer  
- Node.js + npm o yarn  
- Base de datos (MySQL / MariaDB / SQLite / según configuración)

### Pasos

```bash
# 1. Clona el repositorio
git clone https://github.com/JesusMorIba/Tecno-Market.git
cd Tecno-Market

# 2. Instala dependencias backend
composer install

# 3. Instala dependencias frontend
npm install   # o yarn install

# 4. Configura variables de entorno
cp .env.example .env
# / configura .env con tus datos de BD, claves, etc.

# 5. Ejecuta migraciones / estructuras BD
php artisan migrate   # si usas framework tipo Laravel / migraciones
# o configura tu esquema de BD según project

# 6. Levanta el servidor de desarrollo
npm run dev      # para frontend  
php artisan serve  # para backend (si aplica)
```

Luego abre en el navegador `http://localhost:3000` (o el puerto configurado) para ver la aplicación.

---

## 📦 Uso / Funcionalidades

- Navegar catálogo de productos.
- Ver detalles de cada producto.
- (Opcional) Carrito de compra / gestión de pedidos — puedes ampliar esta funcionalidad.
- Interfaz clara y modular, ideal para escalar o adaptar a otros mercados.

---

## 🤝 Contribuir

¡Se aceptan contribuciones! Si quieres colaborar:

1. Haz un fork del repositorio.
2. Crea una rama nueva: `git checkout -b feature/nueva-feature`.
3. Haz tus cambios y commit: `git commit -m "Añade feature X"`.
4. Haz push a tu fork y abre un Pull Request.

Por favor, mantén la estructura de carpetas, usa buenas prácticas de codificación y documenta tus funciones / componentes.

---

## 📝 Licencia

Este proyecto está bajo la licencia MIT — libre para usar, modificar y distribuir.

---

## 📬 Contacto

Si tienes dudas, sugerencias o quieres colaborar:  
- Usuario GitHub: **JesusMorIba**  
- Abrir un issue o Pull Request en este repositorio

---

¡Gracias por interesarte en Tecno‑Market! Espero que te sea útil como base para un e‑commerce robusto y fácilmente ampliable. 🚀