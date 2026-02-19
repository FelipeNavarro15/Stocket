# 📦 Stocket

**“Conecta y Crece con Stocket”**

Plataforma B2B que elimina intermediarios en la cadena de suministro. Permite a almacenes y distribuidoras negociar directamente, gestionar pedidos y facturas, y aprovechar análisis de datos para tomar decisiones inteligentes.

---

## ✨ Características

- **Conexión Directa**  
  Negocia sin comisiones ni intermediarios ocultos.

- **Control Total**  
  Gestión integral de pedidos y facturación desde un solo panel.

- **Análisis Detallado**  
  Gráficos y estadísticas para entender el comportamiento comercial.

- **Seguridad y Escalabilidad**  
  Backend en Django/DRF con JWT; frontend en React 18.

---

## 🛠 Stack Tecnológico

| Capa       | Tecnologías principales |
|------------|-------------------------|
| Backend    | Django, Django REST Framework, SQLite/PostgreSQL, JWT, CORS, dotenv |
| Frontend   | React 18, Vite, React Router Dom v6, Chart.js, Lucide React |
| Despliegue | (por definir: Docker/Heroku/Azure/etc.) |

---

## 🚀 Instalación

### Backend (local)

1. Crear entorno virtual y activarlo:

   ```bash
   python -m venv venv
   .\venv\Scripts\activate       # Windows
   # source venv/bin/activate   # macOS/Linux
   ```

2. Instalar dependencias:

   ```bash
   pip install -r backend/requirements.txt
   ```

   *(o `pip install django djangorestframework django-cors-headers ...`)*

3. Configurar variables de entorno (`.env`) y migrar:

   ```bash
   cd backend
   python manage.py migrate
   python manage.py runserver
   ```

4. Accede a `http://localhost:8000/`.

### Frontend

1. Instalar paquetes:

   ```bash
   cd frontend
   npm install
   ```

2. Arrancar el servidor de desarrollo:

   ```bash
   npm run dev
   ```

3. Abrir `http://localhost:5173` (o la URL mostrada por Vite).

---

## ⚙️ Uso

- **Registro / Login:** Formulario con JWT.  
- **Panel de análisis:** Gráficos interactivos de transacciones.  
- **Gestión de productos/pedidos:** CRUD desde el frontend.  

---