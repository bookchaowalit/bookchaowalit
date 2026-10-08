---
title: bookchaowalit GitHub Profile — Product Card
doc_id: CARD-bookchaowalit
doc_type: product-card
verdict: showcase
version: 0.1
date: 2026-10-08
status: ร่างเพื่อพิจารณา
owner: Product owner (Book Dev)
---

# bookchaowalit GitHub Profile — Product Card

## 1. สรุปคุณค่าในหนึ่งประโยค

เป็นหน้าแรกที่ผู้จ้าง/ลูกค้าเห็นบน GitHub — แนะนำตัวตน องค์กร 10 org และโปรเจกต์เด่น แล้วชี้ไปยัง portfolio เต็ม

## 2. ปัญหาและผู้ใช้เป้าหมาย

- ปัญหา: ผู้เข้าชม GitHub ต้องเข้าใจภายในไม่กี่วินาทีว่าเจ้าของทำอะไรและควรดูอะไร
- ผู้ใช้: ผู้จ้างงาน ลูกค้า freelance และนักพัฒนาที่เข้ามาดู profile

## 3. สิ่งที่ทำได้จริงตอนนี้

- `README.md` อย่างเดียว (ไม่มีโค้ด): hero, knowledge atlas 45 domains, empire map 10 org, featured projects
- รอบ 2026-09-30 ลบตัวเลข "129 projects" ที่พิมพ์มือและพิสูจน์ไม่ได้ออกแล้ว (`docs/UPGRADE-PLAN.md`)
- ใช้บริการภายนอก (typing SVG, visitor badge, stats card) แสดงผล

## 4. หลักฐานสถานะ

| รายการ | ค่า (ตรวจจาก repository) |
|---|---|
| Stack | ไม่พบ manifest ของ stack (ตัวตรวจไม่ระบุ) |
| Commits | 24 (แรก 2022-06-26 → ล่าสุด 2026-10-01) |
| Source | 0 ไฟล์ / 0 บรรทัด |
| Tests | 0 ไฟล์ |
| CI | 0 workflow |
| Deploy config | ไม่มี |
| Live URL | https://agriculture.bookchaowalit.com, https://bookmarketing.bookchaowalit.com, https://booktrading.bookchaowalit.com, https://chat-playground.bookchaowalit.com, https://github-stats-extended.vercel.app/api, https://real-estate.bookchaowalit.com |
| README | 210 บรรทัด (`who i am`) |
| โครงสร้างซ้ำ (template family) | 1 repo ที่มี structure signature เดียวกัน |

URL ใน README เป็นลิงก์ที่อ้างถึง ไม่ได้ตรวจว่าใช้งานได้ในรอบนี้

## 5. คุณค่าและจุดต่าง

- เป็นจุดเข้าเดียวของ portfolio; คุณค่าวัดจากความซื่อตรงของข้อมูลมากกว่าความสวย
- รายได้ทางตรง: ไม่มี; ทางอ้อม: ช่วย conversion งานจ้าง **[สมมติฐาน]**

## 6. ช่องว่างสำคัญ

- พึ่งบริการภายนอกที่อาจล่ม (Upgrade plan P1)
- ตัวเลขบางอย่าง (45 domains, 5+ ปี) ยังพิมพ์มือ **[ต้องยืนยัน]**
- รูป badge/stat ยังไม่มี `alt` text

## 7. คำตัดสิน

**`showcase`** — เป็น showcase โดยธรรมชาติ ไม่ใช่ผลิตภัณฑ์ ต้องรักษาให้ซื่อตรงและทันสมัย จะไม่มีวันเป็น `invest` แต่ถ้าข้อมูลล้าสมัยจะทำลายความน่าเชื่อถือของทั้ง portfolio

## 8. ขั้นต่อไป

1. ชี้ featured projects ไปที่ repo Tier A (เช่น `book-job-scraping`, `book-migration-validation-workbench`) ที่มี product card แล้ว
2. ทำ backlog P1/P2 ใน `docs/UPGRADE-PLAN.md` (นับ repo อัตโนมัติ, alt text)
3. ตรวจลิงก์ live URL ทุกไตรมาส

## การอนุมัติ

| บทบาท | สถานะ | วันที่ | ลงนาม |
|---|---|---|---|
| Product owner (Book Dev) | รอพิจารณา | — | ________ |

## แหล่งข้อมูล

- `README.md`
- `docs/UPGRADE-PLAN.md`
