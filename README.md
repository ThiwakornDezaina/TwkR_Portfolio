# Thiwakorn Reanluk Portfolio

เว็บไซต์พอร์ตโฟลิโอสำหรับ **Thiwakorn Reanluk** นักออกแบบ UX/UI และ Product Designer ภายในเว็บไซต์ประกอบด้วยหน้าแนะนำตัว ผลงานที่คัดเลือก และ case study ของแต่ละโปรเจ็กต์

## ฟีเจอร์

- หน้า portfolio หลักพร้อมส่วนแนะนำตัว ผลงาน เกี่ยวกับผู้สร้าง และช่องทางติดต่อ
- case study แยกตามโปรเจ็กต์ พร้อมรายละเอียด Problem, Goal, Challenge และ Design Approach
- รองรับธีมมืดและธีมสว่าง โดยจดจำค่าธีมผ่าน `localStorage`
- responsive layout สำหรับ desktop และ mobile
- custom cursor และ animation สำหรับ interaction บน desktop
- image lightbox สำหรับดูภาพในหน้า case study
- ใช้ Google Fonts และ Font Awesome ผ่าน CDN

## ผลงาน

| โปรเจ็กต์                     | หน้าเว็บ                                           |
| ----------------------------- | -------------------------------------------------- |
| SomeBank                      | [project-somebank.html](project-somebank.html)     |
| Corporate Digital Gold Saving | [project-goldsaving.html](project-goldsaving.html) |
| Regulation Library (RLS)      | [project-rls.html](project-rls.html)               |
| VR Seeker                     | [project-vrseeker.html](project-vrseeker.html)     |
| Grearot                       | [project-grearot.html](project-grearot.html)       |

## โครงสร้างโปรเจ็กต์

```text
.
├── index.html                  # หน้า portfolio หลัก
├── project-somebank.html       # Case study: SomeBank
├── project-goldsaving.html     # Case study: Corporate Digital Gold Saving
├── project-rls.html            # Case study: Regulation Library
├── project-vrseeker.html       # Case study: VR Seeker
├── project-grearot.html        # Case study: Grearot
├── images/                     # ภาพ hero ของผลงาน
└── README.md
```

## การเปิดใช้งาน

โปรเจ็กต์นี้เป็น static website จึงไม่ต้องติดตั้ง package หรือ build ก่อนใช้งาน

### วิธีที่ 1: เปิดไฟล์โดยตรง

ดับเบิลคลิก `index.html` หรือเปิดไฟล์ผ่าน browser จากนั้นเลือกผลงานเพื่อดูรายละเอียดแต่ละ case study

### วิธีที่ 2: ใช้ local server

การใช้ local server ช่วยให้การทำงานใกล้เคียงกับการ deploy มากขึ้น ตัวอย่างเช่นใช้ Python:

```bash
python -m http.server 8000
```

จากนั้นเปิด [http://localhost:8000](http://localhost:8000) ใน browser

หรือใช้ extension **Live Server** ใน VS Code แล้วกด **Go Live**

## เทคโนโลยี

- HTML5
- CSS3 พร้อม CSS custom properties และ responsive design
- Vanilla JavaScript
- Google Fonts: Space Grotesk, Inter และ JetBrains Mono
- Font Awesome 6.5.1

## หมายเหตุ

- ไม่จำเป็นต้องใช้ Node.js, npm หรือ framework ใด ๆ
- ฟอนต์และไอคอนจาก CDN ต้องเชื่อมต่ออินเทอร์เน็ต หากเปิดแบบออฟไลน์อาจใช้ฟอนต์สำรองและไม่แสดงไอคอนบางส่วน
- ภาพ hero ถูกเก็บไว้ใน `images/` ส่วนภาพประกอบจำนวนมากถูกฝังอยู่ในไฟล์ HTML เป็น Base64
- ข้อมูลติดต่อและลิงก์ภายนอกอยู่ในส่วน Contact ของแต่ละหน้า

## ติดต่อ

- Email: [thiwakorn.dezaina@gmail.com](mailto:thiwakorn.dezaina@gmail.com)
- LinkedIn: [thiwakorn-rl](https://www.linkedin.com/in/thiwakorn-rl/)
- Resume: [Google Drive](https://drive.google.com/file/d/1_47kL6livkH-yhhtXA3gw_jvgUJSWFVs/view?usp=sharing)
