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
Ingeniero de Sistemas en formación (UTP) enfocado en **Arquitectura de Datos** y **Desarrollo Cloud**. 

Mi background manejando lógica de negocio en **Oracle WMS** me permite entender no solo el código, sino el *flujo operativo* de los datos en entornos logísticos e industriales. Actualmente, diseño soluciones que conectan bases de datos transaccionales con dashboards de alto impacto.

- 🔭 **Actualmente trabajando en:** Portafolio Full Stack con **Supabase (PostgreSQL)** y **Python**.
- 🌱 **Especializándome en:** Data Engineering Pipelines & Cloud Architecture.
- ⚙️ **Mi Stack Favorito:** Python + SQL + Streamlit + Cloud DBs.
- 🎯 **Objetivo:** Construir sistemas ETL resilientes y escalables.

---

## 🛠️ Tech Stack & Herramientas

### ☁️ Cloud & Database Architecture
[![My Skills](https://skillicons.dev/icons?i=supabase,postgres,aws,mysql,oracle,docker,linux)](https://skillicons.dev)

### 📊 Data Science & Backend logic
[![My Skills](https://skillicons.dev/icons?i=python,pandas,numpy,sklearn,fastapi,java)](https://skillicons.dev)

### 🎨 Frontend & Visualization
[![My Skills](https://skillicons.dev/icons?i=streamlit,powerbi,react,html,css,git,github)](https://skillicons.dev)

---

## 🚀 Proyecto Insignia: Data Engineering Portfolio

> **[Ver Aplicación en Vivo](https://pjcordova-portafolio.streamlit.app)** > Un sistema centralizado Full Stack desplegado en la nube.

**Arquitectura del Sistema:**
```mermaid
graph LR
    User([Usuario / Reclutador]) -- HTTPS --> Streamlit(Frontend App)
    Streamlit -- Python Driver --> Pooler{Connection Pooler}
    Pooler -- Puerto 6543 --> Supabase[(Supabase PostgreSQL)]
    Supabase -- Datos JSON --> Streamlit
    Streamlit -- Render --> User
