# นักสืบตัวจิ๋ว ตามหาของในบ้าน 🔎 (Little Detective Game)

เกมเว็บแอปพลิเคชันฝึกสายตาและการสังเกตสิ่งของในบ้านสำหรับเด็กเล็ก พัฒนาด้วย HTML5, Tailwind CSS, SVG และ Web Audio API พร้อมเสียงอ่านภาษาไทย (Thai Speech Synthesis)

---

## 🌟 ฟีเจอร์เด่น
1. **5 ด่านห้องต่าง ๆ ในบ้าน**:
   - 🛏️ **ด่าน 1: ห้องนอน** (หมอนนุ่ม, ตุ๊กตาหมี, โคมไฟ)
   - 🛋️ **ด่าน 2: ห้องนั่งเล่น** (รีโมตทีวี, หมอนอิง, แจกันดอกไม้)
   - 🍳 **ด่าน 3: ห้องครัว** (แอปเปิ้ลสีแดง, แก้วน้ำสีฟ้า, ทัพพี)
   - 🛁 **ด่าน 4: ห้องน้ำ** (เป็ดยางสีเหลือง, แปรงสีฟัน, สบู่ก้อน)
   - 🚀 **ด่าน 5: ห้องของเล่น & สวน** (ลูกบอลหลากสี, เครื่องบินของเล่น, แว่นขยายสีทอง)
2. **ระบบเสียงในตัว 100% ไม่พึ่งพาไฟล์ภายนอก**:
   - Web Audio API สร้างเสียงเอฟเฟกต์ (Chimes, Thud, Fanfare) แบบเรียลไทม์
   - Web Speech API อ่านออกเสียงคำสั่งเป็นภาษาไทย 🔊
3. **ระบบคะแนนและรางวัล**:
   - สะสมดาวสูงสุด 15 ดวง (ด่านละ 3 ดวง)
   - เอฟเฟกต์ประกายดาว (Sparkles) และพลุฉลอง (Confetti)
   - ถ้วยรางวัลชนะเลิศเมื่อผ่านครบทั้ง 5 ด่าน

---

## 🚀 วิธีเอาขึ้น GitHub (Deploy to GitHub)

1. สร้าง Repository ใหม่บน GitHub: [https://github.com/new](https://github.com/new)
   - ตั้งชื่อ เช่น `detective-kids-game`
2. เปิด Terminal ในโฟลเดอร์นี้ แล้วรันคำสั่ง:
   ```bash
   git remote add origin https://github.com/YOUR_USERNAME/detective-kids-game.git
   git branch -M main
   git push -u origin main
   ```

---

## ⚡ วิธี Deploy บน Vercel

### วิธีที่ 1: Deploy ผ่าน GitHub (แนะนำ สะดวกที่สุด)
1. ไปที่ [https://vercel.com/new](https://vercel.com/new)
2. เลือก Import repository `detective-kids-game` จาก GitHub
3. กดปุ่ม **Deploy** ได้ทันที (Vercel จะตรวจจับเป็น Static Site อัตโนมัติและให้ URL ใช้งานได้ทันที)

### วิธีที่ 2: Deploy ผ่าน Vercel CLI
เปิด Terminal ในโฟลเดอร์นี้แล้วรัน:
```bash
npx vercel
```
ทำตามขั้นตอนบนหน้าจอเพื่อล็อกอินและยืนยันการ Deploy
