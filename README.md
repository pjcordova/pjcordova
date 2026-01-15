<p align="center">
  <img src="https://capsule-render.vercel.app/render?type=waving&color=0e75b6&height=220&section=header&text=Piero%20Cordova&fontSize=80&fontColor=ffffff&animation=fadeIn&fontAlignY=35" />
</p>

<p align="center">
  <a href="https://pjcordova-portafolio.streamlit.app">
    <img src="https://img.shields.io/badge/Status-Open%20to%20Work-success?style=for-the-badge&logo=linkedin" alt="Open to Work"/>
  </a>
  <a href="https://pjcordova-portafolio.streamlit.app">
    <img src="https://img.shields.io/badge/App-Streamlit%20Cloud-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white" alt="Streamlit App"/>
  </a>
</p>

# 👋 Hola, soy Piero Cordova
### 🚀 Data Engineer | Cloud Systems Integrator | Full Stack Developer

<p align="left">
  <img src="https://komarev.com/ghpvc/?username=pjcordova&label=Profile%20views&color=0e75b6&style=flat-square" alt="pjcordova" />
</p>

## 💡 Sobre mí
Ingeniero de Sistemas en formación (UTP) enfocado en **Arquitectura de Datos**, **Machine Learning** y **Desarrollo Cloud**. 

Mi background manejando lógica de negocio en **Oracle WMS** me permite entender no solo el código, sino el *flujo operativo* de los datos en entornos logísticos e industriales. Actualmente, diseño soluciones que conectan bases de datos transaccionales con dashboards de predicción.

- 🔭 **Actualmente trabajando en:** Portafolio Full Stack con **Supabase**, **Scikit-Learn** y **Python**.
- 🌱 **Especializándome en:** Data Engineering Pipelines & AI Integration.
- ⚙️ **Mi Stack Favorito:** Python + SQL + Streamlit + Cloud DBs.
- 🎯 **Objetivo:** Construir sistemas que transformen datos crudos en predicciones de negocio.

---

## 🛠️ Tech Stack & Herramientas

### ☁️ Cloud & Database Architecture
[![My Skills](https://skillicons.dev/icons?i=supabase,postgres,aws,mysql,oracle,docker,linux)](https://skillicons.dev)

### 📊 Data Science & AI
[![My Skills](https://skillicons.dev/icons?i=python,sklearn,pandas,numpy,fastapi,java)](https://skillicons.dev)

### 🎨 Frontend & Visualization
[![My Skills](https://skillicons.dev/icons?i=streamlit,powerbi,react,html,css,git,github)](https://skillicons.dev)

---

## 🚀 Proyectos Destacados (Repositorios)

| Proyecto | Rol & Tech Stack | Descripción |
| :--- | :--- | :--- |
| **[🏭 Enterprise ERP Data Warehouse](https://github.com/pjcordova/enterprise-erp-sql-project)** | **Data Engineer** <br> `Python` `SQL` `ETL` | Infraestructura de datos corporativa con Triggers, Stored Procedures y arquitectura Snowflake en la nube. |
| **[🤖 Peru Market Predictor](https://github.com/pjcordova/peru-market-predictor)** | **Data Scientist** <br> `Scikit-Learn` `Time-Series` | Sistema de predicción financiera con IA que proyecta tendencias económicas a 30 días. |
| **[🛒 Retail Inventory BI](https://github.com/pjcordova/retail-inventory-analytics)** | **BI Analyst** <br> `Power BI` `DAX` `Modeling` | Dashboard estratégico para control de mermas y optimización de stock (Pareto ABC). |

---

## 🌟 Proyecto Insignia: Portafolio Centralizado

> **[Ver Aplicación en Vivo](https://pjcordova-portafolio.streamlit.app)** > Plataforma que integra todos los proyectos anteriores en una sola interfaz web.

**Arquitectura del Sistema:**
```mermaid
graph LR
    User([Usuario / Reclutador]) -- HTTPS --> Streamlit(Frontend App)
    Streamlit -- Python Driver --> Pooler{Connection Pooler}
    Pooler -- Puerto 6543 --> Supabase[(Supabase PostgreSQL)]
    Streamlit -- Datos Históricos --> MLEngine(AI Engine / Scikit-Learn)
    MLEngine -- Predicción Futura --> Streamlit
    Streamlit -- Render --> User
