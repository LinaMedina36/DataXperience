# 📡 Análisis de Tráfico de Red y Predicción

## 📌 Descripción
Este proyecto analiza datos de tráfico de red capturados con Wireshark para identificar patrones de comunicación y construir un modelo predictivo base que estime el volumen de datos transferidos.

---

## 🎯 Objetivo
- Explorar el comportamiento del tráfico de red  
- Identificar protocolos y patrones relevantes  
- Construir un modelo predictivo simple e interpretable  

---

## 📊 Dataset
- Más de 394,000 registros  
- Variables clave: IP origen/destino, protocolo, tiempo relativo y bytes transferidos  
- Sin valores nulos en variables críticas  

---

## 🤖 Modelo
Se implementó una **Regresión Lineal** para estimar `bytes_transferred`.

**Resultados:**
- MAE: 241.01  
- RMSE: 558.93  
- R²: 0.54  

El modelo captura parcialmente la variabilidad del tráfico y funciona como una línea base interpretable.

---

## 🛡️ Aplicación
Este enfoque puede aplicarse en:
- Monitoreo de redes  
- Detección de anomalías  
- Análisis de ciberseguridad (SOC)  

---

## 📓 Notebook
[Ver cuaderno](https://colab.research.google.com/drive/1Bp686dV1CL0r2nkWJnYmvcAqlzRj25Mx?usp=sharing)

---

## 📊 Dashboard
[Ver en Power BI](https://app.powerbi.com/links/DwDfH-PN_A?ctid=c06fb559-1b68-4b84-a14f-47d0d837a5ab&pbi_source=linkShare)

---

## 🎥 Video
[Ver video]([LINK](https://youtu.be/pGWvjVR89kU))

---

## 🧰 Tecnologías
Python · Pandas · Scikit-learn · Wireshark · Power BI
