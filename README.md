# ✨ ChaoNueaChok (เจ้าเหนือโชค)

Static website รวม **เลขเด็ด ดูดวง ทำนายฝัน ข่าวลี้ลับ และเคล็ดลับความเชื่อ**  
ไม่มีฐานข้อมูล (HTML + CSS + JS เท่านั้น) — เหมาะกับ GitHub Pages

## 🚀 Deploy
1) สร้าง repo: `ChaoNueaChok` (Public)  
2) อัปโหลด `index.html` + `README.md`  
3) Settings → Pages → Deploy from branch (`main` / root)  
4) เปิด: `https://<username>.github.io/ChaoNueaChok/`

## 🛠 อัปเดตเนื้อหา
แก้ไขในบล็อก `<script>` ตัวแปร `SITE`:
- `todayNumbers`, `newsNumbers`, `dreamNumbers`, `templeNumbers`
- `daily` (love, money, work)
- `mysteryNews`, `tips`, `chants`
- `dreamBook` (คลังทำนายฝัน — ตอนนี้มี 40+ รายการ เพิ่มได้ไม่จำกัด)
- `tagline` (แก้ข้อความใต้ชื่อแบรนด์ในหัวเว็บ)

## 🧪 ฟีเจอร์เด่น
- Header มี **Logo Text + Tagline** (“Master of Fortune & Luck”)
- กล่องค้นหา “ทำนายฝัน” (ค้นจาก `dreamBook`)
- การ์ดข่าวลี้ลับ/ทิป/คาถาแบบสวย ๆ (ไม่มี lib ภายนอก)
- เร็วและเบา เหมาะกับมือถือ

## 📄 โครงสร้าง
```
ChaoNueaChok/
├─ index.html   # หน้าเว็บหลัก (ครบทุกหมวด + dream search + tagline)
└─ README.md    # วิธีใช้งาน
```
