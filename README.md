# ♟️ Visión Artificial para Ajedrez: De Píxeles a Narrativa (PGN)

Este proyecto implementa un sistema de **Visión Artificial** capaz de analizar vídeos de partidas de ajedrez en tiempo real y generar automáticamente la narración de la partida (formato PGN).

![Demo](<img width="1980" height="1179" alt="Captura de pantalla 2026-02-10 014812" src="https://github.com/user-attachments/assets/ac7196f4-cdb5-47f4-8be1-90d20c26388a" />)

## 🚀 Características
* **Detección Robusta:** Uso de **YOLOv8** entrenado con Data Augmentation (HSV) para invarianza al color.
* **Lógica de Negocio:** Motor de inferencia que valida reglas FIDE (Enroques, Coronaciones).
* **Datos Sintéticos:** Generación programática de tableros para "Stress Testing".
* **Rendimiento:** Inferencia en tiempo real sobre CPU.

## 🛠️ Tecnologías
* Python 3.9+
* Ultralytics YOLOv8
* OpenCV
* NumPy / Pandas

## 📄 Documentación
Puedes consultar los detalles técnicos del proyecto aquí:
* [📄 Memoria Técnica del Proyecto (PDF)](./Memoria.pdf)
* [📊 Presentación de Defensa (PDF)](./PresentaciónAIVA.pdf)

## 🎥 Demo
Puedes ver el funcionamiento del sistema en el siguiente vídeo:
[Enlace al vídeo](https://github.com/user-attachments/assets/85245a31-8d8e-4c42-a3aa-a86e7a532c84)

---
*Autor: Raúl Sánchez Ibáñez - 2026*
