# manual-formateo
MANUAL DE SOPORTE TÉC. FORMATEO

# 🖥️ Manual de Formateo y Reinstalación de Windows

## 📌 Descripción
Este proyecto documenta el proceso completo de **formateo y reinstalación de Windows 11** en notebooks y PCs de escritorio. Incluye opciones de recuperación, reinstalación desde la nube o local, y configuración inicial del sistema.

## 🎯 Objetivo
- Proporcionar una guía clara y visual para técnicos y usuarios avanzados.  
- Estandarizar el procedimiento de soporte técnico en entornos Windows.  
- Ahorrar tiempo mediante pasos automatizados y documentados.

## 🛠️ Requisitos previos
- Pendrive booteable con Windows 10/11.  
- Acceso a BIOS/UEFI para configurar el arranque.  
- Conocimientos básicos de comandos en consola (Diskpart).  
- Conexión a internet (si se usa descarga desde la nube).

---

## 🚀 Procedimiento paso a paso

### PASO 1️⃣ - Acceso a Información del Sistema
**Ubicación:** Configuración > Sistema > Información

En esta pantalla se puede verificar las especificaciones técnicas del equipo antes de proceder con el formateo:

![Información del Sistema](assets/imagen1_informacion_sistema.png)

**Detalles que se muestran:**
- 📊 **Procesador**: AMD Ryzen AI 7 PRO 350 w/ Radeon 860M @ 2.00 GHz
- 💾 **RAM instalada**: 32.0 GB (27.6 GB utilizables)
- 🎮 **Tarjeta gráfica**: AMD Radeon(TM) 860M Graphics (4 GB)
- 💿 **Almacenamiento**: 477 GB total (109 GB disponibles)
- 🖥️ **Tipo de sistema**: 64 bits, procesador x64

---

### PASO 2️⃣ - Acceso a Opciones de Recuperación
**Ubicación:** Configuración > Sistema > Recuperación

Desde esta sección se accede a todas las herramientas de restablecimiento del sistema:

![Opciones de Recuperación](assets/imagen2_recuperacion_opciones.png)

**El sistema ofrece varias secciones:**
- ⚙️ Restablecer este equipo
- 🔄 Recuperación del sistema
- 📋 Soporte técnico relacionado
- 🌍 Ayuda con recuperación

---

### PASO 3️⃣ - Selección del Tipo de Restablecimiento
**Pantalla:** "Elegir una opción"

En este paso crucial, debes elegir entre dos opciones:

![Elegir Opción de Restablecimiento](assets/imagen3_elegir_opcion.png)

#### 🔹 Opción A: **Conservar mis archivos**
- ✅ Mantiene los archivos personales
- ❌ Elimina todas las aplicaciones
- ❌ Elimina la configuración personalizada
- ⏱️ Tiempo: ~20-30 minutos

**Uso recomendado:** Cuando solo necesitas limpiar el sistema pero mantener documentos, fotos, videos, etc.

#### 🔹 Opción B: **Quitar todo**
- ❌ Elimina TODOS los archivos personales
- ❌ Elimina todas las aplicaciones
- ❌ Elimina toda la configuración
- ⏱️ Tiempo: ~30-45 minutos

**Uso recomendado:** Antes de vender/regalar el equipo o cuando necesitas un formateo completo.

---

### PASO 4️⃣ - Seleccionar Método de Reinstalación
**Pregunta:** "¿Cómo te gustaría reinstalar Windows?"

![Método de Reinstalación](assets/imagen4_metodo_reinstalacion.png)

#### 🌐 Opción A: **Descarga desde la nube**
- 📥 Descarga la última versión de Windows
- ⚡ Obtiene las actualizaciones más recientes
- 📡 **Requiere:** Conexión a internet estable
- 💾 **Requiere:** Mínimo 4 GB de datos
- ⏱️ Tiempo: Depende de la velocidad de conexión (puede tardar 1-2 horas)

**Recomendación:** Ideal si tienes internet rápido y quieres la versión más actualizada.

#### 💾 Opción B: **Reinstalación local**
- 📦 Reinstala desde la imagen existente en el dispositivo
- ⚡ Más rápido (sin descargas)
- 🔄 Mantiene la versión actual de Windows
- ⏱️ Tiempo: ~20-30 minutos
- 📡 No requiere conexión a internet

**Recomendación:** Ideal si tienes conexión lenta o necesitas hacerlo rápidamente.

---

### PASO 5️⃣ - Configuración Adicional
**Pantalla:** "Configuración adicional"

Aquí puedes revisar y personalizar las opciones antes de confirmar:

![Configuración Adicional](assets/imagen5_configuracion_adicional.png)

**Configuración que se aplicará:**
- 🗑️ Quitar aplicaciones y archivos
- ⚠️ NO limpiar la unidad (opción de seguridad)
- 📋 Eliminar los paquetes de aprovisionamiento del área de trabajo
- 🔄 Reinstalar Windows desde este dispositivo

**Botones disponibles:**
- 🔙 **Atrás**: Volver a pasos anteriores
- ✅ **Siguiente**: Continuar con el proceso
- ❌ **Cancelar**: Abortar la operación

---

### PASO 6️⃣ - Confirmación Final: "Listo para restablecer este equipo"
**Pantalla crítica:** Punto de no retorno

![Listo para Restablecer](assets/imagen6_listo_restablecer.png)

**Resumen final de lo que ocurrirá:**
- 👤 Quitar todos los archivos personales y las cuentas de usuario
- ⚙️ Quitar los cambios hechos en la configuración
- 🛑 Quitar todas las aplicaciones y los programas
- 🔄 Reinstalar Windows desde este dispositivo

**⚠️ NOTA IMPORTANTE:**
- ⏰ Esto llevará un rato
- 🔌 Tu PC se reiniciará automáticamente
- ⛔ No desconectes la alimentación durante el proceso
- 🔒 Asegúrate de haber hecho backup de datos importantes

**Botones finales:**
- 🔴 **Restablecer**: Confirma e inicia el formateo (¡NO hay retorno!)
- ❌ **Cancelar**: Aborta la operación completamente

---

### PASO 7️⃣ - Proceso en Progreso: "Preparando para restablecer"
**Pantalla de inicio del proceso**

![Preparando para Restablecer](assets/imagen7_preparando_restablecer.png)

**Durante esta fase:**
- ⏳ Estado inicial: **preparando: 1%**
- 🔄 Animación de carga en progreso
- 📱 Mensaje: "Este dispositivo se reiniciará automáticamente"
- ⏱️ Tiempo: Varía según el equipo (5-15 minutos iniciales)

**Lo que está pasando:**
1. El sistema está configurando los parámetros de formateo
2. Se están preparando los archivos del sistema
3. Se está configurando el punto de reinicio
4. Próximamente se producirá un reinicio automático

**⚠️ Importante durante esta fase:**
- ❌ NO desconectes el equipo
- ❌ NO desactives la alimentación
- ⏸️ NO suspendas el equipo
- 📌 Solo puedes cancelar durante esta fase inicial si lo deseas

---

## 📊 Estadísticas del Proceso

| Fase | Tiempo Estimado | Acción |
|------|-----------------|--------|
| Selección de opciones | 2-5 min | Manual |
| Preparación | 5-15 min | Automático |
| Restablecimiento (local) | 20-30 min | Automático |
| Restablecimiento (nube) | 1-2 horas | Automático |
| Configuración inicial | 10-15 min | Manual |
| **TOTAL (local)** | **45-60 min** | - |
| **TOTAL (nube)** | **1.5-2.5 horas** | - |

---

## 🔒 Recomendaciones de Seguridad

### ✅ ANTES de formatear:
- 📁 Realiza copia de seguridad de archivos importantes
- 📷 Exporta tus fotos y documentos
- 🔐 Guarda contraseñas en lugar seguro
- 📧 Anota cuentas de usuario importantes
- 💿 Ten a mano drivers o software que necesites instalar

### ⚠️ DURANTE el formateo:
- 🔌 Mantén el equipo conectado a la corriente (preferiblemente con UPS)
- 📡 Cierra todas las aplicaciones antes de iniciar
- ⏸️ No suspendas ni hibernes el equipo
- 🌐 Si usas descarga de nube, mantén conexión estable

### ✅ DESPUÉS del formateo:
- 🔄 Instala drivers de hardware
- 🔐 Crea contraseña fuerte
- 📦 Instala antivirus y firewall
- 🔄 Instala aplicaciones necesarias
- 💾 Restaura datos desde backup

---

## 📂 Estructura del Proyecto

```
manual-formateo/
│
├── README.md                    # Este archivo (guía principal)
│
├── assets/                      # Capturas de pantalla
│   ├── imagen1_informacion_sistema.png
│   ├── imagen2_recuperacion_opciones.png
│   ├── imagen3_elegir_opcion.png
│   ├── imagen4_metodo_reinstalacion.png
│   ├── imagen5_configuracion_adicional.png
│   ├── imagen6_listo_restablecer.png
│   ├── imagen7_preparando_restablecer.png
│   └── recuperacion.png         (original)
│
└── docs/                        # Documentación adicional
    ├── TROUBLESHOOTING.md       # Solución de problemas
    ├── DRIVERS.md               # Guía de instalación de drivers
    └── POST_INSTALACION.md      # Pasos después del formateo
```

---

## 🆘 Solución de Problemas Comunes

### ❌ "No puedo acceder a Recuperación"
**Solución:**
1. Presiona `Windows + I` para abrir Configuración
2. Ve a Sistema > Recuperación
3. Si aún así no funciona, reinicia en Modo Seguro

### ❌ "El proceso se congela"
**Solución:**
1. Espera al menos 30 minutos más (puede ser lento)
2. Verifica que no haya pop-ups ocultos
3. Si realmente se congela, reinicia forzadamente (apaga/enciende)

### ❌ "No tengo espacio suficiente"
**Solución:**
1. Libera espacio en disco (mínimo 10 GB recomendado)
2. Elimina archivos temporales: `Windows + R` → `%temp%`
3. Vacía la papelera de reciclaje

### ❌ "Se interrumpió la conexión a internet"
**Solución:**
1. Si elegiste descarga de nube, el proceso se pausará
2. Restaura la conexión de internet
3. El proceso debería reanudar automáticamente
4. Si no, reinicia y comienza de nuevo

---

## 📞 Contacto y Soporte

Para dudas o problemas durante el formateo:
- 📧 Consulta con soporte técnico
- 📱 Contacta al administrador del sistema
- 🌐 Revisa la documentación en `/docs`

---

## 📋 Checklist Previo al Formateo

- [ ] ¿He hecho backup de mis archivos?
- [ ] ¿Tengo acceso a mis contraseñas?
- [ ] ¿El equipo está conectado a corriente?
- [ ] ¿Tengo tiempo suficiente (mínimo 1 hora)?
- [ ] ¿He anotado números de serie o licencias?
- [ ] ¿Tengo acceso a drivers si es necesario?
- [ ] ¿He cerrado todas las aplicaciones?
- [ ] ¿Estoy seguro de que quiero formatear?

---

## 📊 Estadísticas del Repositorio
![Stats](https://github-readme-stats.vercel.app/api?username=MarceloNH-IT&show_icons=true&theme=radical)

---

**Última actualización:** 2026-06-07  
**Versión:** 2.0  
**Estado:** ✅ Completo con imágenes paso a paso
