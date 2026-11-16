# สรุปโครงงาน Mobile & Web Week 02: ร้านขายม้า Royal Equine

เว็บไซต์หน้าร้านขายม้าและฟาร์มเพาะพันธุ์ม้าสายพันธุ์แท้ระดับพรีเมียม (Single Page Web Application)
พร้อมส่วนแนะนำตัวผู้จัดทำโครงงาน (Student Profile & Lab Banner)

---

## 🌟 ฟีเจอร์ที่ได้รับการอัปเดตและตกแต่ง (Enhancements)

1. **ส่วนแนะนำตัวผู้จัดทำโครงงาน (Top Profile & Lab Week 02 Banner)**
   - แถบสถานะด้านบนระบุโครงงาน Week 02 ชัดเจน
   - แสดง **ชื่อเล่น**, **สาขาวิชา**, และ **ร้านโครงงาน: ร้านขายม้า Royal Equine**
   - มีปุ่ม Interactive Edit ให้คลิกแก้ไขชื่อเล่นหรือสาขาวิชาได้สดๆ บนหน้าเว็บ พร้อมจำค่าลงใน `localStorage`
   - สามารถแก้ไขข้อความได้โดยตรงในโค้ด HTML บรรทัดที่ 80-110

2. **ดีไซน์หรูหราแบบ Modern Equestrian Luxury**
   - โทนสีเขียวบริติชเรซซิ่งกรีน (`Noble Forest Green`), สีทองแชมเปญ (`Warm Gold`), และพื้นหลังอบอุ่นสไตล์คลับเฮาส์ยุโรป
   - ฟอนต์คู่ระดับพรีเมียม: **Prompt** (ภาษาไทยคมชัดอ่านง่าย) + **Playfair Display** (หัวข้อภาษาอังกฤษทรงเสน่ห์)
   - เอฟเฟกต์ Glassmorphism, เงา Soft Shadows, และ Hover Micro-interactions

3. **ระบบค้นหาและกรองม้าอัจฉริยะ (Smart Filters)**
   - ค้นหาตามคำสำคัญ (ชื่อม้า, สายพันธุ์, ส่วนสูง) แบบ Real-time
   - กรองตามสายพันธุ์ (Friesian, Arabian, Warmblood, Thoroughbred, Andalusian, Pony, Gypsy Vanner)
   - กรองตามประเภทการใช้งาน (Show Jumping, Dressage, สันทนาการ, ม้าสำหรับเด็ก)
   - จัดเรียงตามราคาและอายุ

4. **แคตตาล็อกม้า 8 รายการ พร้อมสเปกเจาะลึก**
   - ภาพถ่ายม้าความละเอียดสูง
   - ป้ายกำกับเกรดม้าและรางวัล
   - ป๊อปอัปดูข้อมูลเชิงลึก (Detail Modal) พร้อม **ผังสายเลือด (Pedigree Tree: Sire, Dam, Studbook)** และผลตรวจสุขภาพ (Coggins Test EIA)

5. **ระบบรายการโปรดและนัดหมาย (Wishlist & Direct Booking)**
   - ปุ่มหัวใจบันทึกม้าที่สนใจ พร้อมแถบแจ้งเตือน Toast แจ้งสถานะ
   - ลิ้นชัก Wishlist ด้านขวา สามารถกด **"นัดดูม้าทั้งหมดที่เลือก"** เพื่อนำชื่อม้าทั้งหมดไปกรอกในแบบฟอร์มนัดหมายอัตโนมัติ

---

## 🚀 วิธีเปิดใช้งาน
- ดับเบิ้ลคลิกเปิดไฟล์ [`Untitled-2.html`](file:///d:/mobile-week02/Untitled-2.html) หรือ [`index.html`](file:///d:/mobile-week02/index.html) ใน Google Chrome หรือ Microsoft Edge ได้ทันที
