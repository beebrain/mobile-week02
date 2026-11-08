# สัปดาห์ที่ 2 ใช้ Git ทำงานจริง (add, commit, push)

ทำตามใบงานที่ 2 ทีละขั้น คำตอบเขียนลงในใบงาน (กระดาษ) ส่งงานเป็นลิงก์คลัง `https://github.com/<ชื่อผู้ใช้>/mobile-week02`

## เปิดเทอร์มินัล
ในคลังของตน กดปุ่ม **Code** > แท็บ **Codespaces** > **Create codespace on main** แล้วพิมพ์คำสั่งในแถบ TERMINAL ด้านล่าง
(ถ้ามีคำถาม *Do you trust the authors...* ให้กด **Trust Folder & Continue**)
หรือใช้ Git ในโน้ตบุ๊กของตนเอง (`git clone https://github.com/<ชื่อผู้ใช้>/mobile-week02.git`) ตามภาคผนวกท้ายใบงาน

## ไฟล์ที่ต้องแก้: `week02/index.html`
แก้ทีละ TODO เปลี่ยนเฉพาะ `...` (อย่าลบ `<p>` และ `</p>`) บันทึกไฟล์ แล้วคอมมิตด้วยข้อความตามใบงานทุกตัวอักษร

```
git add week02/index.html
git commit -m "เพิ่มชื่อเล่นในหน้า week02"     # หลังแก้ TODO 1
git add week02/index.html
git commit -m "ระบุสาขาวิชา"                  # หลังแก้ TODO 2
git add week02/index.html
git commit -m "เพิ่มชื่อร้านโครงงาน"            # หลังแก้ TODO 3
git push
```

ผู้สอนตรวจจากประวัติคอมมิตบน GitHub ห้ามแก้ไฟล์ด้วยปุ่มดินสอบนเว็บ

## ดูผล
`https://<ชื่อผู้ใช้>.github.io/mobile-week02/week02/` (เปิด Pages ก่อน: Settings > Pages > Deploy from a branch > main)

## ก่อนเลิก
`git status` ต้องขึ้น `up to date with 'origin/main'` แล้ว Stop codespace ที่ https://github.com/codespaces

## โฟลเดอร์ workshop
`workshop/` เป็นไฟล์ฝึกเพิ่มเติม ไม่ต้องส่ง · อย่าลบคลังนี้ ใบงานที่ 3 ใช้ต่อ
