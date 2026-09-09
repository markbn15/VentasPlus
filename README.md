<div align="center">

# 🚀 VentasPlus — Punto de Venta & Control de Inventario Inteligente

<p align="center">
  <img src="https://github.com/user-attachments/assets/8328ae36-0e37-442b-8ebc-2e82c6ee64e4" alt="VentasPlus Logo" width="200" height="200" />
</p>

![Kotlin](https://img.shields.io/badge/Language-Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white)
![Android Studio](https://img.shields.io/badge/IDE-Android%20Studio-3DDC84?style=for-the-badge&logo=android-studio&logoColor=white)
![Platform](https://img.shields.io/badge/Platform-Android-3DDC84?style=for-the-badge&logo=android&logoColor=white)
![Architecture](https://img.shields.io/badge/Architecture-MVVM-FF6F00?style=for-the-badge)
![Database](https://img.shields.io/badge/Database-Room%20SQLite-4285F4?style=for-the-badge&logo=sqlite&logoColor=white)

**VentasPlus** es un Sistema de Punto de Venta (POS) e inventario inteligente desarrollado desde cero en **Android Studio** utilizando **Kotlin puro**. Diseñado para emprendedores y pequeños negocios que priorizan la **rapidez, el control financiero total y la privacidad absoluta** sin depender de internet ni de suscripciones en la nube.

---

### 📲 ¡Descarga la Aplicación Ahora!

[<img src="https://img.shields.io/badge/Descargar_Última_Versión-APK-2ea44f?style=for-the-badge&logo=android&logoColor=white" height="45">](https://github.com/markbn15/VentasPlus/releases)

</div>

---

## 🔒 1. Pilar Fundamental: Privacidad y Seguridad Local

> [!IMPORTANT]
> **Tus datos son 100% tuyos.**  
> VentasPlus opera bajo un modelo **totalmente local (*Offline-First*)**. Ningún dato de tus ventas, catálogo, precios ni notificaciones viaja a servidores externos. Toda la información sensible permanece dentro del almacenamiento interno de tu dispositivo.

* 🌐 **Arquitectura 100% Offline:** Funciona totalmente de manera local mediante una base de datos **Room (SQLite)**. No realiza conexiones a servidores externos.
* 👤 **Privacidad por Diseño:** No exige registros ni cuentas en la nube. El correo y datos de perfil se utilizan estrictamente para la **personalización local de recibos**.
* 💾 **Copia de Seguridad Simplificada:** Sistema de exportación a archivo `.txt` en la carpeta de Descargas (ejemplo: `C:\Users\Admin\Downloads`), permitiendo respaldar la configuración del perfil y **3 meses de historial de ventas** en un formato legible por humanos.

---

## 🛠️ Especificaciones Técnicas
+---------------------------------------------------------------------------------+
|                               STACK TECNOLÓGICO                                 |
+--------------------------+------------------------------------------------------+
| Lenguaje                 | Kotlin Puro                                          |
| Arquitectura             | MVVM (Model-View-ViewModel)                          |
| Base de Datos            | Room (SQLite) con Migración Segura (Migration 1->2)  |
| Concurrencia             | Kotlin Coroutines & StateFlow                        |
| Escáner de Código        | ML Kit Barcode Scanning                              |
| Optimización de APK      | ABI Splits (arm64-v8a, armeabi-v7a, x86, x86_64)     |
+--------------------------+------------------------------------------------------+

---

## ✨ Características Destacadas

### 📦 2. Gestión de Inventario Inteligente
* 📝 **Ficha de Producto Completa:** Registro de *nombre, marca, categoría, precio de venta, costo de adquisición, stock y URI de imagen*.
* 📷 **Escáner Integrado:** Entrada y salida rápida de productos vía cámara utilizando **ML Kit Barcode Scanning**.
* ⚠️ **Control de Stock Crítico:** Algoritmo que detecta automáticamente productos con **5 unidades o menos**, activando alertas visuales e indicadores inmediatos.
* 📈 **Análisis de Rentabilidad:** Cálculo automático e instantáneo del **margen de ganancia neto y porcentual** por cada producto.

### 🛒 3. Punto de Venta (POS) y Facturación
* 🛍️ **Carrito de Compras Dinámico:** Permite añadir productos mediante búsqueda predictiva o escaneo de código de barras.
* 💳 **Métodos de Pago Versátiles:** Soporte para **Efectivo**, **QR de Banco** (con visor de imagen guardada) y **Fiado (Deuda)**.
* 🧾 **Generador de Recibos Digitales:** Creación de comprobantes de pago profesionales en formato de **imagen**, listos para compartir por **WhatsApp** o redes sociales.

### 👥 4. Gestión de Deudas (Fiado)
* 📋 **Módulo Dedicado de Deudores:** Pantalla independiente para monitorear *quién debe, cuánto debe y desde qué fecha*.
* ⏰ **Alertas de Antigüedad:** Notificaciones automáticas para deudas con **más de 7 días de vencimiento**.
* ✅ **Liquidación en Un Clic:** Marca deudas como pagadas, actualizando instantáneamente el historial y las métricas de caja.

### 📊 5. Dashboard e Inteligencia de Negocio
* ⚡ **Métricas en Tiempo Real:** Visualización de ingresos y transacciones con filtros dinámicos (**Hoy, 7 días, 30 días**).
* 📅 **Calendario Financiero v3.0:** Vista mensual interactiva con indicadores de actividad diaria.
* 💰 **Desglose Semanal Inteligente:** Panel que separa visualmente el **Dinero en Caja** del **Dinero por Cobrar** de la semana en curso.
* 🌍 **Sincronización Regional:** Reloj digital, calendario y adaptabilidad **multimoneda** vinculados a la zona horaria legal de la región elegida.

### 🎨 6. Interfaz (UX/UI) y Personalización
* 🎨 **Material Design 3:** Paleta de colores **Soft Light Blue** con tipografía monoespaciada tipo **Consolas** para una lectura clara de montos.
* 🌙 **Modo Oscuro OLED:** Fondo negro puro con resaltados en **celeste neón** para trabajo nocturno y reducción de consumo de batería.
* 🚀 **Onboarding Dinámico:** Tutorial paso a paso interactivo para la primera configuración del usuario.

---

## 🛠️ Requisitos de Instalación

* **S.O. Compatible:** Android 7.0 (API Nivel 24) o superior.
* **Permisos requeridos:**
  * 📷 `Cámara`: Para la lectura de códigos de barras y QR mediante ML Kit.
  * 🔔 `Acceso a Notificaciones`: Para la verificación de confirmaciones de pago bancarias *(opcional si prefieres verificar manualmente)*.

---

## 💻 Compilación e Instalación

``
# 1. Clona este repositorio

```bash
git clone [https://github.com/markbn15/VentasPlus.git](https://github.com/markbn15/VentasPlus.git)

```
# 2. Abre el proyecto en Android Studio (versión recomendada)

# 3. Sincroniza el proyecto con los archivos Gradle

# 4. Compila y ejecuta en un dispositivo físico o emulador
```
⭐ Apoya el Proyecto
Si VentasPlus te ha sido de utilidad para gestionar tu negocio o proyecto de desarrollo:

Dale una Estrella (⭐) a este repositorio en la parte superior derecha de GitHub.

Comparte el proyecto con otros desarrolladores o emprendedores.

🤝 Créditos y Agradecimientos
Agradecimiento especial a las tecnologías, librerías y personas que hicieron posible este proyecto:

📱 Google ML Kit: Por la tecnología rápida y precisa de escaneo de códigos de barras.

🗄️ Android Jetpack (Room & Coroutines): Por la infraestructura local de almacenamiento y concurrencia.

🎨 Material Components for Android: Por los componentes visuales de Material Design 3.

🧑‍💻 Comunidad Open Source: Por la documentación y ejemplos arquitectónicos.

Hecho con ❤️ para la comunidad de código abierto.

*Gracias kiri por el nombre del app*

📄 Licencia

## 📄 Licencia

Este proyecto está distribuido bajo los términos de la Licencia **Apache 2.0**. Para más detalles sobre permisos, limitaciones y derechos de uso, consulta el archivo `LICENSE` incluido en este repositorio.
