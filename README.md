# Code-Mixed Information Retrieval (Bengali-English) 🔍📑  

A **Natural Language Information Retrieval Project** focused on **Roman transliterated Bengali-English code-mixed text**.  
The project develops mechanisms to identify and return the **most relevant answers** from informal online community conversations.  
<br>Project descriptioin: https://cmir-iitbhu.github.io/cmir/index.html

---

## 📂 Project Information  

- **Type:** Information Retrieval (IR) Project  
- **Language:** Bengali-English (Roman Script, Code-Mixed)   
- **Main Output:** Evaluation of system performance using IR and determination of Mean MAP scores to check the relavance. 

> ⚠️ Retrieval happens at the **document level**. A document is considered relevant if it contains an answer to the query.  

---

## 🔑 Project Objectives  

### 1️⃣ Address Code-Mixed Challenges  
- Handle **Roman transliterated Bengali mixed with English**.  
- Manage **non-standardized spellings** and **colloquial language**.  

### 2️⃣ Develop Effective Retrieval Mechanism  
- Given a **natural language query** in code-mixed text, return the most **relevant documents**.  
- Provide **document-level retrieval** (not just snippets).  


👉 Dataset represents **real-world challenges**:  
- Informal language  
- Roman transliteration of Bengali  
- Mixed use of Bengali & English  

---

## ⚙️ Implementation Details  

### 🔹 File 1: `filemerger.ipynb`  
- Merges multiple dataset components into one file.  
- Produces **`MergedFile.csv`** containing the complete dataset.  

### 🔹 File 2: `newTechnique_Encoding.ipynb`  
- Implements a model to calculate the **Mean Mapping Score (MMS)**.
- Uses three different models to obtain the MMS: **`Cross Encoder`**, **`Bi-Encoder`**, **`T5 Model`**
- Used for performance evaluation and encoding-based analysis.  

---

## 🚀 Applications  

- Information discovery in **online migrant communities**.  
- Q&A support for **regional user groups**.  
- Research benchmark for **code-mixed language IR**.  
- Extendable to **other Indian languages** facing similar challenges.  

---

## 🔮 Future Scope  

- Expanding dataset to cover **more regional languages** in India.  
- Integrating **deep learning models** (e.g., multilingual transformers).  
- Establishing **standardized benchmarks** for code-mixed retrieval tasks.  

---

## 👨‍💻 Contributor:  

**Hemant Prakash**  
- Integrated B.Tech-M.Tech in Computer Science & Engineering  
- Semester 4
- Central University of Jharkhand,Ranchi.

