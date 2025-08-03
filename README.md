# 🩺 Agentic AI Health Symptom Checker

## 📌 Overview
The **Agentic AI Health Symptom Checker** is an AI-powered system that interprets user-reported symptoms, retrieves verified medical data, and delivers structured, multilingual health guidance.  
It helps users:
- Understand **probable conditions**
- Get **urgency levels**
- Learn **home remedies & self-care tips**
- Know **when to consult a doctor**
- Always receive a **Result** disclaimer for safety

---

## 🚨 Problem Statement
Many individuals struggle to access **reliable health guidance**.  
Searching symptoms online often leads to **misinformation** and confusion.  
Language barriers and limited healthcare access make the situation worse.  
Current symptom checkers lack **accuracy, context, and trusted data sources**.

---

## 💡 Proposed Solution
Our solution analyzes user symptoms in **natural language** and provides **safe, educational, and referral-based recommendations**.

### Key Features:
1. **Data Collection**  
   - Collect user symptom descriptions via chat or voice  
   - Retrieve verified data from WHO, CDC, and official health portals  
2. **Data Preprocessing**  
   - Handle typos, incomplete sentences, multilingual inputs  
3. **AI Symptom Analysis**  
   - Provide probable causes, urgency, remedies, and medical advice triggers  
4. **Deployment**  
   - Mobile and web chatbot interface  
5. **Evaluation**  
   - Measure accuracy, clarity, and user satisfaction against medical expert reviews

---

## 🛠 System Development Approach

### **Hardware Requirements**
- Intel i5 / AMD Ryzen 5 or higher
- 8GB RAM minimum (16GB recommended)
- 256GB SSD storage

### **Software Requirements**
- IBM Cloud Lite Account
- Python 3.8+
- Web Browser (Chrome/Edge/Firefox)
- Internet Connection

### **Libraries & Tools**
- **IBM Watsonx**
- **LangChain**
- Python Libraries (for optional backend integration)

---

## 📋 Output Format
When a user enters symptoms, the system responds as follows:

1. **Probable Condition(s)** – 2–3 likely conditions, ranked by probability  
2. **Urgency Level** – Low, Moderate, or High, with explanation  
3. **Home Remedies & Self‑Care Tips** – Evidence-based recommendations  
4. **When to Consult a Doctor** – Warning signs and escalation triggers  
5. **Result** –  
   > This is general health information and not a substitute for professional medical advice. Consult a qualified healthcare provider for personalized diagnosis and treatment.

---

## 🖼 Example Output
**Input:**  
`User Symptoms: sore throat, mild fever, difficulty swallowing`

**Output:**  
1. **Probable Condition(s):**  
   - Pharyngitis  
   - Tonsillitis  
   - Laryngitis  

2. **Urgency Level:** Low to Moderate – Monitor symptoms; see doctor if worsening.  

3. **Home Remedies & Self‑Care Tips:** Warm fluids, saltwater gargle, lozenges, rest.  

4. **When to Consult a Doctor:** High fever, severe swelling, persistent symptoms >7 days.  

5. **Result:** This is general health information and not a substitute for professional medical advice. Consult a qualified healthcare provider for personalized diagnosis and treatment.

---

## 🚀 Deployment
1. Log in to IBM Cloud and search **Watsonx**  
2. Create a **new project** in Watsonx  
3. Open **Agent Lab** and configure:  
   - Setup  
   - Configuration  
   - Knowledge  
   - Tools  
4. Define **agent instructions** with the above output format  
5. Deploy chatbot on mobile/web platforms

---

## 📈 Future Scope
- Integrate **wearable health data** for real-time symptom tracking  
- Expand **multilingual support**  
- Enable **telemedicine integration** for direct doctor consultations  
- Add **predictive analytics** for early disease detection

---

## 📚 References
- [IBM Watsonx Documentation](https://cloud.ibm.com/watsonx/overview)  
- Wang, Y., & Kung, L. (2020). *AI in healthcare: Opportunities and challenges*. **Journal of Medical Systems**, 44(9), 1–12.  
- Rajpurkar, P., et al. (2022). *AI in health and medicine*. **Nature Medicine**, 28, 31–38.  

---

## 🏆 IBM Certifications
- Getting Started with AI *(Credly Certificate)*  
- Journey to Cloud *(Credly Certificate)*  
- RAG Lab 

---

## 🙏 Acknowledgements
Developed by **Chaitanya Bhargava**  
Banarsidas Chandiwala Institute of Information Technology, Delhi  
