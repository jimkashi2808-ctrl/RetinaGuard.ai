# 👁️ RetinaGuard AI — Autonomous Medical AI Screening System

> **Live Web Application:** [https://joy-render-world.lovable.app](https://joy-render-world.lovable.app)  
> **Hackathon:** Bharat Builds Tour 2026 (WeMakeDevs & AWS Builder Center)  
> **Track:** Ship It (Deployed)

---

## 📌 Overview & Problem Statement
Modern society faces critical healthcare bottlenecks where expanding populations outstrip vital human resource capacities. In India, over 70 million adults live with diabetes, putting them at high risk of Diabetic Retinopathy—a leading cause of permanent blindness if left undiagnosed. 

While medical technology is advanced, healthcare delivery systems remain severely underdeveloped in rural and low-income areas. Catching blinding eye diseases early requires an expert to manually inspect specialized fundus images of the eye[cite: 1]. Because specialists are heavily concentrated in wealthy urban centers, millions of underserved individuals in rural communities have effectively zero access to timely diagnostic screenings[cite: 1].

## 💡 The Solution: RetinaGuard AI
**RetinaGuard AI** bridges this diagnostic bottleneck by combining accessible smartphone fundus photography with cloud-native multimodal AI vision[cite: 1].

1. **Accessible Image Capture:** A local health worker captures a retinal photo using a low-cost camera attachment on a standard smartphone[cite: 1].
2. **Multimodal AI Analysis:** The image and patient metadata are transmitted via AWS API Gateway to **Amazon Bedrock (Claude 3.5 Sonnet Vision)**[cite: 1]. The AI scans for micro-aneurysms, hemorrhages, exudates, and structural lesions in seconds[cite: 1].
3. **Instant Automated Triage:** The system automatically classifies patient risk into actionable categories—**Healthy**, **Mild (Monitor locally)**, or **Urgent Referral (Immediate hospital routing)**[cite: 1].

---

## 🏗️ Technical Architecture & AWS Stack
## 📜 Medical Disclaimer
RetinaGuard AI is developed as a prototype demonstration for educational and preliminary screening assistance purposes only. It is not a replacement for professional ophthalmological diagnosis[cite: 1]. All flagged cases must be verified by a certified healthcare professional[cite: 1].
