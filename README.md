# Dji Trello AI-Powered Autonomous Drone Control System 
  โปรเจกต์ควบคุมโดรน DJI Tello ด้วยภาษา Python ที่ผสมผสานระหว่างการควบคุมแบบ Manual (GUI/Keyboard) และการควบคุมแบบ 
  AI (Computer Vision) โดยใช้ Mediapipe ในการตรวจจับท่าทาง (Pose) และท่าทางมือ (Hand Gestures)

# ฟีเจอร์เด่น (Key Features)
- Keyboard Control: ควบคุมทิศทางการบินผ่านแป้นพิมพ์ (WASD, Arrow Keys) พร้อมหน้าจอ GUI ด้วย Tkinter
- Live Video Stream: แสดงผลภาพจากกล้องหน้าโดรนแบบ Real-time
- AI Follow Me (PID Control): ระบบบินติดตามบุคคลอัตโนมัติ โดยใช้ Mediapipe Pose Detection และอัลกอริทึม PID Controller เพื่อความนุ่มนวลในการเคลื่อนที่
- Gesture Command: * ยกแขนซ้าย/ขวา เพื่อสั่งให้โดรนเคลื่อนที่ตามทิศทาง
- ชู 2 นิ้ว (สัญลักษณ์ Peace) เพื่อสั่งถ่ายภาพและบันทึกไฟล์อัตโนมัติ
- Safety Features: ระบบ Landing อัตโนมัติเมื่อสิ้นสุดโปรแกรม

# เทคโนโลยีที่ใช้ (Tech Stack)
- Python 3.x
- DJITelloPy: สำหรับเชื่อมต่อและส่งคำสั่ง SDK ของ Tello
- OpenCV: ประมวลผลภาพ (Image Processing)
- Mediapipe: ตรวจจับ Pose และ Hand Landmarks
- Tkinter & Pillow: สร้างหน้าต่าง GUI และจัดการการแสดงผลรูปภาพ
- NumPy: คำนวณค่าทางคณิตศาสตร์สำหรับ PID Control


# การติดตั้ง (Installation)
Clone โปรเจกต์:
- git clone https://github.com/your-username/your-repo-name.git
- cd your-repo-name

ติดตั้ง Library ที่จำเป็น:
- pip install djitellopy opencv-python mediapipe pillow numpy


<img width="1100" height="621" alt="image" src="https://github.com/user-attachments/assets/5a7f0f5c-92a1-4c91-b1d1-aaeab8b848e0" />
<img width="1097" height="613" alt="image" src="https://github.com/user-attachments/assets/26480347-4191-48f1-985b-5daf2dd46744" />

