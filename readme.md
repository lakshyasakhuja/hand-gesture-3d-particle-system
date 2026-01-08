# Hand-Gesture Controlled 3D Particle System (AI + Computer Vision)

This repository contains a **personal AI-powered interactive graphics project**, combining **real-time hand-tracking**, **3D particle simulation**, and **gesture-based control** using modern web technologies.

The project uses **AI computer vision models** to interpret hand gestures from a webcam and translate them into dynamic transformations of a **3D particle system**, creating an immersive, real-time human–computer interaction experience.

---

## 📘 Project Overview

This project explores how **AI perception models** can be integrated with **real-time graphics engines** to create natural, intuitive interaction systems.

Using a live webcam feed, the system tracks hand landmarks in real time and maps gestures to visual transformations such as:

- Morphing between complex 3D shapes  
- Expanding and contracting particle structures  
- Rotating and colouring particle systems dynamically  

The result is an interactive, responsive 3D environment controlled entirely through **hand gestures**, without any physical controllers.

---

## 🧠 Core Concepts & Motivation

Traditional user interfaces rely heavily on keyboards, mice, or touch input. This project was motivated by the question:

> *How can AI-driven perception enable more natural, embodied forms of interaction?*

By combining **computer vision**, **gesture recognition**, and **3D graphics**, this project demonstrates how AI can bridge the gap between physical movement and digital environments — a key concept in areas such as:
- Human–Computer Interaction (HCI)  
- Creative AI  
- AR/VR interfaces  
- Interactive visualisation  

---

## 🖐️ AI Hand-Tracking & Gesture Control

The system uses **MediaPipe Hands**, an AI-based hand-tracking model, to detect and track 21 hand landmarks in real time.

Recognised gestures and mappings include:

- ✌️ **Victory / Peace sign** → Cycle through 3D shapes  
- 👌 **Pinch gesture** → Expand or contract particle structures  
- ✊ **Fist gesture** → Collapse particles toward the core  
- Hand position (X/Y) → Control rotation speed and colour gradients  

Gesture logic is implemented with debouncing to ensure smooth, intentional interaction.

---

## 🌌 3D Particle System & Shape Morphing

The visual system is built using **Three.js**, rendering **12,000+ particles** in real time.

Particles dynamically morph between mathematically defined 3D shapes, including:

- Sphere  
- Heart (parametric curve)  
- Saturn-style planet with rings  
- Flower / rose curve  
- Torus  

Particles interpolate smoothly between target positions, creating fluid transitions rather than abrupt shape changes.

---

## ⚙️ Technical Architecture

The project is implemented as a **single-file, self-contained web application**, making it easy to run locally or deploy.

Key components:
- **MediaPipe Hands** → AI hand landmark detection  
- **Three.js** → 3D rendering and animation  
- **WebGL** → GPU-accelerated particle rendering  
- **JavaScript (ES Modules)** → Real-time logic and animation loop  

The architecture cleanly separates:
- AI perception  
- Gesture interpretation  
- Visual transformation  
- Rendering and animation  

---

## 📂 Repository Structure

```text
hand-gesture-3d-particles/
├── index.html
├── assets/
│   └── demo_images/
├── README.md
````

The entire application runs directly from `index.html` — no build tools or frameworks required.

---

## 🧠 Key Learnings

* Integrating AI perception models into real-time systems
* Mapping noisy sensor data to stable interactive controls
* Designing gesture-based interaction logic
* Optimising GPU-based particle systems
* Combining mathematics, graphics, and AI into a cohesive system

---

## 🛠 Tools & Technologies

* **JavaScript (ES6+)**
* **Three.js**
* **MediaPipe Hands**
* **WebGL**
* **Computer Vision**
* **AI-based Gesture Recognition**
* **Creative Coding & Interactive Systems**

---

## 📝 Significance

This project represents a **self-directed exploration** at the intersection of:

* Artificial Intelligence
* Real-time graphics
* Human–Computer Interaction

It demonstrates the ability to:

* Design interactive systems from first principles
* Work directly with AI models rather than abstractions
* Build visually compelling, technically complex applications

This is my **most experimental and technically expressive project** to date.