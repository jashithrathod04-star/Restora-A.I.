# 🎨 ArtRestorer AI  
### CRS Artificial Intelligence – Generative AI Summative Assessment  

---

## 👤 Student Details

- **Student Name:** Jashith Hemendra Rathod 
- **Candidate Registration Number:** 1000422  
- **CRS Name:** Artificial Intelligence  
- **Course Name:** Generative AI  
- **School Name:** Aspee Nutan Academy
- **Live Link:** https://restora-ai-nbf5s8bjghxrfzvr2maxge.streamlit.app/
    

---

# 🌍 Project Overview

## 📌 Scenario Selected
**Scenario 1 – Smart Assistance Web Application to Support Art Restoration**

ArtRestorer AI is a generative AI-powered web application that assists:

- Museum Curators  
- Art Historians  
- Conservation Specialists  
- Cultural Researchers  
- Students  

The system uses **Google Gemini API** to generate historically grounded and culturally sensitive restoration suggestions.

It bridges the gap between:

> Artificial Intelligence and Cultural Heritage Preservation

---

# 🧠 Problem Definition & Research

## 🎯 Problem Statement

Thousands of historical artworks are deteriorating due to:

- Water damage  
- Fading pigments  
- Structural cracks  
- Mold and erosion  
- Loss of documentation  

Traditional restoration requires expert knowledge and is not always accessible globally.

---

## 💡 Proposed Solution

Develop a Smart Generative AI Assistant that:

- Accepts artwork metadata (type, period, damage description)
- Optionally analyzes uploaded images
- Generates restoration strategies
- Produces cultural interpretations
- Creates visitor-friendly summaries
- Logs restoration history
- Provides real-time analytical insights

---

# 🤖 Model Integration

## Model Used

```python
model = genai.GenerativeModel("gemini-3-flash-preview")
```

API configured securely using Streamlit Secrets.

---

# 🔧 Hyperparameter Tuning

| Parameter | Purpose | Value Used |
|-----------|----------|------------|
| temperature | Controls creativity | 0.3 – 0.9 |
| top_p | Diversity sampling | 0.95 |
| top_k | Token selection filtering | 40 |
| max_output_tokens | Response length | 2048 |

### Tuning Strategy

- **0.3 temperature** → Conservative, historically safe output  
- **0.7+ temperature** → Creative stylistic reconstruction  
- Tested across Renaissance, Mughal, Gothic, Abstract artworks  

---

# 🧩 Prompt Engineering

The system dynamically builds structured prompts combining:

- Artwork Type  
- Art Period  
- Artist (optional)  
- Damage Description  
- Selected Output Format  

---

## 📌 10 Core Prompts Implemented

1. Renaissance oil painting restoration  
2. Mughal miniature floral reconstruction  
3. Sandstone sculpture facial repair  
4. 18th century silk tapestry repair  
5. Abstract expressionist texture recreation  
6. Medieval manuscript script recovery  
7. Mayan glyph carving interpretation  
8. Ajanta cave mural fading correction  
9. Ukiyo-e woodblock sun damage recovery  
10. Gothic cathedral mural crack analysis  

Each prompt is structured to reduce hallucinations and increase historical grounding.

---

# 📤 Output Types

Users can select:

- **Full Restoration Report**
- **Restoration Strategy Only**
- **Cultural Interpretation**
- **Visitor-Friendly Summary**

Each output is formatted professionally and structured clearly.

---

# 📊 Advanced Features

## 🕓 Restoration History Tracking
- Stores previous restorations in session
- Timestamp logging
- Expandable output review

## 📈 Real-Time Insights Dashboard
- Total restorations metric
- Most restored artwork type
- Most common period
- Trend analysis (line chart)
- Artwork distribution (bar chart)

## 💬 AI Chat Assistant
- Conversational restoration guidance
- Quick prompt support

## ⭐ Feedback System
- User rating (1–5)
- AI accuracy metric
- Usability scoring
- Rating distribution visualization

---

# 🧪 Model Validation & Optimization

### Testing Conducted On:
- Renaissance paintings
- Mughal miniatures
- Gothic murals
- Abstract Expressionism
- Stone sculptures
- Manuscripts

### Validation Strategy
- Compared outputs with known stylistic traits
- Cross-checked historical techniques
- Refined prompts to reduce hallucination

---

# 🖥 Web Application Design

## Built Using

- streamlit
- google-generativeai
- pandas
- matplotlib
- PIL
- datetime

---

## Key UI Features

- Cinematic splash screen  
- Animated landing page  
- Sign-up system  
- Session management  
- Glass + gold themed dashboard  
- Responsive tab structure  
- Sidebar sign-out functionality  
- Real-time metrics  

---

# 🚀 Deployment

## Files Included

- app.py  
- requirements.txt  
- README.md  

## Deployment Steps

1. Push project to GitHub repository:
   ```
   IDAI103-YourName
   ```

2. Deploy using:
   https://streamlit.io/cloud  

3. Configure Gemini API in Streamlit Secrets  

4. Test across devices  

---

# 📂 Repository Checklist

- [x] Functional app.py  
- [x] Gemini API integration  
- [x] 10+ prompts implemented  
- [x] Hyperparameter tuning  
- [x] Real-time analytics  
- [x] Feedback system  
- [x] GitHub repository accessible  
- [x] README fully documented  
- [x] Streamlit deployment link  

---

# App ScreenShots 
###Enterance Page 
<img width="1710" height="701" alt="image" src="https://github.com/user-attachments/assets/2b0c7cd2-bd17-429e-b11e-c22eee9b342e" />

--------------------------------------------------------------------------------------------------------------------------------------------------------------

###Landing Page 
<img width="1764" height="796" alt="image" src="https://github.com/user-attachments/assets/7ceadfb8-dd0b-4ba7-b354-83aed74dc069" />


--------------------------------------------------------------------------------------------------------------------------------------------------------------


###Sign up Page 
<img width="1787" height="778" alt="image" src="https://github.com/user-attachments/assets/9807fe5f-72db-4605-a97e-944444e4a13a" />


--------------------------------------------------------------------------------------------------------------------------------------------------------------



###Dashboard 
<img width="1578" height="684" alt="image" src="https://github.com/user-attachments/assets/c03b95ce-1fb6-40fc-9eec-f5f23d2952a3" />


--------------------------------------------------------------------------------------------------------------------------------------------------------------

###Side Bar 
<img width="347" height="879" alt="image" src="https://github.com/user-attachments/assets/edda03d2-b264-492c-b87d-78b5c1754ec7" />


--------------------------------------------------------------------------------------------------------------------------------------------------------------




# 🎯 Rubric Alignment (Distinction Level)

### Problem Understanding & Solution Design
✔ Real-world cultural preservation problem  
✔ AI aligned with social good  

### Prompt Engineering & Creativity
✔ 10+ structured prompts  
✔ Multi-style, multi-era coverage  

### Output Quality & Relevance
✔ Context-sensitive  
✔ Period-specific  
✔ Cultural safeguards included  

### Model Testing & Optimization
✔ Temperature tuning  
✔ Prompt refinement  
✔ Multiple art forms tested  

### Deployment & Usability
✔ Fully functional Streamlit app  
✔ Professional UI  
✔ Interactive features  

---

# 🌟 Conclusion

ArtRestorer AI demonstrates how Generative AI can:

- Assist cultural preservation  
- Enhance restoration research  
- Democratize heritage knowledge  
- Provide accessible museum-level insights  

It combines:

> Technical AI integration  
> Cultural sensitivity  
> Creative interface design  
> Real-world problem solving  

---

**End of README**
