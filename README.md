# # Klipper para Hellbot Magna SE 8 Bits Creado y Optimizado por Fuzion3d

Este repositorio proporciona una implementación de **Klipper** para la **Hellbot Magna SE (8 bits)**, basada en una imagen de **Armbian** optimizada para un rendimiento estable y eficiente.

## ✨ Características

- **Configuración de Klipper (`printer.cfg`) personalizada:** Parámetros ajustados específicamente para la **Hellbot Magna SE 8 bits**, garantizando máxima precisión y rendimiento.
- **Perfil de Orca Slicer optimizado:** Configuración avanzada adaptada a la máquina, asegurando **calidad y eficiencia** en la impresión.
- **Velocidades calibradas para drivers A4988:** Ajustes de **aceleración, jerk y velocidades** adaptados para garantizar un equilibrio entre velocidad y calidad de impresión.

## 📌 Requisitos

- **Impresora:** Hellbot Magna SE (8 bits)
- **Cable de conexión:** Impresora a PC
- **SBC compatible con Armbian** (Raspberry Pi, MakerbasePI) o **PC compatible con Linux**
- **Software requerido:** Klipper, Moonraker y Mainsail/Fluidd configurados

## ⚙ Instalación

1. **Flashear Armbian** en la SBC (Raspberry Pi) o **instalar una distro Debian** en PC.
2. **Instalar Klipper, Moonraker y la interfaz web** (Mainsail/Fluidd). [Guía de instalación](https://github.com/dw-0/kiauh)
3. **Copiar el archivo `printer.cfg`** en la ruta correspondiente de configuración de Fluidd.
4. **Configurar Orca Slicer** con el perfil optimizado disponible en este repositorio.
5. **Flashear el firmware** `firmware.hex` a la impresora con [**Arduloader**](https://github.com/Fuzion3d-klipper/magna-se-8-bits-klipper/blob/main/arduloader.rar), utilizando el perfil `ATMega1284p usando Optiboot`. *(En algunos casos, puede ser necesario renombrar el archivo para que funcione correctamente. La pantalla de la impresora debería quedarse en el logo clavado después de la carga.)*
6. **Iniciar Klipper y realizar pruebas de calibración** para validar la configuración.

## 🔧 Notas

- Este firmware ha sido probado con **excelentes resultados** en la **Hellbot Magna SE 8 bits**.
- Se recomienda realizar una calibración básica (**PID, Z-offset, flow rate**) después de la instalación.
- **Ajustes adicionales** pueden ser necesarios según modificaciones del hardware.

Este repositorio está diseñado para **facilitar la implementación de Klipper en la Hellbot Magna SE 8 Bits**, optimizando su rendimiento y asegurando una **experiencia de impresión superior**. 🚀

