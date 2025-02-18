<p align="center">
  <img src="https://github.com/Fuzion3d-klipper/magna-se-8-bits-klipper/blob/main/logo.png" alt="logo" width="700">
</p>


# # Klipper para Hellbot Magna SE 8 Bits Creado y Optimizado por Fuzion3d

Este repositorio proporciona una implementación de **Klipper** para la **Hellbot Magna SE (8 bits)**, basada en una imagen de **Armbian** optimizada para un rendimiento estable y eficiente.

## ✨ Características

- **Configuración de Klipper (`printer.cfg`) personalizada:** Parámetros ajustados específicamente para la **Hellbot Magna SE 8 bits**, garantizando máxima precisión y rendimiento.
- **Perfil de Orca Slicer optimizado:** Configuración avanzada adaptada a la máquina, asegurando **calidad y eficiencia** en la impresión.
- **Velocidades calibradas para drivers A4988:** Ajustes de **aceleración, jerk y velocidades** adaptados para garantizar un equilibrio entre velocidad y calidad de impresión.
- **M600** para cambio de color
- **Screw tilt Adjust** con las medidas especificas de los tornillos de la cama.
- **Aceleraciones** adaptadas para mejorar velocidades con drivers 4988

## 📌 Requisitos

- **Impresora:** Hellbot Magna SE (8 bits)
- **Cable de conexión:** Impresora a PC
- **SBC compatible con Armbian** Raspberry Pi, Recomiendo MakerbasePI de [**Techforge**](https://techforge.com.ar/)  o **PC compatible con Linux**
- **Software requerido:** Klipper, Moonraker y Mainsail/Fluidd configurados

## ⚙ Instalación

1. **Flashear Armbian** en la SBC (Raspberry Pi) o **instalar una distro Debian** en PC.
2. **Instalar Klipper, Moonraker y la interfaz web** (Mainsail/Fluidd). [Guía de instalación](https://github.com/dw-0/kiauh)
3. **Copiar el archivo `printer.cfg`** en la ruta correspondiente de configuración de Fluidd.
4. **Configurar Orca Slicer** con el perfil optimizado disponible en este repositorio.
5. **Flashear el firmware** `firmware.hex` a la impresora con [**Arduloader**](https://github.com/Fuzion3d-klipper/magna-se-8-bits-klipper/blob/main/arduloader.rar), utilizando el perfil `ATMega1284p usando Optiboot`. *(En algunos casos, puede ser necesario renombrar el archivo para que funcione correctamente. La pantalla de la impresora debería quedarse en el logo clavado después de la carga.)*
6. **Iniciar Klipper y realizar pruebas de calibración** para validar la configuración.

**📢 Disclaimer: El uso de toda la documentacio aqui detallada es bajo su propio riesgo!**

## 🔧 Notas

- Este firmware ha sido probado con **excelentes resultados** en la **Hellbot Magna SE 8 bits**.
- Se recomienda realizar una calibración básica (**PID, Z-offset, flow rate**) después de la instalación.
- **Ajustes adicionales** pueden ser necesarios según modificaciones del hardware.
- **Utilizar perfil Orca Slicer** que se provee el perfil especifico para la maquina en este repositorio, no usar otro perfil

Este repositorio está diseñado para **facilitar la implementación de Klipper en la Hellbot Magna SE 8 Bits**, optimizando su rendimiento y asegurando una **experiencia de impresión superior**. 🚀


## 🔗 Recursos y Créditos
- 📄 [Documentación oficial de Klipper](https://www.klipper3d.org/)
- 💬 Soporte en [Klipperianos Whatsapp](https://chat.whatsapp.com/IHaUnmBsNPnJ1kDIenCrmT)

## 📢 Conéctate conmigo 📢

- 🔗 **TikTok:** [Fuzion3D](https://www.tiktok.com/@fuzion3d)
- 📸 **Instagram:** [Fuzion3D Crea](https://www.instagram.com/fuzion3dcrea)
- 🎥 **YouTube:** [Fuzion3D Crea](https://youtube.com/@fuzion3dcrea)
- 💬 **WhatsApp:** [Klipperianos Whatsapp](https://chat.whatsapp.com/IHaUnmBsNPnJ1kDIenCrmT)

¡Únete a la comunidad y comparte tus creaciones con nosotros! 🚀🔥

## ☕ ¡Apoya al Creador!  

Si este proyecto te ha sido útil y quieres contribuir a futuros desarrollos, considera invitarme a un café. Tu apoyo ayuda a mejorar y mantener este contenido disponible para toda la comunidad.  

[![Apoya al creador](https://img.buymeacoffee.com/button-api/?text=Apoya%20al%20creador&emoji=&slug=fuzion3d&button_colour=FFDD00&font_colour=000000&font_family=Lato&outline_colour=000000&coffee_colour=ffffff)](https://www.buymeacoffee.com/fuzion3d)


Si encuentras útil esta macro, ⭐ ¡dale una estrella a este repositorio en GitHub! 🚀

<hr>

<h2 align="center">🌐 Fuentes y más información </h2>

<table align="center">
<tr>
    <th><h3><a href="https://github.com/Klipper3d/klipper">Klipper</a></h3></th>
    <th><h3><a href="https://github.com/Arksine/moonraker">Moonraker</a></h3></th>
    <th><h3><a href="https://github.com/mainsail-crew/mainsail">Mainsail</a></h3></th>
</tr>
<tr>
    <th><img src="https://raw.githubusercontent.com/Klipper3d/klipper/master/docs/img/klipper-logo.png" alt="Klipper Logo" height="64"></th>
    <th><img src="https://avatars.githubusercontent.com/u/9563098?v=4" alt="Arksine avatar" height="64"></th>
    <th><img src="https://raw.githubusercontent.com/mainsail-crew/docs/master/assets/img/logo.png" alt="Mainsail Logo" height="64"></th>
</tr>
<tr>
    <th>by <a href="https://github.com/KevinOConnor">KevinOConnor</a></th>
    <th>by <a href="https://github.com/Arksine">Arksine</a></th>
    <th>by <a href="https://github.com/mainsail-crew">mainsail-crew</a></th>
</tr>

<tr>
    <th><h3><a href="https://github.com/fluidd-core/fluidd">Fluidd</a></h3></th>
    <th><h3><a href="https://github.com/jordanruthe/KlipperScreen">KlipperScreen</a></h3></th>
    <th><h3><a href="https://github.com/OctoPrint/OctoPrint">OctoPrint</a></h3></th>
</tr>
<tr>
    <th><img src="https://raw.githubusercontent.com/fluidd-core/fluidd/master/docs/assets/images/logo.svg" alt="Fluidd Logo" height="64"></th>
    <th><img src="https://avatars.githubusercontent.com/u/31575189?v=4" alt="jordanruthe avatar" height="64"></th>
    <th><img src="https://raw.githubusercontent.com/OctoPrint/OctoPrint/master/docs/images/octoprint-logo.png" alt="OctoPrint Logo" height="64"></th>
</tr>
<tr>
    <th>by <a href="https://github.com/fluidd-core">fluidd-core</a></th>
    <th>by <a href="https://github.com/jordanruthe">jordanruthe</a></th>
    <th>by <a href="https://github.com/OctoPrint">OctoPrint</a></th>
</tr>

<tr>
    <th><h3><a href="https://github.com/nlef/moonraker-telegram-bot">Moonraker-Telegram-Bot</a></h3></th>
    <th><h3><a href="https://github.com/Kragrathea/pgcode">PrettyGCode for Klipper</a></h3></th>
    <th><h3><a href="https://github.com/TheSpaghettiDetective/moonraker-obico">Obico for Klipper</a></h3></th>
</tr>
<tr>
    <th><img src="https://avatars.githubusercontent.com/u/52351624?v=4" alt="nlef avatar" height="64"></th>
    <th><img src="https://avatars.githubusercontent.com/u/5917231?v=4" alt="Kragrathea avatar" height="64"></th>
    <th><img src="https://avatars.githubusercontent.com/u/46323662?s=200&v=4" alt="Obico logo" height="64"></th>
</tr>
<tr>
    <th>by <a href="https://github.com/nlef">nlef</a></th>
    <th>by <a href="https://github.com/Kragrathea">Kragrathea</a></th>
    <th>by <a href="https://github.com/TheSpaghettiDetective">Obico</a></th>
</tr>

<tr>
    <th><h3><a href="https://github.com/Clon1998/mobileraker_companion">Mobileraker's Companion</a></h3></th>
    <th><h3><a href="https://octoeverywhere.com/?source=kiauh_readme">OctoEverywhere For Klipper</a></h3></th>
    <th><h3><a href="https://github.com/crysxd/OctoApp-Plugin">OctoApp For Klipper</a></h3></th>
</tr>
<tr>
    <th><a href="https://github.com/Clon1998/mobileraker_companion"><img src="https://raw.githubusercontent.com/Clon1998/mobileraker/master/assets/icon/mr_appicon.png" alt="Mobileraker Logo" height="64"></a></th>
    <th><a href="https://octoeverywhere.com/?source=kiauh_readme"><img src="https://octoeverywhere.com/img/logo.svg" alt="OctoEverywhere Logo" height="64"></a></th>
    <th><a href="https://octoapp.eu/?source=kiauh_readme"><img src="https://octoapp.eu/octoapp.webp" alt="OctoApp Logo" height="64"></a></th>
</tr>
<tr>
    <th>by <a href="https://github.com/Clon1998">Patrick Schmidt</a></th>
    <th>by <a href="https://github.com/QuinnDamerell">Quinn Damerell</a></th>
    <th>by <a href="https://github.com/crysxd">Christian Würthner</a></th>
</tr>

<tr>
    <th><h3><a href="https://github.com/staubgeborener/klipper-backup">Klipper-Backup</a></h3></th>
    <th><h3><a href="https://simplyprint.io/">SimplyPrint for Klipper</a></h3></th>
</tr>
<tr>
    <th><a href="https://github.com/staubgeborener/klipper-backup"><img src="https://avatars.githubusercontent.com/u/28908603?v=4" alt="Staubgeroner Avatar" height="64"></a></th>
    <th><a href="https://github.com/SimplyPrint"><img src="https://avatars.githubusercontent.com/u/64896552?s=200&v=4" alt="" height="64"></a></th>
</tr>
<tr>
    <th>by <a href="https://github.com/Staubgeborener">Staubgeborener</a></th>
    <th>by <a href="https://github.com/SimplyPrint">SimplyPrint</a></th>
</tr>
</table>

<hr>

