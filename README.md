# CodeTest_300620_NOPROBLEM_OTA
แก้ปัญหา OTA ทดสอบ 30/06/2020
Node 30/06/20
Code ทดสอบ ที่ มี task OTA โดยที่ การทำงานส่งข้อมูล Machine read from ram ได้ 
แต่ยังควบคุม เวลาการส่ง ตาม config ไม่ได้ ยังคง ส่งทุกๆ 1 วิ  คงต้องทำ task send realtime แล้วเรียกใช้ใน task นี้ 
และ เมื่อสั่ง OTA ก็งาน เลย โดยไม่ติดขัด 
