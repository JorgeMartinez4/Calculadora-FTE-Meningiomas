# Calculadora-FTE-Meningiomas
Esta es una calculadora interactiva desarrollada como parte de un estudio retrospectivo en pacientes operados por meningiomas, para estimar el riesgo postoperatorio de desarrollar fenómenos tromboembólicos (FTE) como trombosis venosa profunda (TVP) o tromboembolismo pulmonar (TEP).

🔍 Descripción
El modelo predictivo fue construido utilizando regresión logística multivariada, identificando las siguientes variables como significativas:

Edad

Índice de Masa Corporal (IMC)

Invasión de seno venoso

Edema peritumoral

Uso de corticoides preoperatorios

📊 Desempeño del modelo
Área bajo la curva (AUC): 0.99

Índice de Youden: 0.7647

Valor de corte óptimo: 0.236

Clasificación: Riesgo alto si probabilidad ≥ 0.236, Riesgo bajo si < 0.236

👨‍⚕️ Uso clínico
Esta herramienta busca asistir en la estratificación de riesgo perioperatorio. No reemplaza el juicio clínico ni protocolos institucionales.
