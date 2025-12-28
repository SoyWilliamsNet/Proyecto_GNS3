# Proyecto_GNS3 (Cisco Dynamips + IOU/IOL)

Laboratorio y recursos para **cargar y usar imágenes Cisco** en GNS3 con Dynamips e IOU/IOL, pensado para practicar routing/switching en escenarios reales de networking.

🎥 Video guía (paso a paso): https://youtu.be/PvLKN8buyoM

---

## 🚀 ¿Qué incluye este repositorio?

- Imágenes y/o referencias para trabajar con **Cisco Dynamips** (routers IOS).
- Imágenes y/o referencias para **Cisco IOU/IOL** (switching y routing más ligero).
- Material de apoyo para reproducir el laboratorio del video y montar tu entorno de práctica.

> Nota: GNS3 puede trabajar con diferentes emuladores; Dynamips está orientado a emulación de hardware Cisco y el ecosistema IOU/IOL se usa para laboratorios de alto rendimiento en equipos de escritorio. (Revisar siempre licenciamiento).  
> Referencia general (GNS3 docs): https://docs.gns3.com/docs/ [web:36]

---

## ✅ Requisitos

- GNS3 instalado (GUI y, recomendado, GNS3 VM si tu escenario lo requiere).
- CPU con virtualización habilitada (VT-x/AMD-V).
- Memoria y disco suficientes para tus topologías.
- Imágenes IOS / IOU **con licenciamiento correspondiente**.

---

## 🧩 Cómo usarlo (flujo recomendado)

1. Clona el repo:
git clone https://github.com/SoyWilliamsNet/Proyecto_GNS3.git

2. Abre el video y sigue el orden (es la forma más rápida de replicar el LAB):
https://youtu.be/PvLKN8buyoM
3. Importa las imágenes en GNS3 según el tipo:
- IOS (Dynamips)
- IOU/IOL (IOS on UNIX)

> Tip: IOU requiere licencia en GNS3 VM; la documentación de GNS3 explica el concepto del archivo de licencia (iourc) y la configuración en preferencias. [web:33]

---

## 🧠 Buenas prácticas (para que te corra fluido)

- Si estás empezando, arma topologías pequeñas y valida conectividad (ICMP, routing básico) antes de escalar.
- Documenta tu lab: nombre de nodos, subredes, protocolos y objetivos de verificación.
- Guarda “snapshots” o versiones del proyecto cuando logres un hito.

---

## 🌐 Mis redes y recursos

🌲 Linktree: https://linktr.ee/SoyWilliamsnet  
🌀 Discord (comunidad de redes): https://discord.gg/vUfrPXqv  
💻 GitHub: https://github.com/SoyWilliamsNet  
💡 Substack: https://substack.com/@soywilliamsnet  

---

## ⭐ Apoya el proyecto

Si este repo te ayudó:
- Dale **Star** al repositorio
- Comparte el video con alguien que esté aprendiendo redes
- Únete al Discord para resolver dudas y proponer labs nuevos

---

## 📌 Disclaimer (importante)

Este repositorio no pretende distribuir software sin autorización. Usa siempre imágenes y licencias obtenidas de forma legítima y respeta los términos del fabricante.
