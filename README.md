# 603888_-_superai-s6
# Super AI Engineer Season 6 – Learning Repository

Repository นี้ใช้เก็บการเรียนรู้และการฝึกฝนด้าน Data Science และ Machine Learning ระหว่างการเตรียมตัวสำหรับโครงการ **Super AI Engineer Season 6**

เป้าหมายของ repository นี้คือการฝึกทักษะที่จำเป็นสำหรับการทำงานด้าน AI และ Data Science เช่น

- Python Programming
- Data Analysis ด้วย pandas
- Exploratory Data Analysis (EDA)
- Data Cleaning และการจัดการ Missing Values
- Feature Engineering
- Machine Learning Model เบื้องต้น

---

# โครงสร้างของ Repository

## notebooks/
เก็บไฟล์ Jupyter / Google Colab สำหรับการทดลอง วิเคราะห์ข้อมูล และฝึกเขียนโค้ด

ตัวอย่างไฟล์

- `day9_python_review.ipynb`  
  ทบทวนพื้นฐาน Python เช่น function, list, logic และการเขียนโค้ดพื้นฐาน

- `day9_EDA_practice.ipynb`  
  ฝึกการสำรวจข้อมูล (Exploratory Data Analysis) ด้วย pandas

- `day9_real_dataset_eda.ipynb`  
  วิเคราะห์ข้อมูลจริงจาก **Titanic Dataset** ตั้งแต่ขั้นตอน
  - การสำรวจข้อมูล
  - การวิเคราะห์ feature
  - การจัดการ missing values
  - การสร้าง feature ใหม่
  - การสร้าง baseline machine learning model

---

## notes/
เก็บบันทึกสรุปแนวคิดที่เรียนในแต่ละวัน

ตัวอย่าง

- `day9_note.md`

เนื้อหาภายในประกอบด้วย
- แนวคิดสำคัญที่เรียน
- keyword ที่ควรจำ
- สรุปสิ่งที่เข้าใจจากการเรียนในวันนั้น

---

## projects/
โฟลเดอร์สำหรับเก็บ **Mini Projects และ Challenge ต่าง ๆ** ที่จะทำระหว่างการเรียนรู้

ตัวอย่างที่อาจเพิ่มในอนาคต

- Data Analysis Projects
- Machine Learning Projects
- Hackathon Challenge

---

# ตัวอย่างโปรเจกต์ใน Repository

## Titanic Dataset Analysis

โปรเจกต์นี้เป็นการวิเคราะห์ข้อมูลจาก Titanic Dataset โดยมีขั้นตอนดังนี้

### 1. Data Exploration
สำรวจโครงสร้างของข้อมูล เช่น
- จำนวนแถวและคอลัมน์
- ประเภทของตัวแปร
- ค่าที่หายไป (Missing Values)

### 2. Feature Analysis
วิเคราะห์ความสัมพันธ์ระหว่างตัวแปรต่าง ๆ กับตัวแปรเป้าหมาย (`survived`)

ตัวอย่าง
- เพศกับการรอดชีวิต
- ชั้นโดยสารกับการรอดชีวิต
- ราคาตั๋วกับการรอดชีวิต

### 3. Data Cleaning
จัดการข้อมูลที่หายไป เช่น

- เติมค่า median สำหรับตัวแปร `age`
- เติมค่า mode สำหรับตัวแปร `embarked`

### 4. Feature Engineering
สร้าง feature ใหม่เพื่อช่วยให้โมเดลเรียนรู้ได้ดีขึ้น

ตัวอย่าง

**family_size**

จำนวนสมาชิกครอบครัวบนเรือ
