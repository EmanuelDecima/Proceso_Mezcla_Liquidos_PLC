# 🏭 Proceso de Mezcla de Líquidos Controlado por PLC

## 📌 Descripción general

Este proyecto implementa el control automático de un proceso de **mezcla de líquidos** mediante un **PLC**, simulando una operación típica de entornos industriales como:

- Industria alimentaria  
- Industria química  
- Procesos de bebidas  
- Sistemas batch  

El sistema permite controlar el llenado, mezcla y gestión del proceso de forma automatizada, garantizando **repetibilidad, eficiencia y control del proceso**.

---

## ⚙️ Objetivos del proyecto

- Diseñar un sistema de control secuencial para mezcla de líquidos  
- Implementar lógica de control en PLC (tipo Ladder)  
- Simular el comportamiento del proceso industrial  
- Integrar sensores y actuadores típicos de planta  
- Documentar el sistema mediante esquema eléctrico/funcional  

---

## 🧩 Descripción del proceso

El sistema modela un proceso típico de mezcla:

1. Ingreso de líquido A  
2. Ingreso de líquido B  
3. Control de nivel en tanque  
4. Proceso de mezcla (agitador)  
5. Descarga del producto final  

El control se basa en lógica secuencial, donde cada etapa depende del estado del sistema (niveles, tiempos o condiciones).

---

## 🔌 Arquitectura del sistema

El sistema está compuesto por:

### 🟢 Sensores
- Sensor de nivel mínimo  
- Sensor de nivel máximo  

### 🔵 Actuadores
- Electroválvulas de entrada (líquido A y B)  
- Motor agitador  
- Válvula de descarga  

### 🧠 Control
- PLC programado en lógica Ladder  

---

## 🗺️ Esquema del sistema

El esquema completo del sistema se encuentra en el archivo PDF del repositorio:

📄 `Esquema_Proceso_Mezcla.pdf`

Este documento incluye:

- Diagrama de conexiones  
- Entradas y salidas del PLC  
- Representación de sensores y actuadores  
- Lógica general del sistema  

👉 Es clave para entender la integración hardware–control.

---

## 🔄 Lógica de control (resumen)

El proceso sigue una secuencia automática:

1. Verificación de condiciones iniciales  
2. Llenado con líquido A hasta nivel definido  
3. Llenado con líquido B  
4. Activación del agitador por tiempo determinado  
5. Descarga del tanque  
6. Reinicio del ciclo  

Este tipo de control es típico en sistemas batch industriales, donde la secuencia garantiza la calidad del producto.

---

## 🛠️ Tecnologías utilizadas

- PLC (programación Ladder)  
- Simulación de procesos industriales  
- Modelado de sistemas secuenciales  

---

## 🧪 Aplicaciones industriales

Este tipo de sistema se utiliza en:

- Producción de bebidas  
- Mezcla de químicos  
- Procesos farmacéuticos  
- Industria cosmética  

La automatización mediante PLC permite lograr:

- Mayor precisión  
- Repetibilidad del proceso  
- Reducción de errores humanos  

---

## 🚀 Posibles mejoras

- Implementación de HMI  
- Control por recetas (proporciones variables)  
- Sensores analógicos (nivel continuo)  
- Control PID del mezclado  
- Integración con SCADA  

---

## 👨‍💻 Autor

**Emanuel Decima**  
Estudiante avanzado de Ingeniería Electrónica  
Orientación: Automatización e Instrumentación Industrial  

🔗 GitHub: https://github.com/EmanuelDecima  
🔗 LinkedIn: https://www.linkedin.com/in/enrique-emanuel-d%C3%A9cima-5934b720b/