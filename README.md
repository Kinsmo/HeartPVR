# 🔬 HeartPVR — Physics‑Based Pressure‑Volume Relationship for Heart

This repository implements a **physics‑based pressure‑volume relationship of Heart (HeartPVR)** for cardiac research.
The model describes both the **end‑diastolic pressure‑volume relationship (EDPVR)** and the
**end‑systolic pressure‑volume relationship (ESPVR)** using a physically grounded framework.

---

## 📌 Overview

The HeartPVR model provides:

- A **physics‑based mathematical description** of left ventricular pressure‑volume behavior
- Python implementations for generating **EDPVR** and **ESPVR** curves
- Example scripts and figures demonstrating model outputs

This work is based on the publication:

> **Zhang Y, Kalhöfer‑Köchling M, Bodenschatz E, Wang Y (2023)**  
> *Physical model of end‑diastolic and end‑systolic pressure‑volume relationships of a heart*  
> *Frontiers in Physiology*, 14:1195502

---

## 🧠 Motivation

Pressure‑volume (PV) relationships are fundamental to understanding cardiac mechanics.
While many traditional models rely on empirical curve fitting, **HeartPVR is derived from physical principles**,
allowing more direct interpretation of myocardial mechanical properties and physiological changes.

---

## 📂 Repository Structure

```
HeartPVR/
├── Demo 1 EDPVR generated from HeartPVR model.png
├── Demo 2 EDPVR and ESPVR generated from HeartPVR model.png
├── Demo 1 EDPVR.py
├── Demo 2 EDPVR and ESPVR.py
├── heartpvr_lib.py
├── heartpvr_help_functions.py
├── LICENSE
└── README.md
```

---

## 🐍 Requirements

- Python 3.7+
- NumPy
- SciPy
- Matplotlib

```bash
pip install numpy scipy matplotlib
```

---

## 🚀 Usage

```bash
python "Demo 1 EDPVR.py"
python "Demo 2 EDPVR and ESPVR.py"
```

---

## 📖 Citation

```
Zhang Y, Kalhöfer‑Köchling M, Bodenschatz E, Wang Y (2023).
Physical model of end‑diastolic and end‑systolic pressure‑volume relationships of a heart.
Frontiers in Physiology, 14:1195502.
```

---

## 🌐 Related

https://physical-pvr.streamlit.app/

---

## 📜 License

MIT License
