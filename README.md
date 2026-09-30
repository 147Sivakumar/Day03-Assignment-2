# Day03-Assignment-2
CAIE Architect Program
It should open your installed Google Chrome, go to WhatsApp Web, and use the automation flow:
contacts.xlsx
      ↓
Open Google Chrome
      ↓
WhatsApp Web
      ↓
Search phone number
      ↓
Open chat
      ↓
Personalize {name}
      ↓
Type message
      ↓
Press Enter
      ↓
Screenshot
      ↓
Extract messages
      ↓
JSON + Excel report
## One important detail
If you mean use your existing normal Chrome profile, don't point Playwright at your everyday Chrome profile while Chrome is already running. Chrome profiles are commonly locked while Chrome is open. Your existing whatsapp_profile approach is safer for this assignment and preserves the WhatsApp login between runs.

Also, only automate messages to contacts who have agreed to receive them.
