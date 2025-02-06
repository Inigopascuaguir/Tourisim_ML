# 🚧 Tourist Travel Modes in Europe - Machine Learning Project 🚧

![Travel Modes](images/Budget-friendly-travel-destinations-in-Europe.jpg) 
*Project focused on predicting key tourist behaviors to optimize travel services.*

---

## 📌 Descripción del Proyecto
Este proyecto utiliza el dataset **["Tourist Travel Modes in Europe"](https://www.kaggle.com/datasets/ashaychoudhary/tourist-travel-modes-in-europe-dataset/data)** para desarrollar modelos de Machine Learning que permitan predecir variables clave relacionadas con los hábitos de viaje de turistas en Europa. El objetivo es proporcionar insights accionables para empresas del sector turístico.

### Dataset Overview
El dataset contiene las siguientes variables:
- `Tourist_ID`: Identificador único del turista.
- `Country_Visited`: País europeo visitado.
- `City_Visited`: Ciudad visitada.
- `Mode_of_Travel`: Medio de transporte utilizado (Tren, Autobús, Avión, Coche, Bicicleta).
- `Travel_Duration_Days`: Duración de la estancia (días).
- `Number_of_Companions`: Número de acompañantes.
- `Total_Travel_Cost`: Costo total del viaje (€).
- `Accommodation_Type`: Tipo de alojamiento (Hotel, Hostal, Airbnb, Camping).
- `Main_Purpose`: Propósito del viaje (Ocio, Negocios, Visita familiar).
- `Season_of_Visit`: Temporada del viaje (Primavera, Verano, Otoño, Invierno).

---

## 🎯 Variables Objetivo (Targets)

### 1. **`Total_Travel_Cost` (Regresión)**  
**Objetivo**: Predecir el costo total del viaje en función de variables como la duración, el medio de transporte, el alojamiento y la temporada.  
**Implicación Empresarial**:  
- Permite a **agencias de viajes** ofrecer paquetes personalizados ajustados al presupuesto del cliente.  
- Ayuda a plataformas como **Booking** o **Airbnb** a implementar precios dinámicos basados en la demanda estacional o el perfil del turista.  
- Facilita la identificación de segmentos de alto gasto para estrategias de marketing premium.

### 2. **`Season_of_Visit` (Clasificación)**  
**Objetivo**: Predecir la temporada en la que un turista realizará su viaje según sus preferencias y características.  
**Implicación Empresarial**:  
- Empresas de transporte (ej: aerolíneas) pueden optimizar rutas y frecuencia de vuelos en temporadas específicas.  
- Destinos turísticos pueden planificar campañas promocionales anticipadas (ej: ofertas de invierno para esquí).  
- Hoteles y alojamientos pueden ajustar tarifas y disponibilidad para maximizar ocupación en temporadas altas.

---

## 🛠️ Estructura del Proyecto
