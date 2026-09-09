# DPU CA Lab — Cinematography

Cinema learning module for Nitade Creator Lab Learning Hub, Faculty of Communication Arts, Dhurakij Pundit University.

## ไฟล์หลัก

- `cinematography.html` — ไฟล์ต้นฉบับหลักสำหรับแก้ไข
- `index.html` — หน้าเริ่มต้นสำหรับ GitHub Pages ซึ่งต้องมีเนื้อหาตรงกับ `cinematography.html`
- `assets/` — ฟอนต์และไอคอนที่หน้าเว็บเรียกใช้ด้วย relative path

หลังแก้ `cinematography.html` ให้ซิงก์ `index.html` ก่อน Commit:

```powershell
Copy-Item -LiteralPath .\cinematography.html -Destination .\index.html -Force
```

## ทำงานสลับระหว่างคอมพิวเตอร์

ก่อนเริ่มแก้ไขทุกครั้ง:

```powershell
git pull --ff-only
git status
```

หลังแก้ไขและตรวจสอบแล้ว:

```powershell
git add .
git commit -m "อธิบายสิ่งที่แก้ไข"
git push
```

เครื่องใหม่ให้ Clone repository เพียงครั้งแรก จากนั้นใช้ขั้นตอน Pull/Commit/Push ด้านบน:

```powershell
git clone https://github.com/aohpongsathon-con/dpu-ca-lab-cinema.git
```

อย่าแก้ไฟล์พร้อมกันสองเครื่องโดยยังไม่ได้ Push งานจากเครื่องแรก และควรให้ `git status` สะอาดก่อนเปลี่ยนเครื่อง
