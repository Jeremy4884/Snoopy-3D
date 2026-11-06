# 🐶 Snoopy & Woodstock 3D (Interactive WebGL Experience)

<div align="center">

[![Live Demo](https://img.shields.io/badge/🎮%20Play%20Online-Live%20Demo-brightgreen?style=for-the-badge&logo=googlechrome&logoColor=white)](https://jeremy4884.github.io/Snoopy-3D/)
[![GitHub Pages](https://img.shields.io/badge/Hosted%20with-GitHub%20Pages-blue?style=for-the-badge&logo=github)](https://jeremy4884.github.io/Snoopy-3D/)
[![Blender](https://img.shields.io/badge/Blender-5.2-orange?style=for-the-badge&logo=blender&logoColor=white)](https://www.blender.org/)
[![Three.js](https://img.shields.io/badge/Three.js-r160-black?style=for-the-badge&logo=threedotjs&logoColor=white)](https://threejs.org/)

### 👉 [คลิกที่นี่เพื่อเข้าเล่นบนเว็บ (Play Live Experience)](https://jeremy4884.github.io/Snoopy-3D/) 👈

![Snoopy and Woodstock 3D](banner.png)

*An authentic, Charles Schulz-inspired 3D interactive web experience starring **Snoopy** and **Woodstock**.*

</div>

---

## 🌟 จุดเด่นของโปรเจกต์ (Features)
- 🚶 **Snoopy 3D Rigged Animations**:
  - **Walk**: ท่าเดินดุ๊กดิ๊กน่ารักตามต้นฉบับการ์ตูน Peanuts
  - **Wave**: ท่าโบกมือทักทายอย่างเป็นมิตร
  - **Jump**: ท่ากระโดดดีใจยกมือสองข้างสุดน่ารัก
- 🐤 **Woodstock Companion (เสกเพื่อนซี้)**:
  - บินโฉบลงมาจากด้านบนพร้อมอนิเมชันกระพือปีกวนลูป 24 เฟรม (`Woodstock_Fly`)
  - ดีไซน์ถอดแบบจากโมเดล Peanuts แท้ (แผงขน 6 แฉก, ปากทรงกระเปาะ, ตาเพชร)
- 🎵 **Soundtrack ในตัว**:
  - เครื่องเล่นแผ่นเสียงจำลองเพลงแจ๊สคลาสสิก *"Linus and Lucy"* (Vince Guaraldi Trio)
- 📱 **Mobile & Desktop Responsive**:
  - รองรับหน้าจอคอมพิวเตอร์และมือถือเต็มรูปแบบ มีแผงควบคุมแบบ Bottom Sheet Drawer ที่เปิด-ปิดได้ พร้อมปุ่มลอยควบคุมสะดวกสบาย
- 🎥 **Interactive Controls**:
  - หมุนรอบตัว 360° ได้อิสระ, ซูมเข้า-ออก, พร้อมปุ่มลัดมุมกล้อง (Perspective, ด้านหน้า, ด้านข้าง)

---

## 🎮 วิธีเข้าใช้งาน (How to Play)
เปิดผ่านบราวเซอร์ได้ทันที ไม่ต้องติดตั้งโปรแกรมเพิ่มเติม:
🔗 **[https://jeremy4884.github.io/Snoopy-3D/](https://jeremy4884.github.io/Snoopy-3D/)**

- **คอมพิวเตอร์**: คลิกซ้ายลาก = หมุน 360°, Scroll เมาส์ = ซูมเข้า/ออก
- **มือถือ / แท็บเล็ต**: ใช้นิ้วลากเพื่อหมุน, ใช้สองนิ้วขยายเพื่อซูมเข้า/ออก

---

## 📁 โครงสร้างไฟล์หลัก (Key Files)
- `index.html`: แอปพลิเคชันเว็บหลัก พัฒนาด้วย Three.js และโมเดิร์นกลาสมอร์ฟิซึม UI
- `snoopy.glb`: โมเดล 3D Snoopy พร้อม Rigging และอนิเมชัน (Walk, Wave, Jump)
- `woodstock.glb`: โมเดล 3D Woodstock พร้อมท่าบินวนลูป
- `woodstock_icon_big.png`: ไอคอน Woodstock คมชัดสำหรับ UI
- `snoopy_avatar.png`: อาร์ตเวิร์กแผ่นเสียงสำหรับเครื่องเล่นเพลง
- `banner.png`: ภาพพรีวิวตัวละครหลักสำหรับหน้ารายละเอียดโปรเจกต์

---

## 🛠️ เครื่องมือที่ใช้พัฒนา (Tech Stack)
- **Blender 5.2 LTS**: ปั้นโมเดล 3D, Rigging กระดูก, Weight Painting, Action Strips
- **Three.js (r160)**: WebGL 3D Engine, OrbitControls, AnimationMixer, ACES Filmic Tone Mapping
- **GitHub Pages**: การ Deploy และโฮสต์เว็บไซต์แบบไร้รอยต่อ

---

## ⚖️ Disclaimer
> This website is a non-commercial, fan-made project created solely for educational and research purposes. All characters, names, images, and related indicia of Snoopy and Woodstock are trademarks and registered copyrights of Peanuts Worldwide LLC. No copyright infringement is intended.
