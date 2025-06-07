# 🎓 Education Gap Validator

An AI-powered tool to analyze academic certificates and detect education gaps based on semester/year patterns. This project uses Optical Character Recognition (OCR) to extract content from uploaded PDF or image-based certificates, and applies logic to validate semester sequences, date gaps, and progression consistency.

---

## 🚀 Features

- 🔍 Extracts text from academic certificates using Tesseract OCR
- 📅 Identifies missing semesters or year gaps automatically
- 📄 Accepts image or PDF inputs
- 🧠 Smart validation logic based on expected semester flow
- 💡 Designed to assist HR/college admissions in validating education history
- 🎨 Clean frontend interface for file upload and results

---

## 📁 Folder Structure

education-gap-validator/  
│  
├── app.py  
├── ocr_reader.py          
├── test_ocr.py             
├── requirements.txt       
│   
├── templates/  
│   ├── index.html    
│   └── result.html   
│  
├── Uploads/  
│   └── (empty or sample test files)    


---

## 🛠️ Installation

### 1️⃣ Clone the Repository
git clone https://github.com/RasagnaRayasam/education-gap-detector.git
cd education-gap-detector


### 2️⃣ Set Up a Virtual Environment (Optional but Recommended)
python -m venv venv
venv\Scripts\activate   # Windows
# or
source venv/bin/activate  # Linux/macOS


### 3️⃣ Install Dependencies
pip install -r requirements.txt


### 4️⃣ Run the App
python app.py

---

📌 Future Enhancements

📝 Add digital signature validation

🌐 Upload to Streamlit Cloud or Hugging Face Spaces

📊 Build a dashboard for reviewing flagged gaps

---

👩‍💻 Author
Rasagna Rayasam
AI/ML & Web Development Enthusiast
