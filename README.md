# Population Dashboard — Render Static Site

เว็บไซต์นี้เป็นไฟล์ HTML/CSS/JavaScript แบบ static และสามารถ deploy เป็น Render Static Site ได้โดยไม่ต้องมี backend

## Render settings
- Service type: Static Site
- Branch: main
- Root Directory: เว้นว่าง (ถ้า index.html อยู่ที่ root ของ repository)
- Build Command: เว้นว่าง
- Publish Directory: `.`

## Deploy
1. สร้าง GitHub repository ใหม่
2. อัปโหลด `index.html` ไปไว้ที่ root ของ repository และ Commit
3. เข้า Render แล้วเลือก New → Static Site
4. เชื่อมต่อ GitHub repository นี้
5. กรอกค่าตาม Render settings ด้านบน แล้วกด Create Static Site
6. เมื่อสถานะเป็น Live ให้เปิด URL ที่ลงท้ายด้วย `.onrender.com`

หมายเหตุ: หน้าเว็บโหลดฟอนต์ Google Fonts และ Three.js จาก CDN ภายนอก จึงต้องมีอินเทอร์เน็ตเพื่อให้ส่วนเหล่านั้นทำงาน/แสดงผลได้ครบ
