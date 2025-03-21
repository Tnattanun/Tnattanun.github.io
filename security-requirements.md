# Business Logic Architecture 
## Business Logic Architecture : 
- Verify that all high-value business logic flows, including authentication, session management and access control, do not share unsynchronized state.  
## Source : 
- [https://wiki.owasp.org/images/d/d4/OWASP_Application_Security_Verification_Standard_4.0-en.pdf](https://wiki.owasp.org/images/d/d4/OWASP_Application_Security_Verification_Standard_4.0-en.pdf)
## Chat GPT
- การตรวจสอบให้แน่ใจว่า กระบวนการทางธุรกิจที่มีมูลค่าสูงทั้งหมด เช่น การยืนยันตัวตน, การจัดการเซสชัน และการควบคุมการเข้าถึง จะไม่ใช้สถานะ (state) ที่ไม่ได้รับการซิงโครไนซ์ร่วมกัน ซึ่งหมายถึงการตรวจสอบว่าแต่ละกระบวนการเหล่านี้ไม่ได้แชร์ข้อมูลหรือสถานะที่อาจทำให้เกิดความขัดแย้งหรือข้อผิดพลาด เนื่องจากการซิงโครไนซ์ไม่ถูกต้อง หรือไม่ได้รับการจัดการอย่างเหมาะสมในหลายๆ ตัวแปรที่เกี่ยวข้อง
## Gemini
- ตรวจสอบว่าขั้นตอนการทำงานเชิงธุรกิจที่มีมูลค่าสูงทั้งหมด รวมถึงการตรวจสอบสิทธิ์ การจัดการเซสชัน และการควบคุมการเข้าถึง ไม่ได้ใช้สถานะที่ไม่ซิงโครไนซ์ หมายถึง การตรวจสอบให้แน่ใจว่าส่วนสำคัญของระบบซอฟต์แวร์ทำงานกับข้อมูลอย่างสอดคล้องและเชื่อถือได้ โดยเฉพาะอย่างยิ่งเมื่อผู้ใช้หรือกระบวนการหลายอย่างเกี่ยวข้องพร้อมกัน
## My Summary
- การตรวจสอบการทำงานทางธุรกิจ เช่น การยืนยันตัว, การควบคุมการเข้าถึง จะไม่ใช้ state ที่ไม่ได้รับการซิงโครไนซ์ หมายถึง การตรวจสอบว่าระบบสามารถทำงานร่วมกันได้ แม้จะทำกระบวนการหลายอย่างพร้อมกัน
## Sample
- ล็อกอิน facebook ในโทรศัพท์ แต่ในคอมพิวเตอร์ก็ล็อกอินอยู่ด้วย ทำให้สามารถเข้าถึงข้อมูลใน facebook จากทั้งสองเครื่องได้

## Partner
[Pongpipat](https://6530200711.github.io/security-requirements)
