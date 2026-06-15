# 📦 MANUAL DE USUARIO
## Sistema de Inventario y Ventas

---

## 🎨 PORTADA

```
╔════════════════════════════════════════════════════════════════╗
║                                                                ║
║          SISTEMA DE INVENTARIO Y VENTAS                       ║
║                    Versión 1.0                                ║
║                                                                ║
║                  [📊 MANUAL DE USUARIO 📊]                    ║
║                                                                ║
║                   Junio de 2026                               ║
║                                                                ║
║   Desarrollo: Certificación EC0835                           ║
║   Plataforma: Windows, Linux, macOS                          ║
║   Lenguaje: Python + Tkinter                                 ║
║                                                                ║
║        "Gestiona tu inventario de forma fácil"              ║
║                                                                ║
╚════════════════════════════════════════════════════════════════╝
```

---

## 📄 PÁGINA DE TÍTULO

**SISTEMA DE INVENTARIO Y VENTAS**

**Versión:** 1.0  
**Fecha:** Junio 2026  
**Certificación:** EC0835  

**Propósito del Manual:** Guiar al usuario en la instalación, configuración y uso de la aplicación Sistema de Inventario y Ventas de forma simple e intuitiva.

**Audiencia:** Usuarios finales sin conocimientos técnicos avanzados

**Contenido:** Este manual incluye instrucciones paso a paso para usar todas las funciones del sistema.

---

## 📚 ÍNDICE

1. [Introducción](#introducción)
2. [¿Qué puedes hacer con esta aplicación?](#qué-puedes-hacer-con-esta-aplicación)
3. [Requisitos de Instalación](#requisitos-de-instalación)
4. [Instalación y Configuración](#instalación-y-configuración)
5. [Primer Uso - Pantalla Principal](#primer-uso---pantalla-principal)
6. [Guía de Funciones Básicas](#guía-de-funciones-básicas)
7. [Glosario](#glosario)
8. [Preguntas Frecuentes](#preguntas-frecuentes)

---

## 🎯 INTRODUCCIÓN

¡Bienvenido al **Sistema de Inventario y Ventas**!

Esta aplicación ha sido diseñada para ayudarte a:
- 📦 **Organizar tus productos** en categorías
- 📊 **Controlar tu inventario** (cuántos productos tienes)
- 💰 **Registrar tus ventas** de forma fácil
- 📈 **Ver reportes** de lo que has vendido

**¿Para quién es esta aplicación?**

Perfecta para:
- Pequeños negocios
- Tiendas
- Almacenes
- Cualquiera que necesite controlar productos y ventas

**¿Qué hace especial esta aplicación?**

✨ **Interfaz Amigable** - Botones grandes y claros  
✨ **Fácil de usar** - No necesitas ser un experto en computación  
✨ **Segura** - Tus datos se guardan en tu computadora  
✨ **Rápida** - Registra ventas en segundos  
✨ **Gratuita** - Sin costos de suscripción

---

## 💡 ¿QUÉ PUEDES HACER CON ESTA APLICACIÓN?

### 1️⃣ GESTIONAR CATEGORÍAS
Organiza tus productos en grupos. Por ejemplo:
- Electrónica
- Ropa
- Alimentos
- Bebidas

### 2️⃣ CREAR PRODUCTOS
Registra cada producto con:
- Nombre
- Precio
- Cantidad en stock
- Categoría a la que pertenece

### 3️⃣ REGISTRAR VENTAS
Cuando vendes algo:
- Selecciona el producto
- Ingresa la cantidad
- La aplicación **calcula automáticamente** el total
- El stock se **actualiza solo**

### 4️⃣ VER REPORTES
Obtén información sobre:
- ¿Cuánto vendí en total?
- ¿Cuál fue mi producto más vendido?
- ¿Cuántos productos tengo por categoría?

---

## 🔧 REQUISITOS DE INSTALACIÓN

Antes de instalar, verifica que tu computadora tenga:

### PARA WINDOWS, LINUX O MAC

**Lo que necesitas:**
- Una computadora con **8 años o menos**
- Mínimo **512 MB de memoria RAM**
- Mínimo **50 MB de espacio disponible** en el disco
- Pantalla de **1024x768 píxeles** o superior

**Software necesario:**
- **Python 3.7 o superior** (¡es gratis!)

**¿Cómo sé qué versión de Windows/Linux/Mac tengo?**

**En Windows:**
1. Haz clic derecho en **"Este equipo"** o **"Mi PC"**
2. Selecciona **"Propiedades"**
3. Busca **"Edición"** (Windows 10, Windows 11, etc.)

**En Linux:**
```
Abre Terminal y escribe: lsb_release -d
```

**En Mac:**
1. Haz clic en **Menú Apple** > **Acerca de esta Mac**
2. Mira la **Versión de macOS**

---

## 🚀 INSTALACIÓN Y CONFIGURACIÓN

### PASO 1: DESCARGAR PYTHON

Python es el "motor" de la aplicación.

**Instrucciones:**

1. Abre tu navegador (Chrome, Firefox, Edge, Safari)
2. Ve a: **https://www.python.org/downloads/**
3. Verás un botón amarillo grande con **"Download Python"**
4. Haz clic
5. **Descarga la versión más reciente** (debe ser 3.7 o superior)

**Nota:** El archivo descargado se llama algo como `python-3.x.x.exe` (en Windows)

### PASO 2: INSTALAR PYTHON

#### En Windows:

1. **Abre el archivo descargado** (haz doble clic)
2. Verás una ventana con opciones
3. ⚠️ **IMPORTANTE:** Marca la casilla que dice **"Add Python to PATH"**
4. Haz clic en **"Install Now"**
5. Espera a que se complete la instalación (toma unos minutos)
6. Cuando termine, haz clic en **"Close"**

#### En Linux:

```bash
sudo apt-get update
sudo apt-get install python3 python3-pip python3-tk
```

#### En Mac:

1. Descarga el instalador desde https://www.python.org/downloads/
2. Haz doble clic en el archivo `.pkg`
3. Sigue las instrucciones del instalador
4. Completa la instalación

### PASO 3: VERIFICAR LA INSTALACIÓN

Abre una terminal o símbolo del sistema y escribe:

```
python --version
```

Deberías ver algo como: `Python 3.x.x`

Si ves esto, ¡Python está correctamente instalado! ✅

### PASO 4: OBTENER LA APLICACIÓN

**Opción A - Si tienes el archivo .zip:**
1. Descarga el archivo `gestion_inventario.zip`
2. Haz clic derecho > **"Extraer aquí"**
3. Crea una carpeta en tu escritorio llamada **"MiInventario"**
4. Mueve los archivos extraídos allí

**Opción B - Si tienes una carpeta:**
1. Simplemente copia la carpeta `gestion_inventario` a tu escritorio

### PASO 5: EJECUTAR LA APLICACIÓN

#### En Windows:

1. Abre la carpeta `gestion_inventario`
2. Haz clic en **"main.py"** (o busca un archivo con ese nombre)
3. Si aparece un menú, selecciona **"Ejecutar con Python"**
4. ¡La aplicación debe abrirse! 🎉

**Alternativa:** Si lo anterior no funciona:
1. Abre **"Símbolo del sistema"** (o **"Command Prompt"**)
2. Escribe:
```
cd Desktop\MiInventario
python main.py
```

#### En Linux o Mac:

1. Abre **Terminal**
2. Ve a la carpeta:
```
cd ~/Desktop/gestion_inventario
```
3. Ejecuta:
```
python3 main.py
```

### ¿FUNCIONA BIEN?

Cuando ejecutes la aplicación deberías ver:
- Una ventana con el título **"Sistema de Inventario y Ventas"**
- Botones coloridos
- Un menú en la parte superior

Si ves esto, ¡la instalación fue exitosa! ✨

---

## 📺 PRIMER USO - PANTALLA PRINCIPAL

Cuando abras la aplicación verás una pantalla como esta:

```
┌─────────────────────────────────────────────────────────────┐
│ Sistema de Inventario y Ventas                      [_][□][×]
├─────────────────────────────────────────────────────────────┤
│ Archivo | Gestión | Reportes | Ayuda                        │
├─────────────────────────────────────────────────────────────┤
│ [Gestionar Categorías] [Gestionar Productos] [Registrar ...]│
├─────────────────────────────────────────────────────────────┤
│                                                              │
│          Sistema de Inventario y Ventas                     │
│                 Bienvenido al sistema                       │
│        Use el menú o los botones para navegar              │
│                                                              │
│                                                              │
└─────────────────────────────────────────────────────────────┘
```

### PARTES PRINCIPALES:

**1. MENÚ (arriba)**
- Archivo → Salir
- Gestión → Categorías, Productos, Ventas
- Reportes → Ver análisis
- Ayuda → Información

**2. BOTONES (barra colorida)**
- 🟢 **Gestionar Categorías** - Crear grupos de productos
- 🔵 **Gestionar Productos** - Crear productos
- 🟠 **Registrar Ventas** - Registrar lo que vendes
- 🟣 **Ver Reportes** - Ver gráficos y números
- 🔴 **Salir** - Cerrar la aplicación

**3. ÁREA CENTRAL**
- Aquí verás la información según lo que selecciones

---

## 🎮 GUÍA DE FUNCIONES BÁSICAS

### FUNCIÓN 1: CREAR UNA CATEGORÍA

Las **categorías** son grupos para organizar productos.

**Ejemplo:** Electronics, Ropa, Alimentos

**Pasos:**

1. Haz clic en **"Gestionar Categorías"** (botón verde)

```
┌──────────────────────────────────────────────┐
│ ID:     [ ]                                   │
│ Nombre: [                                ]   │
│ Descripción: [                           ]   │
│                                              │
│ [Guardar] [Actualizar] [Eliminar] [Limpiar]│
│                                              │
│ ┌──────────────────────────────────────────┐ │
│ │ ID | Nombre | Descripción               │ │
│ │────────────────────────────────────────── │ │
│ │ 1  | Ropa  | Camisas, pantalones     │ │ │
│ │ 2  | Comida| Frutas, verduras       │ │ │
│ └──────────────────────────────────────────┘ │
└──────────────────────────────────────────────┘
```

2. **Escribe el nombre** en el campo "Nombre"
   - Ejemplo: `Electrónica`

3. (Opcional) **Escribe una descripción**
   - Ejemplo: `Laptops, teléfonos, accesorios`

4. Haz clic en **"Guardar"**

5. Verás un mensaje: ✅ **"Categoría guardada correctamente"**

6. La categoría aparece en la tabla abajo

**¡Listo!** Creaste tu primera categoría 🎉

---

### FUNCIÓN 2: CREAR UN PRODUCTO

Los **productos** son los artículos que vendes.

**Pasos:**

1. Haz clic en **"Gestionar Productos"** (botón azul)

2. **Primero:** Crea al menos una categoría (ver Función 1)

3. Completa los campos:

```
ID:        [  ]  ← No cambies, se llena automáticamente
Nombre:    [Laptop Dell Inspiron 15]
Precio:    [899.99]
Stock:     [5]
Categoría: [Electrónica ▼]  ← Elige de la lista
```

**Instrucciones por campo:**

| Campo | Qué escribir | Ejemplo |
|-------|-------------|---------|
| Nombre | El nombre del producto | Laptop, Mouse, Cable USB |
| Precio | El costo en dinero | 899.99, 25.50 |
| Stock | Cuántos tienes | 5, 10, 100 |
| Categoría | Selecciona una de la lista | Electrónica, Ropa |

4. Haz clic en **"Guardar"**

5. Verás: ✅ **"Producto guardado correctamente"**

6. El producto aparece en la tabla

**Consejos:**
- El nombre **no puede repetirse** (no puedes tener 2 "Laptop")
- El precio **debe ser positivo** (no negativo)
- El stock **debe ser un número entero** (5, 10, no 5.5)

---

### FUNCIÓN 3: REGISTRAR UNA VENTA

**Las ventas** es lo más importante: registrar lo que vendiste.

**Pasos:**

1. Haz clic en **"Registrar Ventas"** (botón naranja)

```
┌──────────────────────────────────────────┐
│ Producto:  [Laptop Dell Inspiron 15 ▼]   │
│ Cantidad:  [3]                            │
│ Total:     [$2,699.97]  ← Se calcula solo │
│                                           │
│ [Registrar Venta] [Limpiar] [Historial]  │
│                                           │
│ ┌──────────────────────────────────────┐ │
│ │ ID | Fecha | Producto | Cant | Total│ │
│ │──────────────────────────────────────│ │
│ │ 1  | 15:30 | Laptop   | 3    | $... │ │ 
│ └──────────────────────────────────────┘ │
└──────────────────────────────────────────┘
```

2. **Selecciona un producto** del combobox (lista desplegable)
   - Haz clic en el combobox
   - Elige un producto de la lista

3. **Escribe la cantidad** que vendiste
   - Ejemplo: `3` (vendiste 3 unidades)

4. **Observa el Total** (se calcula automáticamente)
   - Si el producto cuesta $899.99 y vendiste 3
   - El total será: $2,699.97

5. Haz clic en **"Registrar Venta"**

6. Verás: ✅ **"Venta registrada correctamente"**
   - Y el total que ganaste

**¿Qué sucede automáticamente?**
- ✅ El stock se reduce (si tenías 5 y vendiste 3, quedan 2)
- ✅ Se registra la fecha y hora
- ✅ Se guarda en el historial

**¿Qué pasa si intento vender más del stock disponible?**
- ❌ Ves un error: "Stock insuficiente. Disponible: 5"
- ✅ La venta se cancela (para tu protección)

---

### FUNCIÓN 4: VER TUS VENTAS (Historial)

Quieres ver lo que ya vendiste.

**Pasos:**

1. Haz clic en **"Registrar Ventas"** (botón naranja)

2. En la tabla de abajo ves **todas tus ventas**:

```
ID Venta | Fecha          | Producto  | Cantidad | Total
────────────────────────────────────────────────────────
1        | 2026-06-14 10:30 | Laptop    | 3        | $2,699.97
2        | 2026-06-14 11:15 | Mouse     | 5        | $127.50
3        | 2026-06-14 12:00 | Monitor   | 2        | $699.98
```

**Información que ves:**
- **ID Venta:** Número único de la venta
- **Fecha:** Cuándo la hiciste (día, hora)
- **Producto:** Qué vendiste
- **Cantidad:** Cuánto
- **Total:** Cuánto dinero ganaste en esa venta

**Para actualizar:** Haz clic en **"Ver Historial"**

---

### FUNCIÓN 5: VER REPORTES

Los **reportes** te muestran análisis de tus ventas.

**Pasos:**

1. Haz clic en **"Ver Reportes"** (botón morado)

2. Verás una lista desplegable con opciones:
   - **Ventas por Producto** (recomendado)
   - **Productos por Categoría**

### OPCIÓN A: VENTAS POR PRODUCTO

Te muestra cuál es tu producto más vendido.

```
Tipo de Reporte: [Ventas por Producto ▼] [Generar Reporte]

Producto     | Cant. Ventas | Total Cantidad | Total Vendido
─────────────────────────────────────────────────────────────
Laptop       | 5            | 10             | $8,999.50
Mouse        | 3            | 15             | $382.50
Monitor      | 2            | 4              | $799.96
────────────────────────────────────────────────────────────────
TOTAL GENERAL|              |                | $10,181.96
```

**Qué significa:**
- **Producto:** Nombre del artículo
- **Cant. Ventas:** Cuántas veces lo vendiste
- **Total Cantidad:** Cuántas unidades vendiste en total
- **Total Vendido:** Cuánto dinero ganaste con ese producto

### OPCIÓN B: PRODUCTOS POR CATEGORÍA

Te muestra cuántos productos tienes por categoría.

```
Tipo de Reporte: [Productos por Categoría ▼] [Generar Reporte]

Categoría       | Cantidad de Productos
────────────────────────────────────────
Electrónica     | 5
Ropa            | 12
Alimentos       | 20
```

**Qué significa:**
- **Categoría:** El grupo de productos
- **Cantidad de Productos:** Cuántos productos tienes en esa categoría

---

### FUNCIÓN 6: EDITAR UN PRODUCTO

Erraste el precio o el stock. ¡No hay problema!

**Pasos:**

1. Haz clic en **"Gestionar Productos"**

2. **Haz clic en la fila** del producto que quieres cambiar

```
┌────────────────────────────────────────────────────┐
│ Los datos del producto aparecen aquí              │
│                                                    │
│ ID:        [1]                                     │
│ Nombre:    [Laptop Dell Inspiron 15]               │
│ Precio:    [899.99]  ← Cambia esto                 │
│ Stock:     [5]      ← O esto                       │
│ Categoría: [Electrónica]                           │
└────────────────────────────────────────────────────┘
```

3. **Modifica el campo que necesites**
   - Borra el número antiguo
   - Escribe el nuevo número

4. Haz clic en **"Actualizar"**

5. Verás: ✅ **"Producto actualizado correctamente"**

**Nota:** No puedes editar el ID (está bloqueado)

---

### FUNCIÓN 7: ELIMINAR UN PRODUCTO

Si un producto ya no se vende.

**Pasos:**

1. Haz clic en **"Gestionar Productos"**

2. **Selecciona el producto** que quieres eliminar (haz clic en la fila)

3. Haz clic en **"Eliminar"**

4. Aparece un mensaje: ¿**Desea eliminar este producto?**
   - Haz clic en **"Sí"** para confirmar
   - O **"No"** para cancelar

5. Si todo está bien: ✅ **"Producto eliminado correctamente"**

**⚠️ IMPORTANTE:** 
No puedes eliminar un producto si ya tiene ventas registradas. Es para proteger tu historial de ventas.

---

## 📚 GLOSARIO

### TÉRMINOS BÁSICOS

**Aplicación**
- Un programa que funciona en tu computadora. En este caso, el Sistema de Inventario y Ventas.

**Categoría**
- Un grupo de productos relacionados. Ejemplo: "Electrónica" agrupa laptops, mouses, monitores.

**Combobox**
- Una lista desplegable donde seleccionas una opción. Ves una flecha ▼.

**Control de Inventario**
- Sistema para saber cuántos productos tienes disponibles.

**Datos**
- Información que guardan. Ejemplo: nombres, precios, cantidades.

**Eliminar**
- Borrar un registro de la base de datos. No se puede recuperar.

**Entrada (Entry)**
- Un cuadro donde escribes información. Ejemplo: [escribe aquí]

**Estándar EC0835**
- Certificación que garantiza la calidad de este software.

**Guardar**
- Registrar información en la base de datos para que se conserve.

**Hardware**
- Las partes físicas de la computadora (pantalla, teclado, mouse).

**Historial**
- Registro de todo lo que pasó. Ejemplo: historial de ventas.

**ID (Identificador)**
- Número único que identifica un registro. Ejemplo: Producto ID 5.

**Interfaz**
- La forma en que ves y usas la aplicación (botones, campos, etc.).

**Join (Combinación)**
- Técnica para juntar información de diferentes partes de la base de datos.

**Limpiar**
- Borrar el contenido de los campos del formulario para que queden vacíos.

**Modelo-Vista-Controlador (MVC)**
- Forma de organizar el código en tres partes: datos, interfaz, y lógica.

**Pantalla Principal**
- La primer pantalla que ves cuando abres la aplicación.

**Precio**
- El costo en dinero de un producto.

**Python**
- El lenguaje de programación usado para crear esta aplicación.

**Reporte**
- Un resumen o análisis de tus datos. Ejemplo: total de ventas.

**Stock (Inventario)**
- La cantidad de productos que tienes disponibles.

**SQLite**
- La base de datos (lugar donde se guardan tus datos).

**Treeview (Tabla)**
- Un cuadro que muestra información en filas y columnas.

**Actualizar**
- Cambiar información de un registro existente.

**Validación**
- Verificación de que los datos que escribes sean correctos.

**Venta**
- La acción de vender un producto. Registro del dinero ganado.

---

## ❓ PREGUNTAS FRECUENTES

### P1: ¿Dónde se guardan mis datos?

**R:** Se guardan en un archivo `inventario.db` en la misma carpeta de la aplicación.
- Windows: `C:\Users\TuNombre\Desktop\gestion_inventario\db\inventario.db`
- Linux: `~/Desktop/gestion_inventario/db/inventario.db`
- Mac: `~/Desktop/gestion_inventario/db/inventario.db`

**Importante:** No borres este archivo o perderás todos tus datos.

---

### P2: ¿Qué pasa si cierro la aplicación?

**R:** Tus datos se guardan automáticamente. Cuando abras nuevamente, verás toda la información que registraste.

---

### P3: ¿Puedo instalar la aplicación en múltiples computadoras?

**R:** Sí, puedes. Pero cada computadora tendrá su propia base de datos. Los datos NO se sincronizan automáticamente.

---

### P4: ¿Puedo cambiar un producto que ya tiene ventas?

**R:** Sí, puedes cambiar nombre, precio y stock. Pero NO puedes eliminarlo mientras tenga ventas.

---

### P5: ¿Qué pasa si me equivoco al registrar una venta?

**R:** Lamentablemente, no hay función para eliminar ventas (es por seguridad). Pero puedes:
- Registrar una venta "negativa" (si lo necesitas discutir con el administrador)
- O usar lápiz y papel para anotarlo

---

### P6: ¿La aplicación necesita Internet?

**R:** No, funciona completamente offline. Tus datos quedan en tu computadora.

---

### P7: ¿Puedo exportar mis datos a Excel?

**R:** En la versión 1.0 no, pero está planificado para futuras versiones.

---

### P8: ¿Qué hago si veo un error?

**R:** 
1. Lee el mensaje de error (te dirá qué está mal)
2. Verifica que escribiste los datos correctamente
3. Intenta nuevamente
4. Si persiste, reinicia la aplicación

---

### P9: ¿Cuál es la cantidad máxima de productos que puedo tener?

**R:** Teóricamente ilimitada, pero la aplicación funciona bien con hasta 10,000 productos.

---

### P10: ¿Es segura mi información?

**R:** Sí, porque:
- ✅ Los datos quedan en tu computadora
- ✅ No se envían a servidores externos
- ✅ Nadie más puede acceder (solo quien use tu computadora)

---

## 💡 CONSEJOS ÚTILES

### 1. ANTES DE EMPEZAR
- Crea todas tus categorías primero
- Luego crea los productos
- Finalmente registra las ventas

### 2. NOMBRES CLAROS
- En lugar de "Prod1" escribe "Laptop Dell Inspiron 15"
- En lugar de "Cat1" escribe "Electrónica"

### 3. REVISA REGULARMENTE
- Mira el historial de ventas frecuentemente
- Genera reportes semanalmente
- Verifica que el stock sea correcto

### 4. RESPALDOS
- Copia el archivo `inventario.db` a una USB o nube
- Hazlo una vez a la semana
- Así no perderás datos si tu computadora falla

### 5. ERRORES COMUNES

| Error | Causa | Solución |
|-------|-------|----------|
| "El nombre no puede estar vacío" | Olvidaste escribir un nombre | Escribe el nombre |
| "Ya existe un producto con ese nombre" | Intentas crear un duplicado | Usa otro nombre |
| "Stock insuficiente. Disponible: 5" | Intentas vender más del que tienes | Vende menos |
| "Seleccione una categoría" | No elegiste categoría en el combobox | Haz clic en el combobox |

---

## 📞 SOPORTE Y CONTACTO

**¿Necesitas ayuda?**

1. **Primero:** Lee nuevamente la sección que no entiendes
2. **Segundo:** Busca tu problema en "Preguntas Frecuentes"
3. **Tercero:** Consulta con alguien técnico de tu organización

**Información de la Aplicación:**
- Versión: 1.0
- Desarrollado para: Certificación EC0835
- Plataforma: Windows, Linux, macOS
- Lenguaje: Python + Tkinter

---

## ✨ CONCLUSIÓN

¡Felicidades! Ahora sabes cómo usar el **Sistema de Inventario y Ventas**.

**Recuerda:**
- 📦 Organiza con categorías
- 📝 Registra todos tus productos
- 💰 Anota cada venta
- 📊 Revisa tus reportes

Con esta aplicación, tendrás un control perfecto de tu negocio.

**¿Preguntas?** Revisa el glosario o las preguntas frecuentes.

**¡Éxito en tu negocio!** 🎉

---

**Manual de Usuario - Sistema de Inventario y Ventas**  
*Versión 1.0 - Junio 2026*  
*Certificación EC0835*

---

## 📄 INFORMACIÓN LEGAL

Este software se proporciona "TAL CUAL" sin garantías. El usuario es responsable de hacer respaldos regulares de sus datos.

**Fin del Manual de Usuario**
