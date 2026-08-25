FlowFin - แอปจดเงินกระเป๋าตุ้ม (สำหรับนักเรียน/นักศึกษา)
เว็บแอปตัวเล็กๆ ไว้จดรายรับ-รายจ่ายส่วนตัว ทำมาเพื่อแก้ปัญหาประจำเดือนที่ว่า "เงินหายไปไหนหมด?" โดยเน้นความเร็วในการใช้งาน ไม่ต้องสมัครบัญชีให้วุ่นวาย เปิดมากดเซฟได้เลย

มีฟีเจอร์อะไรบ้าง?
ตั้งงบประมาณรายวัน: บอกเลยว่าวันนี้เหลือใช้ได้อีกกี่บาท กันเหลือตังค์ลอยไปซื้อของฟุ่มเฟือย
แชร์ค่าใช้จ่าย/จดหนี้เพื่อน: กินหมูกระทะไป 500 แชร์ 4 คน แอปจะคำนวณให้ว่าเพื่อนค้างเราอยู่กี่บาท และรองรับการ "จ่ายบางส่วน" ด้วย ไม่ต้องรอให้โอนมาพร้อมกัน
ติดตามของผ่อน: ใส่ค่างวดและจำนวนงวดได้เลย แล้วกดจ่ายงวดทุกเดือน แอปจะหักเงินออกจากกระเป๋าให้อัตโนมัติ
ปลอดภัย 100%: ข้อมูลเก็บไว้ในเครื่องของคุณเอง (LocalStorage) ไม่มีใครเห็นประวัติการเงินของคุณได้นอกจากคนที่หยิบมือถือคุณไปเปิด

วิธีใช้งาน

1. เข้าไปที่ลิงก์เว็บไซต์: (https://poodlt986-dev.github.io/money.app/)
2. เริ่มกดเพิ่มรายรับหรือรายจ่ายได้เลย
3. แตะที่การ์ด "เหลือใช้ได้วันนี้" เพื่อตั้งงบประมาณ (ต้องมีรายรับก่อนนะ ไม่งั้นจะตั้งไม่ได้)
4. ข้อมูลจะถูกเซฟอัตโนมัติ ปิดเว็บแล้วเปิดใหม่ข้อมูลก็ยังอยู่ครบ
(คำแนะนำ: แอปจะใช้ได้ดีที่สุดถ้าเปิดผ่าน Google Chrome ในมือถือนะครับ)

English Version
FlowFin - Personal Expense Tracker (For Students)
A simple web app for tracking personal income and expenses. Built to solve the classic monthly question: "Where did all my money go?" It's designed for speed—no sign-ups or logins required. Just open it and start typing.

Features
Daily Budget Limit: Shows exactly how much money you have left to spend today, helping you avoid blowing your budget on impulse buys.
Split Bills & Debt Tracking: If you paid 500 for a shared meal split 4 ways, the app calculates who owes you what. It even supports partial payments, so you don't have to wait for everyone to pay up at once.
Installment Tracker: Enter your monthly installment amount and total months. When you click "Pay" each month, it automatically deducts the amount from your wallet.
100% Private & Secure: All data is saved locally on your device (LocalStorage). No one can see your financial history unless they physically have your phone.

How to use

1. Go to the website link: (https://poodlt986-dev.github.io/money.app/)
2. Start adding your income or expenses.
3. Tap the "Remaining today" card to set a daily budget (Note: You must log some income first before setting a budget).
4. Data saves automatically. Close the tab, reopen it later, and your records will still be there.
(Tip: For the best experience, use this app on Google Chrome on your mobile phone.)

Tech Stack
Built simply with pure HTML, CSS, and JavaScript. No databases, no servers. It runs anywhere, anytime.




อัปเดตเวอร์ชั่น 1.5
อัปเดตครั้งนี้เป็นการฟิกบัคและปรับปรุงประสบการณ์การใช้งาน (UX/UI) ให้ลื่นไหลขึ้นกว่าเดิม รวมถึงเพิ่มฟีเจอร์ที่หลายคนขอเข้ามา!

🌍 รองรับ 2 ภาษา (ไทย/อังกฤษ): เพิ่มปุ่มสลับภาษาที่มุมขวาบน กดเดียวเปลี่ยนภาษาทั้งหมดทันที แถมแอปจำภาษาที่คุณเลือกไว้ได้ด้วย ไม่ต้องตั้งใหม่ทุกครั้งที่เข้าใช้
🎯 แยกยอดบิล/ผ่อน ออกจากเงินใช้ได้รายวัน: แก้บัคที่ค่าบิลหรือค่าผ่อนไปหักจาก "เงินที่เหลือใช้ได้วันนี้" ตอนนี้ค่าใช้จ่ายคงที่เหล่านี้จะถูกหักออกจากยอดคงเหลือรวมเท่านั้น ทำให้เราเห็นเงินที่ใช้จ่ายสุรุ่ยสุร่ายได้ตรงๆ ไม่ติดลบระหว่างวัน
📂 ปรับ UI หน้าการเงินใหม่: เดิมทีหน้าการเงินจะยาวเหยียดเลื่อนไม่จบ ตอนนี้เปลี่ยนเป็นระบบเมนูแบบกดเพื่อกาง/พับ (Accordion) ทำให้หน้าจอดูสะอาดตาและเข้าถึงข้อมูลที่อยากดูได้ง่ายขึ้น
📅 จำกัดการจ่ายงวดผ่อน: กดจ่ายค่างวดได้แค่ 1 ครั้งต่อเดือน เพื่อกันกดผิดซ้ำๆ พอจ่ายไปแล้วปุ่มจะหายไปรอเดือนถัดไป
🔔 แจ้งเตือนกระพริบ: เพิ่มจุดแดงกระพริบที่เมนูการเงินด้านล่าง ตอนมีบิลหรือค่าผ่อนใกล้ถึงกำหนด (ภายใน 7 วัน)
🛠️ แก้บัคแจ้งเตือนค้างจอ: แก้ไขปัญหาข้อความแจ้งเตือน (Toast) ค้างอยู่ด้านล่างจอไม่ยอมหายไปในมือถือบางรุ่น
⚙️ เพิ่มปุ่มรีเซ็ตข้อมูล & ลายน้ำ: เพิ่มปุ่มกู้คืนค่าเริ่มต้นสำหรับคนที่อยากเริ่มต้นใหม่ และใส่ลายน้ำ "Dev by Phudit" ไว้ด้านล่างสุด
💾 ระบบสำรองข้อมูล (Export/Import): สามารถโหลดไฟล์สำรองข้อมูลมาเก็บในเครื่อง หรืออัปโหลดกลับเข้าแอปได้เวลาเปลี่ยนมือถือ กันข้อมูลหาย

Version 1.5 Updates
This update focuses on bug fixes, UX/UI improvements, and adding highly requested features!

🌍 Bilingual Support (Thai/English): Added a language toggle button in the top right corner. It translates the entire app instantly and remembers your preference for the next time you open it.
🎯 Separated Bills/Installments from Daily Budget: Fixed a bug where fixed expenses reduced the "Left for today" budget. Now, bills and installments only deduct from the total balance, giving you an accurate view of your flexible spending money for the day without it going negative unexpectedly.
📂 Redesigned Finance Page UI: The Finance page used to be too long. We implemented an Accordion layout (collapsible sections), making the screen much cleaner and easier to navigate.
📅 Monthly Installment Limit: You can now only pay an installment once per month to prevent accidental double-payments. The button disappears after paying and resets the next month.
🔔 Blinking Notifications: Added a blinking red dot on the bottom Finance menu tab when bills or installments are due soon (within 7 days).
🛠️ Fixed Stuck Toast Bug: Fixed an issue on some mobile devices where the toast notification message would get stuck at the bottom of the screen and refuse to disappear.
⚙️ Reset Data & Watermark: Added a "Reset All Data" button for those who want a fresh start, and a "Dev by Phudit" watermark at the bottom of the app.
💾 Backup System (Export/Import): You can now export your data as a backup file to your device and import it back into the app when switching phones, preventing data loss.
