# 🚀 Escalera eléctrica a escala: Automatización, control y simulación de perfiles mediante ESP32


> Nuestro proyecto consiste en el desarrollo de un modelo funcional de una escalera eléctrica a escala. Está orientado a estudiantes de educación técnica para enseñar de manera práctica los principios de automatización, electrónica, mecánica y programación.
Es importante porque ofrece una herramienta didáctica e interactiva que conecta la teoría con la práctica, favoreciendo el aprendizaje en áreas de Sistemas y Diseño, así como su uso en tecnologías IoT.

---

## 🎯 Objetivo del Proyecto

Desarrollar un modelo educativo de escalera eléctrica a escala, controlado mediante un microcontrolador ESP32 y sensores con conexión a una aplicación móvil, para facilitar la enseñanza de conceptos mecánicos, electrónicos y de programación.

- Qué problema busca resolver: La brecha entre la teoría y la práctica en la educación técnica, donde los estudiantes muchas veces carecen de herramientas interactivas para aplicar de una manera didáctica e interesante lo aprendido en el aula.
- A qué público está dirigido: Estudiantes y docentes de educación técnica, princiapalmente de las áreas de Sistemas y Diseño, sin embargo es útil para cualquier persona que quiera interactuar y aprender temas como la automatización electrónica, diseño mecánico e IoT
- Qué lo hace diferente o especial:
  
    - Integra mecánica, electrónica, programación y control remoto en un solo prototipo.
    - Utiliza simulación de perfiles mediante un sensor de color para adaptar el funcionamiento de la escalera.
    - Se controla desde una aplicación móvil Blynk IoT, la cual se conecta mediante la placa ESP32.

---

## 🧪 Prototipo

Este es el circuito que se va a utilizar para el proyecto, en las imagenes se puede evidenciar la conexión de los materiales a utilizar, y el uso que se le da al sensor TCS230, escaneando los diferentes colores, dependiendo de estos la velocidad del motor paso a paso, y por lo tanto de la escalera.

<img width="400" height="560" alt="image" src="https://github.com/user-attachments/assets/55a8d287-a424-4374-aa41-fe03657d5ac1" />
<img width="400" height="560" alt="image" src="https://github.com/user-attachments/assets/1f8e7d55-37ee-4542-b0b7-64b6b21c7fd1" />


## 📸 Imágenes 

A continuación se encuentra una imagén con todos los materiales que se van utilizar, los cuales van a ser utilizados a continuación.

Lista de materiales:
- ESP32
- Sensor PIR
- Sensor de Color
- Motor paso a paso
- Driver ULN2003
- 20 Jumpers macho - macho
- 20 Jumpers macho - hembra
- Protoboard

<img width="1280" height="537" alt="image" src="https://github.com/user-attachments/assets/8e1c1828-1e6c-4fe4-abf5-ec1eaa6f34f6" />
<img width="400" height="480" alt="image" src="https://github.com/user-attachments/assets/db6c7507-217e-4ba3-acca-d60c8f5e1084" />
<img width="600" height="400" alt="image" src="https://github.com/user-attachments/assets/ecbaad26-514e-4f93-9aec-b2d3a3abe8d3" />


## ✨ Materiales

### ESP32 
<img width="330" height="330" alt="image" src="https://github.com/user-attachments/assets/fe87a1e4-5185-4a34-9f49-e412cf9972a9" />

Es el microcontrolador principal del proyecto; coordina todos los sensores, controla el motor y se comunica con la aplicación Blynk mediante Wi-Fi.

### Sensor PIR (HC-SR501)
<img width="330" height="330" alt="image" src="https://github.com/user-attachments/assets/83fc3004-2e9a-472e-a379-b491bd7d3c9d" />

Detecta el movimiento de personas cercanas para encender automáticamente la escalera eléctrica cuando alguien se aproxima.

### Sensor de Color TCS230
<img width="330" height="330" alt="image" src="https://github.com/user-attachments/assets/bcd39a55-4795-47aa-b392-5d25b82ba45c" />

Identifica el color del objeto frente a él, permitiendo ajustar la velocidad de la escalera según el perfil detectado.

### Motor Paso a Paso 28BYJ-48
<img width="330" height="330" alt="image" src="https://github.com/user-attachments/assets/747740f0-6022-4ed9-89c3-f3e575fcb6cf" />

Genera el movimiento controlado y preciso que simula el funcionamiento de la escalera eléctrica.

### Driver ULN2003
<img width="330" height="330" alt="image" src="https://github.com/user-attachments/assets/73bfbf8a-37bc-4b18-987b-30dbe0ea5bc0" />

Actúa como interfaz entre el ESP32 y el motor paso a paso, amplificando la corriente necesaria para su funcionamiento.

### Jumpers
<img width="330" height="330" alt="image" src="https://github.com/user-attachments/assets/46293e44-4acb-4ebf-9e99-c2ed2c7859c9" />

Permiten realizar las conexiones eléctricas entre los componentes del circuito de forma rápida y segura.

### Protoboard
<img width="480" height="330" alt="image" src="https://github.com/user-attachments/assets/86a6eee8-27e9-4d29-a550-5564176fbbc7" />

Facilita el montaje y la organización del circuito sin necesidad de soldar los componentes.

### App Blynk IoT
<img width="293" height="112" alt="image" src="https://github.com/user-attachments/assets/b3f12725-6dcb-4b75-b3ed-56f2306f732e" />


---

## 🧰 Tecnologías Utilizadas

**Frontend:** Aplicación móvil desarrollada en Blynk IoT.

**Backend:** Programación en Arduino IDE para el ESP32.

**Otras herramientas:**
    
    - Modelado CAD para diseño estructural.
    - Sensores PIR y TCS230.
    - Motor paso a paso 28BYJ-48 con driver ULN2003.
    - Protoboard, jumpers y materiales para prototipado.

---

## ⚙️ Instalación

### Requisitos previos

- Arduino IDE instalado con librerías para ESP32 y Blynk.
- Cuenta activa en Blynk IoT.
- Conexión Wi-Fi estable.
- Herramientas básicas de montaje electrónico y mecánico.

## 🦾 Fases

### Fase 1 - Planificación

- Revisión de antecedentes técnicos. 
- Análisis de escaleras eléctricas reales y sistemas automatizados. 

### Fase 2 - Diseño 

- Modelado CAD de las piezas. 
- Esquematización del circuito electrónico.

### Fase 3 - Desarrollo 

- Programación en Arduino IDE. 
- Ensamblaje del circuito en protoboard. 
- Integración con app Blynk IoT. 

### Fase 4 - Pruebas y Ajustes

- Validación de sensores. 
- Ajuste de velocidad, detección de color y comportamiento adaptativo. 

### Fase 5 - Presentación

- Documentación técnica. 
- Demostración funcional del prototipo. 
