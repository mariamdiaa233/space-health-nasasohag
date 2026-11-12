# Space Health — Role-based Premium Edition

## What's included
- Separate accounts for each email address, with a role-specific registration flow.
- Registration fields adapt to the selected account type:
  - **مريض سكري:** نوع السكري والطبيب/المركز المتابع.
  - **رائد فضاء:** اسم المهمة والجهة/الفريق.
  - **شخص بالغ:** الهدف الصحي.
  - **طفل بإشراف ولي الأمر:** اسم ولي الأمر ورقم هاتفه (إلزاميان).
- A different dashboard introduction and navigation for each account type.
- A complete editable profile after registration, including personal details and role-specific information.
- Profile changes are saved to the matching account. Duplicate email addresses are rejected.
- Demo measurement records are stored separately per account email.
- Existing premium styling, Lucide icons, charts, Bluetooth demo, and health assistant are retained.

## Run
Open `index.html` in a browser. Internet access is needed to load the hosted Cairo font, Lucide icons, and Chart.js libraries. Bluetooth requires a supported browser/device and HTTPS (or localhost); replace the sample service/characteristic UUIDs in `script.js` with the actual device UUIDs.

## Important limitations
This is a front-end demonstration. Accounts, passwords, profile information, and sample readings are stored in browser `localStorage`; passwords are not securely hashed and there is no server-side authentication, synchronization, or backup. Do not enter real medical or sensitive personal information. A production system needs a secure backend, password hashing, access controls, encryption, consent, and appropriate medical/privacy review. Demo sensor readings are not medical measurements; the interface does not diagnose or recommend treatment.
