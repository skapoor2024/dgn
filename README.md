# dgn
Deep Generative Models
---

## **📅 1–2 Hour Daily Plan for Diffusion Models (3–4 Months Plan)**  
Each week will have a mix of:  
✅ **Theory** (reading papers, understanding concepts)  
✅ **Implementation** (coding diffusion models from scratch & using existing frameworks)  
✅ **Experiments** (training models, tweaking hyperparameters, exploring applications)  

---

## **🗓️ Phase 1: Foundations (Weeks 1–4)**
### **Daily Routine (~1-2 hours)**
🔹 **Days 1–3:** Read & summarize the **DDPM (Denoising Diffusion Probabilistic Models) paper** by Ho et al. (NeurIPS 2020).  
🔹 **Days 4–5:** Implement a simple **Gaussian diffusion process** (forward and reverse process).  
🔹 **Days 6–7:** Work through **Diffusion Models in PyTorch** (basic implementation).  

### **Week 2–3: Deep Dive into Diffusion Basics**
🔹 **Read & summarize** Variance Scheduling & Score Matching.  
🔹 **Implement DDPM from scratch** (focus on noise scheduling, training objectives).  
🔹 **Experiment with hyperparameters** (changing beta schedules, different noise levels).  
🔹 **Reproduce & modify the DDPM model using Hugging Face Diffusers library.**  

### **Week 4: Applications & Exploring U-Net Architecture**
🔹 Study **U-Net & ResNet backbones** used in diffusion models.  
🔹 **Modify the U-Net architecture** to experiment with different structures.  
🔹 Try **conditional DDPM** (e.g., class-conditioned generation).  

---

## **🗓️ Phase 2: Advanced Techniques (Weeks 5–8)**
### **Week 5–6: Understanding and Implementing Score-Based Generative Models**
🔹 Read **Score-Based Generative Models (SDEs) by Song et al. (ICLR 2021)**.  
🔹 Implement **Stochastic Differential Equations (SDEs)** in diffusion modeling.  
🔹 Train a **continuous-time diffusion model** using Score Matching with Langevin Dynamics.  

### **Week 7–8: Speeding Up Diffusion & Applying in Real-World Tasks**
🔹 Study **DDIM (Denoising Diffusion Implicit Models)** for faster sampling.  
🔹 Implement DDIM from scratch and compare inference speed with DDPM.  
🔹 Work with **Latent Diffusion Models (LDMs)** for high-resolution image generation.  

---

## **🗓️ Phase 3: Research-Level Exploration (Weeks 9–12)**
### **Week 9–10: Fine-Tuning & Applications**
🔹 Fine-tune pretrained diffusion models on a small dataset (e.g., medical images).  
🔹 Experiment with **ControlNet** to condition diffusion models on additional inputs.  

### **Week 11–12: Latest Research & Implementing Novel Ideas**
🔹 Read **recent diffusion-based research papers** (2023–2024).  
🔹 Implement a novel modification to a diffusion model for your research focus.  
🔹 Write a short blog/notebook summarizing your learnings and findings.  

---

## **🛠️ Recommended Resources**
📖 **Papers to Read (Must-Read)**
- [DDPM (Denoising Diffusion Probabilistic Models)](https://arxiv.org/abs/2006.11239)  
- [DDIM (Fast Inference for Diffusion Models)](https://arxiv.org/abs/2010.02502)  
- [Score-Based Generative Modeling (SDEs)](https://arxiv.org/abs/2011.13456)  
- [Latent Diffusion Models (Stable Diffusion)](https://arxiv.org/abs/2112.10752)  

📚 **Courses & Blogs**
- Stanford CS236 (Your current course)  
- Hugging Face Diffusers Tutorials  
- **Andrej Karpathy’s "Let's Build GPT" series** (helps with generative modeling mindset)  

---

## **🚀 How to Track Progress?**
✅ **Create a GitHub repo** → Push weekly code & research summaries.  
✅ **Write a small blog or notes** → Helps clarify concepts.  
✅ **Reproduce results from 2-3 recent diffusion papers**.  
