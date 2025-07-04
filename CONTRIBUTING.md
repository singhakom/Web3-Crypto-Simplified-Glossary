# แนวทางการมีส่วนร่วม (Contributing)

เรายินดีต้อนรับทุกท่านที่สนใจเข้ามามีส่วนร่วมกับโปรเจกต์ Web3 & Crypto Simplified Glossary & Learning Hub! การมีส่วนร่วมของคุณจะช่วยให้โปรเจกต์นี้เป็นประโยชน์ต่อทุกคนมากยิ่งขึ้น

## วิธีการมีส่วนร่วม:

### 1. การเพิ่มหรือแก้ไขคำศัพท์ (Glossary)

1.  **Fork Repository นี้:** คลิกปุ่ม `Fork` ที่มุมบนขวาของหน้า GitHub
2.  **Clone Repository ที่ Fork มา:** ดาวน์โหลดโค้ดลงเครื่องของคุณ
    ```bash
    git clone [https://github.com/YOUR_GITHUB_USERNAME/Web3-Crypto-Simplified-Glossary.git](https://github.com/YOUR_GITHUB_USERNAME/Web3-Crypto-Simplified-Glossary.git)
    ```
3.  **สร้าง Branch ใหม่:** เพื่อทำงานของคุณโดยเฉพาะ
    ```bash
    git checkout -b add-new-term-your-term-name
    ```
4.  **แก้ไขหรือเพิ่มไฟล์:**
    * ไปที่โฟลเดอร์ `glossary/`
    * **สำหรับคำศัพท์ใหม่:** สร้างไฟล์ Markdown ใหม่ (เช่น `blockchain.md`) และเขียนคำอธิบายตามรูปแบบที่เราใช้ (ดูตัวอย่างจากไฟล์อื่นๆ)
    * **สำหรับการแก้ไข:** เปิดไฟล์คำศัพท์ที่มีอยู่แล้ว และแก้ไขคำอธิบายให้ดีขึ้น
5.  **Commit และ Push การเปลี่ยนแปลงของคุณ:**
    ```bash
    git add .
    git commit -m "feat: Add new term [Your Term]"
    git push origin add-new-term-your-term-name
    ```
6.  **สร้าง Pull Request (PR):** ไปที่หน้า Repository ของคุณบน GitHub และคลิก `Compare & pull request` เพื่อส่งการเปลี่ยนแปลงมายัง Repository หลักของเรา

### 2. การเพิ่มแหล่งเรียนรู้ (Learning Resources)

1.  ทำตามขั้นตอน 1-3 ด้านบน
2.  ไปที่โฟลเดอร์ `resources/`
3.  เปิดไฟล์ `learning_resources.md` (ถ้ามี) หรือสร้างไฟล์ใหม่
4.  เพิ่มลิงก์หรือรายละเอียดของแหล่งเรียนรู้ใหม่ที่คุณแนะนำ พร้อมคำอธิบายสั้นๆ ว่าทำไมถึงมีประโยชน์
5.  ทำตามขั้นตอน 5-6 ด้านบน

### 3. การรายงานปัญหาหรือเสนอแนวคิด (Issues)

* หากคุณพบคำผิด, ข้อมูลที่ไม่ถูกต้อง, หรือมีแนวคิดสำหรับคำศัพท์ใหม่ๆ/คุณสมบัติใหม่ๆ
* ไปที่แท็บ `Issues` บน GitHub ของเรา และคลิก `New issue`
* อธิบายปัญหาหรือแนวคิดของคุณให้ชัดเจนที่สุด

### 4. การตรวจสอบ Pull Request (Reviewing PRs)

* หากคุณมีเวลาและความเข้าใจในเนื้อหา สามารถช่วยตรวจสอบ Pull Requests ที่คนอื่นส่งเข้ามา เพื่อช่วยให้โปรเจกต์พัฒนาได้เร็วขึ้น

**ข้อควรจำ:** โปรดใช้ภาษาที่สุภาพและเป็นมิตรในการมีส่วนร่วมเสมอ เราสร้างชุมชนที่เปิดกว้างและเป็นมิตร!
