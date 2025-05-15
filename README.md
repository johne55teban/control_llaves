#  Control de Llaves Institucional

Aplicación de escritorio desarrollada en Python para llevar un control seguro y eficiente de la entrega y devolución de llaves en una institución educativa. Incluye autenticación de usuarios, generación de reportes automáticos y envío de correos periódicos a la administración.

---

##  Tecnologías utilizadas

- **Python 3**
- **PyQt6** – Interfaz gráfica moderna
- **SQLite** – Base de datos local
- **Pandas** – Manipulación y exportación de datos
- **smtplib** – Envío de correos automáticos
- **openpyxl** – Generación de archivos Excel
- **schedule** – Tareas programadas

---

##  Funcionalidades principales

-  Registro e inicio de sesión con validación de contraseñas seguras  
-  Registro y seguimiento del uso de llaves por usuarios (profesores, administrativos, estudiantes)  
-  Generación automática de reportes en Excel cada 2 horas  
-  Envío de reporte por correo electrónico cada 6 horas  
-  Interfaz amigable con diseño personalizado

---

##  Estructura del proyecto

```
ControlLlaves/
│
├── db/
│   └── database.py          # Funciones de conexión y manipulación de la base de datos
│
├── gui/
│   ├── gui.py               # Ventana de login y registro
│   └── main_window.py       # Ventana principal del sistema
│
├── assets/
│   └── fondo.png            # Imagen de fondo de la interfaz
│
├── Reportes/
│   └── control_llaves.xlsx  # Reportes generados automáticamente
│
├── email_sender.py          # Script de envío automático de reportes
└── main.py                  # Archivo principal de ejecución
```

---

##  Cómo ejecutar la aplicación

1. Clona este repositorio:

```bash
git clone https://github.com/tu_usuario/control-llaves-institucional.git
```

2. Instala las dependencias necesarias:

```bash
pip install pyqt6 pandas openpyxl schedule
```

3. Ejecuta la aplicación:

```bash
python gui/gui.py
```

4. (Opcional) Inicia el servicio de envío de correos automáticos:

```bash
python email_sender.py
```

---

## 🛡️ Requisitos de seguridad para contraseñas

- Mínimo 8 caracteres  
- Al menos una letra mayúscula  
- Al menos un número  
- Al menos un carácter especial (ej: `!@#$%^&*()`)

---

## ✍️ Créditos

Desarrollado por [john Esteban Velasquez Gaviria]  
Institución: [Corporacion universitaria de Sabaneta(UNISABANETA)]  
Año: 2025

---

## 📬 Contacto

Wpp: 3195660836
¿Dudas o sugerencias? Escríbeme a: **johne55teban@gmail.com**
