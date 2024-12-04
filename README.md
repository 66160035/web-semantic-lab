# Web Semantic Lab 
โปรเจคนี้เป็นส่วนหนึ่งของวิชา Web Frontend Development 
## รายละเอียด 
- การใช้ Semantic HTML 
- Form Validation 
- ARIA Labels 

## git command used in this lab
ส่วนที่1
git add README.md
git commit -m "comment"
git push

ส่วนที่2
git checkout -b development
git add .
git commit -m "สร้างโครงสร้างโปรเจคเริ่มต้น"

ส่วนที่3
git checkout -b feature/homepage
git add index.html
git add contact.html
git commit -m "สร้างโครงสร้างเริ่มต้นของโปรเจค"

ส่วนที่4
git add index.html
git commit -m "เพิ่ม header และ nav ในหน้าหลัก"
git add index.html
git commit -m "เพิ่มส่วน main และ article ในหน้าหลัก
git add index.html
git commit -m "เพิ่ม aside และ footer ในหน้าหลัก"

ส่วนที่5
git checkout -b feature/contact
git add contact.html
git commit -m "สร้างโครงสร้างพื้นฐานหน้าติดต่อ"
git add contact.html
git commit -m "เพิ่มฟอร์มพื้นฐานในหน้าติดต่อ"
git add contact.html
git commit -m "เพิ่ม validation ในฟอร์มติดต่อ"

ส่วนที่6
git add contact.html
git commit -m "เพิ่ม ARIA labels ในฟอร์ม"
git add contact.html
git commit -m "เพิ่ม ARIA landmarks ในการนำทาง"

ส่วนที่8
git checkout development
git merge feature/homepage
git merge feature/contact
git push origin development