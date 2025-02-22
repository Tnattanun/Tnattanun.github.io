# Topic : Data Consistency
## Definition  
- Data consistency refers to the state of data in which all copies or instances are the same across all systems and databases. Consistency helps ensure that data is accurate, up-to-date, and coherent across different database systems, applications, and platforms.
## [decube](https://www.decube.io/post/what-is-data-consistency-definition-examples-and-best-practice)  
- Data consistency is a crucial aspect that ensures the accuracy and reliability of data. So if data is inconsistent, there is nothing right
Data consistency is the accuracy, completeness, and correctness of data stored in a database. The same data across all related systems, applications, and databases is when we say that data is consistent. Inconsistent data can lead to incorrect analysis, decision-making, and outcomes.
## Chat GPT  
- Data Consistency หมายถึง สภาวะของข้อมูลที่ข้อมูลทั้งหมดในระบบหรือฐานข้อมูลต่าง ๆ มีความสอดคล้องกัน (consistent) ทั้งในแง่ของความถูกต้อง (accuracy) ความครบถ้วน (completeness) และการอัปเดตข้อมูล (up-to-date) เพื่อให้มั่นใจว่าข้อมูลที่เก็บในระบบต่าง ๆ หรือระบบกระจาย (distributed systems) เป็นข้อมูลที่เหมือนกันและถูกต้องในทุกสำเนาหรือทุก instance ที่เกี่ยวข้อง
## Gemini
- Data Consistency หมายถึง สภาพที่ข้อมูลทั้งหมดในระบบมีความถูกต้องและสอดคล้องกัน ไม่ว่าจะถูกเก็บไว้ในที่ใด หรือถูกเข้าถึงโดยใครก็ตาม นั่นคือ ข้อมูลทุกชิ้นจะต้องมีความหมายและค่าที่เหมือนกันเสมอ ไม่ว่าจะถูกดึงมาใช้งานเมื่อไร
## My Summary  
- Data Consistency คือ ข้อมูลที่ต้องความถูกต้อง (accurate), ครบถ้วน (complete), ทันสมัย (up-to-date) และสอดคล้องกัน (consistent) ในทุกระบบที่เกี่ยวข้อง เพื่อป้องกันข้อผิดพลาดในการวิเคราะห์และการดำเนินงาน
## Sample  
### ระบบจองตั๋วเครื่องบินหรือโรงแรม
- เมื่อคุณจองตั๋วเครื่องบินหรือโรงแรมผ่านแอป
ระบบจะต้องอัปเดตสถานะที่นั่งหรือห้องพักในทุกแพลตฟอร์ม เช่น เว็บไซต์, แอปพลิเคชัน, และฐานข้อมูลของบริษัท
หากที่นั่งหรือห้องพักถูกจองแล้ว ระบบอื่นต้องไม่สามารถแสดงสถานะว่าที่นั่งหรือห้องว่าง
- ป้องกันเรื่อง
ลูกค้าหลายคนอาจจองที่นั่งเดียวกัน และสร้างปัญหาเมื่อต้องแก้ไขข้อผิดพลาด
### ระบบธนาคาร
- คุณถอนเงิน 1,000 บาทผ่านตู้ ATM
ยอดเงินในบัญชีของคุณต้องอัปเดตทันทีในทุกช่องทาง เช่น แอปพลิเคชัน, ตู้ ATM อื่น ๆ และระบบธนาคารสาขา
ข้อมูลการทำธุรกรรม (transaction) ต้องถูกบันทึกในประวัติการใช้งานในทุกที่
- ป้องกันเรื่อง
ยอดเงินที่แสดงในแอปและตู้ ATM อาจไม่ตรงกัน ทำให้เกิดความสับสน
