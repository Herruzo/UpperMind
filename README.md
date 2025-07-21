# 🧠 UpperMind – Detección Temprana del Alzheimer mediante IA

**UpperMind** es una aplicación de escritorio desarrollada para el sistema operativo **Windows**, diseñada con el objetivo de ayudar en la **detección temprana del Alzheimer** mediante el análisis automático de imágenes de resonancia magnética cerebral (MRI) utilizando modelos de inteligencia artificial.

---
## 📥 Descargar la aplicación completa.

💾 [Descargar UpperMind (última versión)](https://github.com/Herruzo/UpperMind/releases/latest)

---

## 📁 Estructura del proyecto

```
UpperMind/
├── _internal/                             # Archivos necesarios para la ejecución de UpperMind.exe
├── Imágenes_Validar/
│   └── 50_fotos_de_casa_clase/
│       ├── AD/                           # Imágenes con diagnóstico de Alzheimer
│       ├── CN/                           # Imágenes de sujetos cognitivamente normales
│       ├── EMCI/                         # Deterioro cognitivo leve temprano
│       └── LMCI/                         # Deterioro cognitivo leve tardío
├── leer_antes.txt                        # Información esencial previa al uso
├── UpperMind.exe                         # Ejecutable principal de la aplicación
└── Video_demo.mp4                        # Vídeo demostrativo del funcionamiento
```

---

## 🚀 ¿Qué hace esta aplicación?

1. Valida si una imagen corresponde a una **MRI cerebral real**.
2. Clasifica automáticamente la imagen MRI en una de las siguientes categorías:
   - `AD`: Alzheimer
   - `CN`: Cognitivamente Normal
   - `EMCI`: Deterioro Cognitivo Leve Temprano
   - `LMCI`: Deterioro Cognitivo Leve Tardío

El diagnóstico se presenta de forma visual y comprensible desde una **interfaz gráfica amigable** (desarrollada en PyQt5).

---

## 👀 Características principales
- Precisión del modelo: 98.62% en validación cruzada.
- Interfaz intuitiva (PyQt5) para uso médico.
- Modelo optimizado en TensorFlow Lite para ejecución rápida.

---

## 📌 Requisitos del sistema

- **Sistema operativo**: Windows 10 o superior
- **Procesador**: Intel i5/i7 (10ª gen. o superior)
- **Memoria RAM**: recomendada 16 GB
- **Espacio en disco**: al menos 10 GB libres

---

## 🧪 Imágenes de validación

Las imágenes disponibles en la carpeta `Imágenes_Validar/50_fotos_de_casa_clase/` **no fueron utilizadas en el entrenamiento** de los modelos de IA. Están organizadas en subcarpetas por clase para facilitar pruebas de validación reales:

- `AD/`: Imágenes de pacientes con Alzheimer
- `CN/`: Sujetos cognitivamente normales
- `EMCI/`: Deterioro cognitivo leve temprano
- `LMCI/`: Deterioro cognitivo leve tardío

---

## 📽️ Vídeo demostrativo

Se incluye un vídeo (`Video_demo.mp4`) con una demostración completa del flujo de uso de la herramienta: desde la carga de imágenes hasta la visualización del diagnóstico.

---

## 📄 Documentación adicional

Se recomienda leer el archivo `leer_antes.txt` antes de utilizar la aplicación. Contiene información técnica relevante, tiempos de carga aproximados, condiciones de ejecución, tipo de imágenes soportadas y limitaciones actuales.

---

## ⚠️ Aviso legal

Esta aplicación **no reemplaza el diagnóstico médico profesional**. Su objetivo es ofrecer una herramienta de apoyo al diagnóstico basada en inteligencia artificial, útil para profesionales de la salud, investigadores y entidades interesadas en salud digital.

---

## 📬 Contacto

**Desarrollado por:** Antonio Mata Herruzo  
📧 ant.mata@hotmail.com 
🔗 https://www.linkedin.com/in/ant-mata/
