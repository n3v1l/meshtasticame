# meshtasticame
Sitio documentación y ayuda para los voluntarios de Meshtasticame

# Guía práctica para implementar Meshtastic

Meshtastic es un proyecto de comunicación libre basado en LoRa, ideal para enviar mensajes sin necesidad de infraestructura celular o WiFi. Esta red de malla puede ser utilizada en contextos como senderismo, emergencias, exploración remota o proyectos DIY.

En esta guía encontrarás una introducción a tres aspectos clave para comenzar: **dispositivos compatibles**, **antenas recomendadas** y **modelos 3D para imprimir cases**.

---

## 1. Dispositivos compatibles

Meshtastic se basa en microcontroladores ESP32 con módulos de radio LoRa. Los más populares y soportados oficialmente son:

- **TTGO T-Beam**  
  Viene con GPS y batería integrada. Ideal para nodos portátiles.  
  👉 [Ficha técnica y compra en LilyGO (AliExpress)](https://www.aliexpress.com/item/4001108606602.html)

- **TTGO T-LoRa32**  
  Más compacto, sin GPS, pero funcional para nodos fijos o repetidores.  
  👉 [Más información en el GitHub de LilyGO](https://github.com/LilyGO/TTGO-T-LoRa32)

- **Heltec Wireless Stick / Lora32**  
  Alternativas con pantalla OLED.  
  👉 [Sitio oficial de Heltec](https://heltec.org/project/wireless-stick/)

- **RAK WisBlock**  
  Plataforma modular profesional y expandible.  
  👉 [Sitio oficial de RAK Wireless](https://docs.rakwireless.com/Product-Categories/WisBlock/)

Consulta siempre la [lista oficial de dispositivos compatibles](https://meshtastic.org/docs/hardware/devices/) para confirmar soporte y versiones.

---

## 2. Antenas recomendadas

Una buena antena mejora notablemente el alcance. Considera:

- **Antenas dipolo de 915 MHz**
  Suelen venir incluidas en kits TTGO o Heltec, pero pueden ser mejoradas.

- **Antenas externas tipo SMA (con base magnética o montaje en mástil)**  
  Ideal para nodos en exteriores o puntos altos.  
  👉 [Guía de antenas y conectores LoRa](https://www.thethingsnetwork.org/docs/lorawan/antennas/)

- **DIY: Antenas caseras (e.g. J-pole, ground plane)**  
  Baratas y funcionales, ideales para experimentar.  
  👉 [Ejemplo de antena ground plane casera](https://www.instructables.com/LoRa-Ground-Plane-Antenna-915-MHz/)

**⚠️ Importante:** Usa antenas correctas para la frecuencia de Chile:  
- 915 MHz (América)

---

## 3. Cases y modelos 3D

Proteger tus nodos con un buen case es fundamental. Aquí tienes recursos con diseños imprimibles:

- **Thingiverse - Búsqueda "Meshtastic"**  
  👉 [https://www.thingiverse.com/search?q=meshtastic](https://www.thingiverse.com/search?q=meshtastic)

- **Printables - Modelos para TTGO y Heltec**  
  👉 [https://www.printables.com/search?q=meshtastic](https://www.printables.com/search?q=meshtastic)

- **Diseños personalizados en GitHub**  
  Muchos usuarios publican cajas específicas para nodos con baterías, paneles solares o pantallas.  
  👉 [Repositorio de cases en GitHub (ejemplo)](https://github.com/Exploratorium/Meshtastic-Case)

- **Diseña tu propio case**  
  Puedes usar herramientas como OpenSCAD o Fusion 360 para crear un case a medida.  
  👉 [OpenSCAD - Tutorial básico](https://openscad.org/cheatsheet/)

---

## Recursos adicionales

- 🌐 Sitio oficial del proyecto: [https://meshtastic.org](https://meshtastic.org)
- 📱 App Android/iOS: Busca *Meshtastic* en la tienda.
- 🧠 Comunidad activa en Discord: [https://meshtastic.org/discord](https://meshtastic.org/discord)
- 📚 Documentación técnica: [https://meshtastic.org/docs/](https://meshtastic.org/docs/)

---

¿Estás listo para comenzar tu red Mesh? 🚀 Con un poco de hardware y curiosidad, puedes construir una red resiliente y descentralizada.


