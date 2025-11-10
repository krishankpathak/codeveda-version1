CodeVeda Final — Perfect Hospital System (Zero-Terminal)
=======================================================
This package is a fully offline, browser-based simulation of a hospital infection-tracing system.
- Open `frontend/index.html` in Chrome/Edge (desktop recommended) — everything runs automatically.
- Real-time simulated BLE network, heatmap, EHR, contact tracing, analytics. No terminal required.

# 🧠 CodeVeda — Intelligent Hospital Infection Tracking System (Zero-Terminal | Real-Time)

**CodeVeda** is an AI + IoT–driven hospital infection tracking platform that digitally maps **how infections spread** through movement, contact, and hospital workflows — powered by **BLE-based simulation**, **EHR data**, and **ML-based risk prediction** — all visualized in a **real-time 3D heatmap dashboard**, with **zero terminal setup**.

---

## 🌍 Problem Overview: Why Hospitals Need This

> “Why use IoT? The patient is lying on a bed — we can just note who visited them.”  
> Sounds logical, but here’s the hidden truth 👇

In real hospitals like **AIIMS**, **KGMU**, **Apollo**, or **Fortis** —  
hundreds of people move across **wards, ICUs, corridors, and operation theatres** every hour.  
It’s impossible for humans to manually track who met whom, where, and when.  

But infection doesn’t spread just by *visits*.  
It spreads through a **chain of movements** — nurses, cleaners, tools, and shared surfaces.

### 🦠 Example: How Infection Actually Spreads

- Nurse touches **Patient A’s** bed (infected with MRSA)
- The same nurse adjusts **Patient B’s** oxygen mask  
  ➜ **Transmission occurs**
- A trolley carrying medicines moves from one room to another  
- A cleaner mops two different wards  

👉 Infection spreads invisibly through **movement and overlap**, not just “visits”.

---

## 💡 What CodeVeda Actually Does

CodeVeda doesn’t just track *who visited whom* —  
it builds a **digital contact and movement map** of the hospital.

- Each staff/visitor badge emits a small **BLE signal**
- Gateways (IoT readers) record **entry time, duration, and proximity**
- The system connects all data streams into a **real-time movement graph**

Then, when a lab confirms infection (via EHR), CodeVeda instantly shows:

> “Patient A was visited by Nurse Rina and Cleaner Mohan.  
> Both entered ICU-3 after that. Two other patients were exposed.”

This type of **real-time exposure tracing** is impossible to do manually —  
but CodeVeda makes it instant, automatic, and evidence-based.

---

## 🇮🇳 Why This System Matters for India

- Hospital-acquired infections (HAIs) affect **10–15%** of Indian patients  
- MDR (multi-drug resistant) pathogens are rising  
- NABH mandates hospitals to **report infection data**, but most still use paper

CodeVeda offers:
- 🧠 **Automation** — no manual logs  
- ⏱️ **Real-time data** — continuous BLE tracking  
- ✅ **Evidence-based analytics** — integrates lab + movement data

Even small hospitals can adopt it as a **research + social impact project**.

---

## ⚙️ Deployment Feasibility in India

| Level | Description | Cost Estimate |
|-------|--------------|----------------|
| Prototype | BLE beacons in 2–3 rooms, 10 staff badges | ₹4,000–₹8,000 |
| Pilot Ward | 50 badges + 10 gateways | ₹20,000–₹40,000 |
| Full Deployment | Gateways per ward | Scalable, affordable |

Hardware is **small, reusable**, and easily sourced locally.

---

## 🧩 System Architecture


