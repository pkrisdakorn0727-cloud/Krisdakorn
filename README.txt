AR Washing Machine AR Demo
===========================

ไฟล์:
- index.html  = โปรแกรม AR
- marker.html = หน้าแสดง/พิมพ์ Hiro Marker

วิธีใช้งาน:
1. เปิดโฟลเดอร์นี้ด้วยเว็บเซิร์ฟเวอร์ เช่น VS Code Live Server หรือ
   Python: python -m http.server 8000
2. เปิด http://localhost:8000/index.html
3. อนุญาต Camera
4. เปิด marker.html หรือพิมพ์ Marker จากหน้านั้น
5. ส่องกล้องไปที่ Marker
6. กด +100 / -100 เพื่อปรับความเร็วถังซัก
7. กด ▶/⏸ เพื่อเริ่ม/หยุด และ STOP เพื่อหยุดทันที

หมายเหตุ:
- ตัวเครื่องซักผ้าเป็นโมเดล 3D แบบสร้างจาก A-Frame primitives จึงไม่ต้องมีไฟล์ .glb เพิ่ม
- อินเทอร์เน็ตต้องใช้งานได้ เพราะ A-Frame และ AR.js ถูกโหลดจาก CDN
- สำหรับใช้งานจริงบนมือถือ แนะนำ deploy ผ่าน HTTPS
