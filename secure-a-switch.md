# 🔒 Lab 5.7.6 — Secure a Switch

> **หลักสูตร:** IT Security Administration
> **ระดับ:** Network Infrastructure Security

---

### บทบาท
> คุณคือ **ผู้ดูแลระบบความปลอดภัยด้านไอที (IT Security Administrator)** ของเครือข่ายองค์กรขนาดเล็ก
> ภารกิจ: รักษาความปลอดภัยในการเข้าถึงสวิตช์ที่ยังใช้การตั้งค่าเริ่มต้นจากโรงงาน

### การเข้าสู่ระบบเริ่มต้น

| รายการ | ค่า |
|--------|-----|
| URL | `http://192.168.0.2/` |
| Username | `cisco` |
| Password | `cisco` |

> เปิดผ่านโปรแกรม **Chrome**

---

### งานที่ต้องทำ

#### ✅ ภารกิจที่ 1 — สร้างบัญชีผู้ใช้ใหม่

| รายการ | ค่า |
|--------|-----|
| Username | `ITSwitchAdmin` |
| Password | `Admin$only1844` |
| User Level | **Read/Write Management Access (ระดับ 15)** |

![สร้างบัญชี ITSwitchAdmin](image.png)

---

#### ✅ ภารกิจที่ 2 — แก้ไขบัญชีผู้ใช้เริ่มต้น

| รายการ | ค่า |
|--------|-----|
| Username | `cisco` |
| Password | `CLI$only1958` |
| User Level | **Read-Only CLI Access (ระดับ 1)** |

![แก้ไขบัญชี cisco](image-1.png)

---

#### ✅ ภารกิจที่ 3 — ขั้นตอนการสร้าง User ใหม่ (ITSwitchAdmin)

**1. เข้าเมนู**
```
Administration → User Accounts
(บางรุ่น: Security → User Management)
```

**2. คลิก** `Add` / `Add New User`

**3. กรอกข้อมูล**

```
Username         : ITSwitchAdmin
Password         : Admin$only1844
Confirm Password : Admin$only1844
User Level       : Read/Write Management Access (15)
```

**4. คลิก** `Apply` / `Save`

![กรอกข้อมูลผู้ใช้](image-2.png)

**สำเร็จ ✔**

![ผลลัพธ์](image-3.png)

---

*จัดทำโดย IT Security Lab · อัปเดต 29 มกราคม 2569*
