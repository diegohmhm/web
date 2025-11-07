# 🛍️ Stylex Ecommerce

Aplicación web desarrollada con **Django** para la gestión de productos e inventario.  
Permite registrar, buscar, editar y eliminar productos, así como descargar reportes en formato **CSV** o **Excel**.

---

## 🚀 Características principales

- 📦 CRUD completo de productos (crear, ver, editar, eliminar)
- 🔎 Búsqueda de productos por nombre o categoría
- 📸 Carga de imágenes de productos
- 📊 Exportación de reportes en **CSV** y **Excel**
- 🔐 Sistema de usuarios y autenticación básica
- 🖥️ Interfaz con **Bootstrap 5**

---

## ⚙️ Requisitos previos

Asegúrate de tener instalado:

- **Python 3.10+**
- **pip**
- **virtualenv** (opcional, pero recomendado)

---

## 🧩 Instalación

```bash
# Clonar el repositorio
git clone https://github.com/diegohmhm/web.git
cd web/stylex_ecommerce

# Crear entorno virtual
python3 -m venv venv
source venv/bin/activate  # En macOS/Linux
venv\Scripts\activate     # En Windows

# Instalar dependencias
pip install -r requirements.txt

# Aplicar migraciones
python manage.py migrate





stylex_ecommerce/
│
├── static/               # Archivos estáticos (CSS, JS, imágenes)
├── templates/            # Plantillas HTML (Bootstrap)
├── app_inventario/       # Lógica principal del CRUD
├── db.sqlite3            # Base de datos local (ignorada en Git)
├── manage.py
└── requirements.txt


👨‍💻 Autor

Diego Hernández






# Ejecutar el servidor
python manage.py runserver
