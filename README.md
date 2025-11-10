# 🅿️ Sistema de Estacionamiento - UTN Villa María

Proyecto desarrollado como parte de la materia **Análisis de Sistemas**.

El sistema simula tres casos de uso esenciales del estacionamiento de la UTN:
- Registrar Vehículo  
- Registrar Egreso  
- Registrar Cuenta  

Cada módulo fue implementado en HTML, CSS y JavaScript, con una estética uniforme de color **naranja pastel**.

---

## 📂 Estructura del proyecto

| Archivo | Descripción |
|----------|--------------|
| `index.html` | Página principal (inicio) con menú de acceso a los casos de uso |
| `registrar-vehiculo.html` | Registro de vehículo perteneciente a la comunidad universitaria |
| `registrar-egreso.html` | Registro de egreso de vehículo con control de cobro |
| `registrar-cuenta.html` | Registro de cuenta corriente para usuarios de la comunidad |

---

## 💾 Mini base de datos de prueba

### 🔸 Registrar Vehículo
Para que el sistema confirme que pertenece a la comunidad universitaria, ingresar alguno de los siguientes datos:

| Nombre | Apellido | Documento |
|---------|-----------|-----------|
| Melina | Pedernera | 46034993 |
| Valentino | Miotti | 45697834 |

Si se ingresa otro nombre o documento, el sistema mostrará que no pertenece a la comunidad y no permitirá continuar.

---

### 🔸 Registrar Egreso
Patentes registradas en la base de ingresos activos:

| Patente | Estado |
|----------|--------|
| AB123CD | Ingreso normal |
| AA111BB | Ingreso normal |
| AC987FG | Reserva oficial (no cobra) |
| ZZZ000 | Deuda pendiente |

---

### 🔸 Registrar Cuenta
Tipos de usuario disponibles:
- Estudiante  
- Docente  
- No docente  

---

El proyecto se encuentra disponible en GitHub Pages:  
👉 [https://melpederneraa.github.io/Tpi-playa-de-estacionamiento/](https://melpederneraa.github.io/Tpi-playa-de-estacionamiento/)
