<div align="center">

<!-- Banner -->
<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=2d6a4f,52b788,95d5b2&height=200&section=header&text=Eco-Wise&fontSize=72&fontColor=ffffff&fontAlignY=38&desc=AI-Powered%20Waste%20Classification%20for%20Sustainable%20Living&descAlignY=60&descColor=d8f3dc&animation=fadeIn" />

<!-- Badges -->
<p>
  <img src="https://img.shields.io/badge/Coding%20Camp%202026-DBS%20Foundation-1b4332?style=for-the-badge&logo=leaflet&logoColor=white" />
  <img src="https://img.shields.io/badge/Team%20ID-CC26--PSU341-52b788?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Theme-Sustainable%20Living-74c69d?style=for-the-badge&logo=springsecurity&logoColor=white" />
</p>

<br/>

> **Eco-Wise** adalah aplikasi web klasifikasi sampah cerdas berbasis AI yang membantu masyarakat memilah sampah secara tepat melalui kamera, sekaligus mendorong perubahan perilaku lewat sistem gamifikasi.

<br/>

---

## 🌿 Tentang Proyek

</div>

Krisis sampah di Indonesia semakin mendesak — dengan produksi sampah mencapai puluhan juta ton per tahun, kebiasaan mencampur sampah menjadi hambatan utama dalam proses daur ulang. **Eco-Wise** hadir sebagai solusi cerdas berbasis AI yang mengklasifikasikan sampah secara otomatis melalui kamera pengguna, menjadikan pemilahan sampah mudah, cepat, dan menyenangkan.

<div align="center">

|                🔍 Klasifikasi Real-Time                 |                   🎮 Gamifikasi                   |                 📊 Dashboard Analitik                 |
| :-----------------------------------------------------: | :-----------------------------------------------: | :---------------------------------------------------: |
| Deteksi jenis sampah via kamera menggunakan MobileNetV2 | Daily Task & Eco Points untuk memotivasi pengguna | Visualisasi data distribusi sampah berbasis Streamlit |

</div>

<br/>

---

<div align="center">

## 🗂️ Kategori Klasifikasi

</div>

```
🟢 ORGANIK        →  Sisa makanan, daun, ranting
🔵 ANORGANIK      →  Plastik, kertas, kaleng, kaca
🔴 B3             →  Baterai, cat, bahan kimia berbahaya
⚪ BUKAN SAMPAH   →  Benda sehari-hari yang bukan limbah
```

<br/>

---

<div align="center">

## 🏗️ Arsitektur & Teknologi

</div>

### 🤖 Artificial Intelligence

![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![MobileNetV2](https://img.shields.io/badge/MobileNetV2-FF6F00?style=flat-square&logo=google&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Gemini API](https://img.shields.io/badge/Gemini%20API-4285F4?style=flat-square&logo=google&logoColor=white)

> Model Deep Learning menggunakan **MobileNetV2** via TensorFlow Functional API untuk inferensi ringan dan cepat di browser. REST API inference dibangun dengan FastAPI, dilengkapi integrasi Gemini API untuk fitur generatif.

### 📊 Data Science

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![Kaggle](https://img.shields.io/badge/Kaggle-20BEFF?style=flat-square&logo=kaggle&logoColor=white)

> Dataset dikumpulkan dari Kaggle, diproses dengan Pandas & NumPy, dilengkapi augmentasi gambar, EDA, serta dashboard interaktif via Streamlit.

### 🌐 Full-Stack Web

![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind%20CSS-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-%23404d59?style=for-the-badge&logo=express&logoColor=%2361DAFB)

> Frontend dibangun dengan React + Vite + Tailwind CSS. Backend RESTful API menggunakan Express.js (Node.js) dengan integrasi model AI secara end-to-end.

<br/>

<!-- ---

<div align="center">

## 📁 Struktur Repository

</div>

```
CC26-PSU341/
│
├── 📦 eco-wise-frontend        → React + Vite + Tailwind CSS (UI & Camera Feature)
├── 📦 eco-wise-backend         → Express.js API, Database, Eco Points System
├── 📦 eco-wise-ai-model        → TensorFlow MobileNetV2 Training & FastAPI Inference
└── 📦 eco-wise-data-science    → EDA, Preprocessing, Augmentation & Streamlit Dashboard
```

<br/> -->

<!-- ---

<div align="center">

## 🗓️ Timeline Proyek

</div>

| Minggu | Fokus                              | Deliverable                                          |
| :----: | ---------------------------------- | ---------------------------------------------------- |
| **1**  | Project Planning & System Design   | Wireframe, system design, setup repo, dataset awal   |
| **2**  | Data Collection & AI Preprocessing | Dataset bersih & terstandarisasi, ready for training |
| **3**  | Model Development & Training       | Model MobileNetV2 terlatih, akurasi ≥ 85%            |
| **4**  | Web Development & Integration      | Web app + integrasi model AI end-to-end              |
| **5**  | Evaluation, Feature & Deployment   | Eco Points, Daily Task, bug fix, deployment          |

<br/> -->

<!-- ---

<div align="center">

## 🎯 Target Keberhasilan

</div>

```
✅  Akurasi model AI ≥ 85% pada testing set
✅  Klasifikasi real-time via kamera browser (< 2 detik)
✅  Integrasi frontend ↔ backend ↔ model AI berjalan end-to-end
✅  Fitur Eco Points & Daily Task aktif dan fungsional
✅  Dokumentasi proyek lengkap
```

<br/> -->

---

<div align="center">

## 👥 Tim CC26-PSU341

</div>

<div align="center">

| Nama                    |       ID       |            Role             |
| ----------------------- | :------------: | :-------------------------: |
| Syafa Ali Azmi          | CFCC190D6Y1919 | 💻 Full-Stack Web Developer |
| Iib Ibrahim             | CFCC190D6Y0578 | 💻 Full-Stack Web Developer |
| Vania Rachmawati Dewi   | CDCC201D6X0827 |      📊 Data Scientist      |
| Gigih Dwi Kartika C. W. | CDCC201D6Y2384 |      📊 Data Scientist      |
| Nayala Wulan Ramadhani  | CACC009D6X0550 |       🤖 AI Engineer        |
| Atika Pratiwi Harahap   | CACC251D6X1215 |       🤖 AI Engineer        |

</div>

<br/>

---

<div align="center">

## 🔗 Links

[![Streamlit Dashboard](https://img.shields.io/badge/Dashboard-Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)](#)
[![Live App](https://img.shields.io/badge/Live%20App-Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)](#)
[![API Docs](https://img.shields.io/badge/API%20Docs-FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)](#)

<br/>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=2d6a4f,52b788,95d5b2&height=100&section=footer&animation=fadeIn" />

_Coding Camp 2026 powered by DBS Foundation · Team CC26-PSU341 · Sustainable Living & Responsible Consumption_

</div>
