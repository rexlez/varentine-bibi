# Valentine's Day Web Templates

คอลเลคชั่นเทมเพลตเว็บไซต์สำหรับวันวาเลนไทน์ ประกอบด้วย 3 รูปแบบ:
- แกลอรี่รูปภาพ
- การ์ดอวยพรแบบอินเทอร์แอคทีฟ
- ร้านค้าออนไลน์

## เว็บไซต์ตัวอย่าง

- https://goragodwiriya.github.io/valentine/

- https://goragodwiriya.github.io/valentine/gallery.html

- https://goragodwiriya.github.io/valentine/lovestore.html

- https://goragodwiriya.github.io/valentine/3d.html

- https://goragodwiriya.github.io/valentine/fullscreen.html

## คุณสมบัติ
- 🎨 ดีไซน์สวยงาม ทันสมัย
- 📱 รองรับการแสดงผลบนทุกขนาดหน้าจอ (Responsive)
- 💝 เอฟเฟกต์และแอนิเมชั่นที่น่ารัก
- 🔧 ปรับแต่งง่าย
- 📦 พร้อมใช้งานทันที ไม่ต้องติดตั้งเพิ่มเติม

## โครงสร้างไฟล์
```
valentine/
├── gallery.html     # แกลอรี่รูปภาพพร้อมข้อความ
├── index.html       # การ์ดอวยพรแบบอินเทอร์แอคทีฟ
├── lovestore.html   # ร้านค้าออนไลน์
└── images/         # โฟลเดอร์เก็บรูปภาพ
```

## รายละเอียดแต่ละไฟล์

### gallery.html
แกลอรี่รูปภาพที่แสดงภาพความรักพร้อมข้อความ
- Masonry layout
- Modal แสดงรูปขนาดใหญ่
- ข้อความแสดงความรักที่ซ่อนอยู่
- หัวใจลอยประดับ

### index.html (Interactive Card)
การ์ดอวยพรแบบอินเทอร์แอคทีฟ 3D
- เอฟเฟกต์การพลิกการ์ด
- ข้อความซ่อนด้านใน
- หัวใจประดับมุมการ์ด
- แอนิเมชั่นหัวใจเต้น

### lovestore.html
ร้านค้าออนไลน์สำหรับวันวาเลนไทน์
- แสดงสินค้าในรูปแบบ Grid
- ฟอร์มสั่งซื้อสินค้า
- Newsletter subscription
- หมวดหมู่สินค้าที่น่าสนใจ

## การใช้งาน

1. ดาวน์โหลดหรือ Clone โปรเจ็กต์
```bash
git clone https://github.com/goragodwiriya/valentine.git
```

2. เปิดไฟล์ที่ต้องการใช้งานด้วยเว็บเบราว์เซอร์
   - gallery.html สำหรับแกลอรี่รูปภาพ
   - index.html สำหรับการ์ดอวยพร
   - lovestore.html สำหรับร้านค้า

3. ปรับแต่งตามต้องการ
   - เปลี่ยนรูปภาพในโฟลเดอร์ images/
   - แก้ไขข้อความในไฟล์ HTML
   - ปรับแต่งสีและสไตล์ใน CSS

## การปรับแต่ง

### เปลี่ยนรูปภาพ
1. วางรูปภาพในโฟลเดอร์ images/
2. แก้ไข src ของ `<img>` ในไฟล์ HTML
```html
<img src="images/your-image.jpg" alt="Your description">
```

### เปลี่ยนข้อความ
- gallery.html: แก้ไขอาร์เรย์ `loveQuotes`
- index.html: แก้ไขใน `message-body`
- lovestore.html: แก้ไขเนื้อหาในแต่ละ section

### ปรับแต่งสี
แก้ไขค่าสีใน CSS:
```css
:root {
  --primary-color: #ff4d6d;
  --background-color: #fff5f5;
}
```

## ผู้พัฒนา
- Email: admin@goragod.com
- GitHub: https://github.com/goragodwiriya

## License
MIT License - สามารถนำไปใช้งานได้ฟรี ทั้งเชิงพาณิชย์และไม่เชิงพาณิชย์