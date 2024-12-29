# Gemini Chatbot with Python

ทดลองสร้าง chatbot โดยใช้  **Gemini API** with Python.

---

## Python libraries ที่ใช้: 

- `google-generativeai`
- `python-dotenv`

Install them using `pip`:

```bash
pip install google-generativeai python-dotenv
```

---

## Setup

### 1. ตั้งค่า GEMINI_API_KEY

สร้างไฟล์ชื่อ `.env` ในไดเรกทอรีหลักของโปรเจกต์ จากนั้นเพิ่มบรรทัดนี้ในไฟล์ `.env` file, โดยแทนที่ `YOUR_API_KEY` ด้วย Gemini API key ของคุณ:

```env
GEMINI_API_KEY=YOUR_API_KEY
```

### 2. สร้างไฟล์ Python Script

สร้างไฟล์ชื่อ `chat.py` และเขียนโค้ดสำหรับแชทบอทโดยใช้ไลบรารี `google-generativeai` ให้แน่ใจว่าสคริปต์สามารถอ่าน API key จากไฟล์  `.env` file.

---

## Run the Chatbot

To start the chatbot, simply run the script:

```bash
python chat.py
```

---


Happy coding! 🚀
