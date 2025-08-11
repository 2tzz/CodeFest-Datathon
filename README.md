# RootCode Urban Challenge – CodeFest Datathon 2025  

##  Introduction  
The GENZ Urban Challenge is part of **SLIIT CodeFest Datathon 2025**, hosted by **RootCode**, focusing on enhancing communication between the public and urban authorities.  
The goal is to create a **citizen-driven platform** that allows people to report urban issues — such as potholes, illegal parking, vandalism, or littering — simply by uploading an image.  

Your system must:  
1. **Identify multiple urban issues** present in a single image.  
2. **Classify each issue** into a main category and a sub-category.  
3. **Protect privacy** by anonymizing images before processing.  

---

## 🎯 Tasks  
### 1. Anonymize Images  
- Remove or blur identifiable personal information in images (faces, license plates, private property).  
- Apply anonymization **before** training and inference.  

### 2. Classify Multiple Urban Issues  
- Detect **main categories** and **sub-categories** for each visible issue.  
- Support multiple issues per image.  

**Example Category Hierarchy:**  
| Main Category       | Sub-Category                |  
|--------------------|-----------------------------|  
| Road Issues        | Pothole Issues               |  
|                    | Damaged Road                 |  
|                    | Illegal Parking              |  
|                    | Broken Road Sign             |  
| Public Cleanliness | Littering / Garbage          |  
| Environmental      | Vandalism                    |  

---

## 🗂 Data Sources  
You may create your own dataset or use publicly available sources (with proper attribution).  

Example datasets:  
- [Urban Trash Dataset](https://www.kaggle.com/datasets/dataclusterlabs/domestic-trash-garbage-dataset)  
- [Pothole and Speed Breaker Detection](https://universe.roboflow.com/navrachana-university-nydun/pothole-and-speed-breaker-detect)  
- [Graffiti & Vandalism Dataset](https://universe.roboflow.com/hruts-workspace/graffiti-l6az9)  
- [Damaged Road Signs](https://universe.roboflow.com/jayke-boghean-2pxtg/damaged-signs-multi-label)  
- [Illegal Parking Dataset](https://universe.roboflow.com/parking-amu50/illegal-parking)  

---

## 🏗 Deliverables  
- **Architecture Diagrams** – Model and preprocessing pipeline.  
- **Report** – Approach, insights, preprocessing methods, evaluation metrics.  
- **Trained Model** – `.h5` or `.pkl` format.  
- **Notebooks** – All training & preprocessing notebooks (`*_FinalNotebook.ipynb` for final model).  
- **Demo Video** – 3–5 min YouTube walkthrough.  
- **Dataset** – Split into training, validation, and test sets.  

---

## 🧮 Evaluation  
Models will be judged on:  
- **Accuracy** – Correct classification of main & sub-categories.  
- **Classification Performance** – Handling multiple distinct issues per image.  
- **Anonymization Quality** – Privacy protection effectiveness.  

**Judging Criteria:**  
- Data Wrangling & Dataset Creation – 35%  
- Model & Architecture Implementation – 40%  
- Model Evaluation – 15%  
- Demo Video – 10%  

---

## 📊 Architecture Diagram  
![Architecture Diagram](UrbanChallenge/architecture.png)  

---

## 📜 Rules  
- No multimodal LLMs (e.g., OpenAI GPT, Claude) for model training.  
- All datasets must comply with competition rules.  
- Submission after the deadline will not be accepted.  

---

## 📂 Folder Structure  
